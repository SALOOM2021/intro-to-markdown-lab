# How to write an HTML Boilerplate
![HTML logo](https://i.imgur.com/mAzIORO.png)

**Boilerplate code** or just **boilerplate** are sections of code that are repeated in multiple places with little to no variation.

A **boilerplate in HTML is** a template you will add at the start of your project. You should add this boilerplate to all of your HTML pages.

## Basic Structure of an HTML Boilerplate

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="your-css-file-name.css"> <!-- Link to CSS -->
  <script defer src="your-javascript-file-name.js"></script> <!-- Link to JavaScript -->
  <title>Your Page Title</title>
</head>
<body>

  <!-- Main Content -->

</body>
</html>
```

## Breakdown of the Boilerplate
1. **Documnet Declaration** : This line is a declaration represents the document type, and helps browsers to display web pages correctly.

```html
<!DOCTYPE html>
```
2. **File Language**: On the second line , it shows that the language of the web page will be in *English*

```html
<html lang="en">
    <!-- head and body elements-->
</html>
```
> >  **NOTE**: To define the language of a webpage, we invoke the first 2 letters, and in some cases 3 but no more

3. **Head Element** : This element is a container for metadata (data about data) and is placed between the `<html>` tag and the `<body>` tag.
HTML metadata is data about the HTML document. Metadata is not displayed.The head element typically define the document title `<title>`, character set`<meta charset>`, styles`<style>`, scripts `<script>`, and other meta information.

```html
<head>
    <!-- meta data-->
</head>
```
4. **Charset Attribute** :The *charset* attribute specifies the character encoding for the HTML document.The HTML5 specification encourages web developers to use the UTF-8 character set, which covers almost all of the characters and symbols in the world!

```html
 <meta charset="UTF-8">
```
5. **Viewport**: The viewport is the user's visible area of a web page.The viewport varies with the device, and will be smaller on a mobile phone than on a computer screen.
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
````
6. **Title** : title element shows the name of your page, but does not display it on the screen.

``` html 
 <title>Your Page Title</title>
```

![Amazon Web Titile](https://i.imgur.com/WfuOnpb.png)

7. **Body Element** :The `<body>` element defines the document's body.
It has a start tag `<body>` and an end tag `</body>`.

```html
<body>
    <!--Content-->
</body>
```

## Need To Know
- You may notice that some HTML elements does't not have closing tag which called **self-closing elements**, or **void elements**,because they represent a single entity or perform a specific action that doesn't need additional content inside them.

***Example :***
```html
<meta charset= "UTF-8" /> <!-- Self Closing tag /> -->
<title>...</title> <!-- has a closing tage </> -->
```
- Anything inside the `<head>` element will not be displayed on the screen, the head element deal with the **computer not the user.**

## Tips

- No need to memorize all of these lines, **insted** when creating the new HTML file just write *!* and press `Enter` and the compailer will automatically create the bolierplate for you

- For more information about HTML Boilerplate, you can visit [FreeCodeCamp HTML Boilerplate](https://www.freecodecamp.org/news/basic-html5-template-boilerplate-code-example/)