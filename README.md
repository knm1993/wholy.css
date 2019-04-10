# wholy.css
wholy.css is a simple, useful and really small style sheet, which is specialized in printing documents. 
 
## Introduction
wholy.css borns when I did a project on printing html as PDF, and I found that these codes come in handy when the bootstrap doesn't work well with a printed PDF.  
How simple is it? One stylesheet, three classes and that's it.

## Installation
You may choose one of the following method to install the wholy.css
1. Copy the wholy.css content into your html file, under the head>style tag.
2. Copy the wholy.css to your working folder, reference it as an external stylesheet.
```
<head>
    <link rel="stylesheet" href="./<YOUR_PROJECT>/<WELL_MANAGED_PATH>/wholy.css">
</head>
```

## Glossary
### wholyshit 
It allows you to make a div becomes one pack, never breaks again.
```
.wholyshit {
    page-break-inside: avoid !important;
}
```
### whonypage 
It allows you to insert a page break, put it in an empty div class.
```
.whonypage {
    page-break-after: always !important;
}
```
### whorybreaker
A simple and nice horizontal line break for your html printing. Neat ,tide and visible grey line, use an empty div to bring some holy light to your documents.
```
.whorybreaker {
    border-bottom: solid;
    height: 4px;
    color: #DDDDDD;
}
```