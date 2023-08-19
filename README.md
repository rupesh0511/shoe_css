# shoe_css
hosted link-  https://rupesh0511.github.io/shoe_css/

HTML


![Screenshot 2023-08-15 195004](https://github.com/rupesh0511/shoe_css/assets/69234169/9444b437-6d0e-4b61-ba1f-ea11f05fa3e9)

1.Document Structure:

!DOCTYPE html: This declaration specifies the document type as HTML5.
html lang="en": This tag defines the root of the HTML document and specifies the language as English.

2. Document Metadata (inside the head section):

meta charset="UTF-8": This meta tag sets the character encoding of the document to UTF-8, ensuring proper character display.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: This meta tag configures the viewport settings for responsive web design.
<title>Document</title>: This tag sets the title of the web page, which is displayed in the browser's title bar or tab.
The link tag links an external stylesheet ("styles.css") for styling.

  
3.Page Content (inside the body section):

div class="container": This div tag creates the main container for the content of the web page.

div class="backcontainer": This div tag with the class "backcontainer" is an an empty container,for background styling.

div class="subcontainer": This div tag with the class "subcontainer" is used to create a sub-container within the main container.

div class="text": This div tag with the class "text" is used for containing text content.

 The h1 tag represents the main heading of the content, displaying "Shoe-1."

p class="content".../p: These p tags with the class "content" contain paragraphs of text content, which appear to be Lorem Ipsum placeholder text.

div class="image": This tag with the class "image" is used for containing an image.

The img tag displays an image. It uses the "src" attribute to specify the image file's URL and has a class "picture," which may be used for styling or scripting.


CSS


![Screenshot 2023-08-15 195015](https://github.com/rupesh0511/shoe_css/assets/69234169/c14d2b1e-6c20-4194-b1b6-3f7b91e7569f)
![Screenshot 2023-08-15 195036](https://github.com/rupesh0511/shoe_css/assets/69234169/900e3046-34e5-452a-9db7-b5bebbe9f0ad)


* selector:
  margin: 0;: This rule sets the margin for all elements to 0.
padding: 0px;: It sets the padding for all elements to 0 pixels.
box-sizing: border-box;: This rule ensures that the padding and border of elements are included in their total width and height.

.container selector:

position: relative;: This rule sets the positioning context for elements inside the container.
width: 100%;: It makes the container take up the full width of its parent element.
height: 100vh;: This sets the container's height to 100% of the viewport height.
overflow: hidden;: It hides any content that overflows the container.

.backcontainer selector:

width: 100%;: It makes this container take up the full width of its parent.
height: 100%;: Sets its height to 100% of its parent's height.
background: linear-gradient(to right, #B42C2A, #1964BE);: This creates a linear gradient background from red (#B42C2A) to blue (#1964BE).
z-index: -1;: This places the element behind other content (negative z-index).
position: absolute;: This element is positioned absolutely relative to its nearest positioned ancestor.
transform: skewY(10deg);: It skews the element by 10 degrees along the Y-axis.
