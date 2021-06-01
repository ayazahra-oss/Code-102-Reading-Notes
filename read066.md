## What is CSS?
**CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.**
**in the Introduction to HTML module we covered what HTML is, and how it is used to mark up documents. These documents will be readable in a web browser. Headings will look larger than regular text, paragraphs break onto a new line and have space between them. Links are colored and underlined to distinguish them from the rest of the text. What you are seeing is the browser's default styles — very basic styles that the browser applies to HTML to make sure it will be basically readable even if no explicit styling is specified by the author of the page.**

## How To Add CSS?
**Three Ways to Insert CSS**
**There are three ways of inserting a style sheet:**

**External CSS**
**Internal CSS**
**Inline CSS**
##  External CSS
 With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

### Example
### External styles are defined within the <link> element, inside the ### <head> section of an HTML page:

 <!DOCTYPE html>
 <html>
 <head>
#### <link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

An external style sheet can be written in any text editor, and must be saved with a .css extension.

The external .css file should not contain any HTML tags.
  
Inline CSS
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

Example
Inline styles are defined within the "style" attribute of the relevant element:

<!DOCTYPE html>
<html>
<body>

#### <h1 style="color:blue;text-align:center;">This is a heading</h1>
#### <p style="color:red;">This is a paragraph.</p>

</body>
</html>

## Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.

Example
Internal styles are defined within the <style> element, inside the <head> section of an HTML page:

<!DOCTYPE html>
<html>
<head>
<style>
body {
 ####  background-color: linen;
#### }

#### h1 {
 #### color: maroon;
 #### margin-left: 40px;
#### }
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>

## CSS color Property

#### Example
Set the text-color for different elements:

#### body {
 #### color: red;
#### }

#### h1 {
  #### color: #00ff00;
#### }

#### p.ex {
  #### color: rgb(0,0,255);
#### }
[css](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS).
[css](https://www.w3schools.com/cssref/pr_text_color.asp).
[css](https://www.w3schools.com/css/css_howto.asp).
[Myers Web Reset Stylesheet](https://meyerweb.com/eric/tools/css/reset/).