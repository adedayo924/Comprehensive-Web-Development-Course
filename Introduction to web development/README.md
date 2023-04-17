This is the basic documentation file for html
# Html Basic Structure
## 1. Document Declaration: Also known as DOCTYPE
```
<!DOCTYPE html>
```
## 2. Opening and Closing Html tags
First html tags must be opened and closed after which other tags will be within the opened and closed html tags, such as in the illustration below:
```
<html>
    ...............
</html>
```
## 3. Head Section:
This section works like back end of any computer program apart from the title tags. it contains all the background information about your web page like metadata which contains descriptive info of your page, links, css, javascript, favicon, fonts etc.
A typical example is here below:
```
    <head>
       <meta charset="UTF-8">
       <meta http-equiv="X-UA-Compatible" content="IE=edge">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Head Section</title> 
    </head>
```
## 4. Body Section:
This section contains everything visible a clients get to see on a web page. This include headers, tags, images, href links, audio, video, etc.
```
    <body>
        ...........
    </body>
```
## 5. Others:
This include: Elements, Paragraphs, blockquotes, tags, links, horizontal rule, line breaker, headers etc.

### Tags
tags are mostly defined in two forms: Opening tag and closing tag
#### Opening tag
```
    < >
```
#### Closing tag
```
    </ >
```

### Headers
There are six types of headers numbering from 1 to 6 (h1 to h6). The higher the number the lower the size of the text.
Typical example:
```
    <h1>Welcome to Jeilo CDW!</h1>
    <h2>Want to learn how to code?</h2>
    <h3>Then you have come to the right place!</h3>
    <h4>So get started now!</h4>
    <h5>with the knowledge of headers and their tags</h5>
    <h6>and there are Six types H1 to H6.</h6>
```