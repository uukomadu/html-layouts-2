<!-- <img src="https://devmounta.in/img/logowhiteblue.png" width="250" align="right">

html-layouts-2
==============

##Objectives
Understand HTML and its uses in layout by completing a series of tasks

##Directions
Just like html-layout the original, each folder contains an image you need to recreate using HTML and CSS -->

# Project Summary

In this project, you will be cloning/re-creating three different html-layouts from scratch. This will help you get used to creating html documents and linking css pages. This project will also help you practice the ability to create layouts using html and css.

## Setup

* Fork and clone this repo.
* `cd` into the directory.

## Directions

Inside each of the three folders you will find an image. That image is a representation of the layout you need to create using HTML and CSS. The 'first' folder contains an index.html and a style.css file. In the other folders, you'll need to add them yourself.

## First

### Directions

Below are the very broad directions to finishing the clone of the image in the 'first' folder. We encourage you to try to finish this project with as little help as possible. But if you need more guidance there is a 'Follow Along' section right below these directions that will be a little more in dept. Have Fun!

* Open 'first' folder.
* Create an index.html file in the 'first' folder.
* Create a style.css file in the 'first' folder.
* Create a reset.css file in the 'first' folder.
* Add reset css styles inside reset.css.
* Create your index.html boiler plate.
* Link your style.css in your index.html file.
* Create a HTML structure using semantic elements.
* Add CSS to give each element a height, width, position, etc. to make your webpage look as close as you can to the image provided.

### Follow Along

* Open 'first' folder.
* Create an index.html file in the 'first' folder.
* Create a style.css file in the 'first' folder.
* Create a reset.css file in the 'first' folder.
* Add reset css styles inside reset.css.
  * <details>

    <summary> <code> reset.css </code> </summary>

    ```css
    html, body, div, span, applet, object, iframe,
    h1, h2, h3, h4, h5, h6, p, blockquote, pre,
    a, abbr, acronym, address, big, cite, code,
    del, dfn, em, img, ins, kbd, q, s, samp,
    small, strike, strong, sub, sup, tt, var,
    b, u, i, center,
    dl, dt, dd, ol, ul, li,
    fieldset, form, label, legend,
    table, caption, tbody, tfoot, thead, tr, th, td,
    article, aside, canvas, details, embed,
    figure, figcaption, footer, header, hgroup,
    menu, nav, output, ruby, section, summary,
    time, mark, audio, video {
    	margin: 0;
    	padding: 0;
    	border: 0;
    	font-size: 100%;
    	font: inherit;
    	vertical-align: baseline;
    }

    html {
      box-sizing: border-box;
    }
    *, *:before, *:after {
      box-sizing: inherit;
    }
    /* HTML5 display-role reset for older browsers */
    article, aside, details, figcaption, figure,
    footer, header, hgroup, menu, nav, section {
    	display: block;
    }
    body {
    	line-height: 1;
    }
    ol, ul {
    	list-style: none;
    }
    blockquote, q {
    	quotes: none;
    }
    blockquote:before, blockquote:after,
    q:before, q:after {
    	content: '';
    	content: none;
    }
    table {
    	border-collapse: collapse;
    	border-spacing: 0;
    }

    ```

    </details>
* Open `index.html`.
* Inside index.html, create your index.html boiler plate.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
      </head>
      <body>
      </body>
    </html>
    ```

    </details>
* Inside index.html, link the index.html file to the style.css file.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
      </body>
    </html>
    ```

    </details>
* Inside index.html, link the index.html file to the reset.css file.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
      </body>
    </html>
    ```

    </details>
* Inside index.html, create a div that will act as the wrapper for all the content on the page. Give this element a class name and close the element. The rest of the elements will be put inside this div.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">

        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, create a section and don't forget to close the section. Give the section element a class name to be able to style it later.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">

          </section>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the section you created in the previous step, create three div elements and give each one the same class name. Next give each of the divs another unique class to differentiate each by their background color. You can give a element more that one class by separating them by a space like this `class="firstClass secondClass"`.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, below the section you created, create a paragraph. Give it a class name and close the paragraph.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, create another paragraph tag and give it the same class name as the previous paragraph. Close the paragraph.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, below the two paragraphs create a section. Give this section a class name and don't forget to close the section.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <section class="middle-boxes">

          </section>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the section you created in the previous step create two divs and give each a unique class name. Now reuse the class you used to differentiate the previous section's divs by background color to their corresponding div.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <section class="middle-boxes">
            <div class="middle-red-box red"></div>
            <div class="middle-blue-box blue"></div>
          </section>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, create another section. Give this section a class name and close the section.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <section class="middle-boxes">
            <div class="middle-red-box red"></div>
            <div class="middle-blue-box blue"></div>
          </section>
          <section class="bottom-boxes">

          </section>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the section you created in the previous step create two child divs and give each a different class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <section class="middle-boxes">
            <div class="middle-red-box red"></div>
            <div class="middle-blue-box blue"></div>
          </section>
          <section class="bottom-boxes">
            <div class="bottom-blue-box"></div>
            <div class="bottom-red-box">

            </div>
          </section>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, reuse the class names you are using to differentiate divs by background color and give these two divs their corresponding class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <section class="middle-boxes">
            <div class="middle-red-box red"></div>
            <div class="middle-blue-box blue"></div>
          </section>
          <section class="bottom-boxes">
            <div class="bottom-blue-box blue"></div>
            <div class="bottom-red-box red">

            </div>
          </section>
        </div>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the second div you created inside the section, create another div and give it a class name, also give it a second class name that will differentiate it by background color.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>first Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <div class="wrapper">
          <section class="top-boxes">
            <div class="top-box red"></div>
            <div class="top-box blue"></div>
            <div class="top-box black"></div>
          </section>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <section class="middle-boxes">
            <div class="middle-red-box red"></div>
            <div class="middle-blue-box blue"></div>
          </section>
          <section class="bottom-boxes">
            <div class="bottom-blue-box blue"></div>
            <div class="bottom-red-box red">
              <div class="bottom-black-box black"></div>
            </div>
          </section>
        </div>
      </body>
    </html>
    ```

    </details>
* Open style.css
* Inside style.css, select the div that is acting as the wrapper by class and give it some padding.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .wrapper{
      padding: 50px 30px;
    }
    ```

    </details>
* Inside style.css, select the first section by class and give it css properties that will make the child elements display side-by-side and evenly spread the children by the space between them. Hint: flex.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .top-boxes{
      display: flex;
      justify-content: space-between;
    }
    ```

    </details>
* Inside style.css, in the same css block you used in the previous step add another css property that will keep space between the section and the elements below it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .top-boxes{
      display: flex;
      justify-content: space-between;
      margin-bottom: 50px;
    }
    ```

    </details>
* Inside style.css, select the three boxes at the top of the page by the class that is similar on all three and give them a height and a width.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .top-box{
      width: 31%;
      height: 200px;
    }
    ```

    </details>
* Inside style.css, select the three elements separately by their unique class and give each block a css property that will change the background color.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .red{
      background: #D0021B;
    }

    .blue{
      background: #4A90E2;
    }

    .black{
      background: #4A4A4A;
    }
    ```

    </details>
* Inside style.css, select the text on the page by class and assign it properties that will make it look as close as you can to the image. For example size, font, line height, margin.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .text{
      font-family: sans-serif;
      font-size: 30px;
      line-height: 40px;
      margin-bottom: 50px;
    }
    ```

    </details>
* Inside style.css, select the section(directly after the text) by class and give it a display property that will make its children elements display side-by-side. Next give it a margin to keep some space between it and the elements below it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .middle-boxes{
      display: flex;
      margin-bottom: 50px;
    }
    ```

    </details>
* Inside style.css, select the div on the left side of the section we worked on in the previous step. Give it a height and a width.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .middle-red-box{
      height: 500px;
      width: 33%;
    }
    ```

    </details>
* Inside style.css, select the div on the right side of the same section we worked on in the previous step. Give it a height and a width.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .middle-blue-box{
      height: 500px;
      width: 77%;
    }
    ```

    </details>
* Inside style.css, select the section at the bottom of the page. Give it a style that will make its children elements display side-by-side.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .bottom-boxes{
      display: flex;
    }
    ```

    </details>
* Inside style.css, select the blue box in the section from the previous step and give it a with and height.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .bottom-blue-box{
      width: 70%;
      height: 200px;
    }
    ```

    </details>
* Inside style.css, select the red box in the same section from the previous step and give it a height and width.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .bottom-red-box{
      width: 30%;
      height: 200px;
    }
    ```

    </details>
* Inside style.css, select the black box in the same section from the previous step and give it a height, width and margin that will center it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .bottom-black-box{
      width: 70%;
      height: 100%;
      margin: auto;
    }
    ```

    </details>
* Great job! That looks really close the the original image. Let's keep going!

### Solution

<details>

<summary> <code> index.html </code> </summary>

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>first Solution</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="wrapper">
      <section class="top-boxes">
        <div class="top-box red"></div>
        <div class="top-box blue"></div>
        <div class="top-box black"></div>
      </section>
      <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      <section class="middle-boxes">
        <div class="middle-red-box red"></div>
        <div class="middle-blue-box blue"></div>
      </section>
      <section class="bottom-boxes">
        <div class="bottom-blue-box blue"></div>
        <div class="bottom-red-box red">
          <div class="bottom-black-box black"></div>
        </div>
      </section>
    </div>
  </body>
</html>
```

</details>

<details>

<summary> <code> style.css </code> </summary>

```css
.wrapper{
  padding: 50px 30px;
}

.top-boxes{
  display: flex;
  justify-content: space-between;
  margin-bottom: 50px;
}

.top-box{
  width: 31%;
  height: 200px;
}

.red{
  background: #D0021B;
}

.blue{
  background: #4A90E2;
}

.black{
  background: #4A4A4A;
}

.text{
  font-family: sans-serif;
  font-size: 30px;
  line-height: 40px;
  margin-bottom: 50px;
}

.middle-boxes{
  display: flex;
  margin-bottom: 50px;
}

.middle-red-box{
  height: 500px;
  width: 33%;
}

.middle-blue-box{
  height: 500px;
  width: 77%;
}

.bottom-boxes{
  display: flex;
}

.bottom-blue-box{
  width: 70%;
  height: 200px;
}

.bottom-red-box{
  width: 30%;
  height: 200px;
}

.bottom-black-box{
  width: 70%;
  height: 100%;
  margin: auto;
}
```

</details>

## Second

### Directions

Below are the very broad directions to finishing the clone of the image in the 'second' folder. We encourage you to try to finish this project with as little help as possible. But if you need more guidance there is a 'Follow Along' section right below these directions that will be a little more in dept. Have Fun!

* Open 'second' folder.
* Create an index.html file in the 'second' folder.
* Create a style.css file in the 'second' folder.
* Create a reset.css file in the 'second' folder.
* Add reset css styles inside reset.css.
* Create your index.html boiler plate.
* Link your style.css in your index.html file.
* Create a HTML structure using semantic elements.
* Add CSS to give each element a height, width, position, etc. to make your webpage look as close as you can to the image provided.

### Follow Along

* Open 'second' folder.
* Create an index.html file in the 'second' folder.
* Create a style.css file in the 'second' folder.
* Create a reset.css file in the 'second' folder.
* Add reset css styles inside reset.css.
  * <details>

    <summary> <code> reset.css </code> </summary>

    ```css
    html, body, div, span, applet, object, iframe,
    h1, h2, h3, h4, h5, h6, p, blockquote, pre,
    a, abbr, acronym, address, big, cite, code,
    del, dfn, em, img, ins, kbd, q, s, samp,
    small, strike, strong, sub, sup, tt, var,
    b, u, i, center,
    dl, dt, dd, ol, ul, li,
    fieldset, form, label, legend,
    table, caption, tbody, tfoot, thead, tr, th, td,
    article, aside, canvas, details, embed,
    figure, figcaption, footer, header, hgroup,
    menu, nav, output, ruby, section, summary,
    time, mark, audio, video {
    	margin: 0;
    	padding: 0;
    	border: 0;
    	font-size: 100%;
    	font: inherit;
    	vertical-align: baseline;
    }

    html {
      box-sizing: border-box;
    }
    *, *:before, *:after {
      box-sizing: inherit;
    }
    /* HTML5 display-role reset for older browsers */
    article, aside, details, figcaption, figure,
    footer, header, hgroup, menu, nav, section {
    	display: block;
    }
    body {
    	line-height: 1;
    }
    ol, ul {
    	list-style: none;
    }
    blockquote, q {
    	quotes: none;
    }
    blockquote:before, blockquote:after,
    q:before, q:after {
    	content: '';
    	content: none;
    }
    table {
    	border-collapse: collapse;
    	border-spacing: 0;
    }

    ```

    </details>
* Open `index.html`.
* Inside index.html, create your index.html boiler plate.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
      </head>
      <body>
      </body>
    </html>
    ```

    </details>
* Inside index.html, link the index.html file to the style.css file.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
      </body>
    </html>
    ```

    </details>
* Inside index.html, link the index.html file to the reset.css file. Make sure it comes before your style.css file.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
      </body>
    </html>
    ```

    </details>
* Inside index.html, create a main section. Don't forget the closing tag.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">

        </main>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the main section create two sections and give both a different class name so that we can differentiate them.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">
          <section class="top">

          </section>
          <section class="middle">

          </section>
        </main>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the first section you created in the previous step create a paragraph. Give it a class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">
          <section class="top">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
          <section class="middle">

          </section>
        </main>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the same section you used in the previous step create a div that will house the two button. Give it a class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">
          <section class="top">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <div class="button-wrapper">

            </div>
          </section>
          <section class="middle">

          </section>
        </main>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the div that will house your buttons, create two button elements and give them one similar class name and another unique class name to differentiate them by class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">
          <section class="top">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <div class="button-wrapper">
              <button class="button red" type="button" name="button">Click</button>
              <button class="button blue" type="button" name="button">Click</button>
            </div>
          </section>
          <section class="middle">

        </main>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the second section in the main create an image and give it class and src to a image of your choice. Don't forget to always give an image a alt value.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">
          <section class="top">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <div class="button-wrapper">
              <button class="button red" type="button" name="button">Click</button>
              <button class="button blue" type="button" name="button">Click</button>
            </div>
          </section>
          <section class="middle">
            <img class="image" src="https://c1.staticflickr.com/1/774/20013034233_19f520eefb_b.jpg" alt="coding">
          </section>
        </main>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the same section worked on in the previous step create a paragraph and give the same class name as the previous paragraph you created.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">
          <section class="top">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <div class="button-wrapper">
              <button class="button red" type="button" name="button">Click</button>
              <button class="button blue" type="button" name="button">Click</button>
            </div>
          </section>
          <section class="middle">
            <img class="image" src="https://c1.staticflickr.com/1/774/20013034233_19f520eefb_b.jpg" alt="coding">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
        </main>
      </body>
    </html>
    ```

    </details>
* Inside index.html, outside the main section create a footer and give it a class name to be able to style it later.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">
          <section class="top">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <div class="button-wrapper">
              <button class="button red" type="button" name="button">Click</button>
              <button class="button blue" type="button" name="button">Click</button>
            </div>
          </section>
          <section class="middle">
            <img class="image" src="https://c1.staticflickr.com/1/774/20013034233_19f520eefb_b.jpg" alt="coding">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
        </main>
        <footer class="footer">

        </footer>
      </body>
    </html>
    ```

    </details>
* Inside index.html, inside the footer create two anchor tags. The first anchor tag should display the text "Google" and have a href pointing to the Google homepage. The second should display the text "Apple" and have a href pointing to the Apple homepage. Give them both the same class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>second Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <main class="main">
          <section class="top">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <div class="button-wrapper">
              <button class="button red" type="button" name="button">Click</button>
              <button class="button blue" type="button" name="button">Click</button>
            </div>
          </section>
          <section class="middle">
            <img class="image" src="https://c1.staticflickr.com/1/774/20013034233_19f520eefb_b.jpg" alt="coding">
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
        </main>
        <footer class="footer">
          <a class="footer-link" href="http://google.com">Google</a>
          <a class="footer-link" href="http://apple.com">Apple</a>
        </footer>
      </body>
    </html>
    ```

    </details>
* Open style.css
* Inside style.css, select the main section by class and give it a background color, padding, and font family.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .main{
      background: lightGrey;
      padding: 60px 100px;
      font-family: sans-serif;
    }
    ```

    </details>
* Inside style.css, select the first section by class and give it a background color, padding, and a margin to keep space between it and the elements below it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .top{
      padding: 60px;
      background: white;
      margin-bottom: 60px;
    }
    ```

    </details>
* Inside style.css, select the text by class and give it a font-size, line-height, and a margin to keep space between it and the elements below it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .text{
      font-size: 26px;
      line-height: 35px;
      margin-bottom: 60px;
    }
    ```

    </details>
* Inside style.css, select the buttons by their similar class and give them a height, width, font color, font size, and a margin to keep some space between them. Optional: give it a border of none to erase the default border.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .button{
      height: 90px;
      width: 225px;
      color: white;
      font-size: 40px;
      margin-right: 20px;
      border: none;
    }
    ```

    </details>
* Inside style.css, select each of the buttons separately by the class name that specifies their background color and assign it a property that will change the button's background color.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .red{
      background: #D0021B;
    }

    .blue{
      background: #4A90E2;
    }
    ```

    </details>
* Inside style.css, select the second section by class and give it a background color, padding, and a margin to keep space between it and the elements below it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .middle{
      padding: 60px;
      background: white;
      margin-bottom: 60px;
    }
    ```

    </details>
* Inside style.css, select the image by class and give it a width and margin to keep space between it and the elements below it. NOTE: We do not have to assign the image a height because the default value of height is `auto`. This will make the image stay proportional.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .image{
      width: 100%;
      margin-bottom: 60px;
    }
    ```

    </details>
* Inside style.css, select the footer by class and give it a height, width, background color, and padding.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .footer{
      width: 100%;
      height: 125px;
      background: #333333;
      padding: 0 100px;
    }
    ```

    </details>
* Inside style.css, select the anchors in the footer by class and give them a font color, font size, font-family, line height, and margin. Take of the default text decoration on the links and give them a property to make them move to the right side of the page.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .footer-link{
      color: white;
      font-size: 30px;
      font-family: sans-serif;
      line-height: 125px;
      margin-left: 75px;
      float: right;
      text-decoration: none;
    }
    ```

    </details>

### Solution

<details>

<summary> <code> index.html </code> </summary>

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>second Solution</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <main class="main">
      <section class="top">
        <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <div class="button-wrapper">
          <button class="button red" type="button" name="button">Click</button>
          <button class="button blue" type="button" name="button">Click</button>
        </div>
      </section>
      <section class="middle">
        <img class="image" src="https://c1.staticflickr.com/1/774/20013034233_19f520eefb_b.jpg" alt="coding">
        <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </section>
    </main>
    <footer class="footer">
      <a class="footer-link" href="http://google.com">Google</a>
      <a class="footer-link" href="http://apple.com">Apple</a>
    </footer>
  </body>
</html>
```

</details>

<details>

<summary> <code> style.css </code> </summary>

```css
.main{
  background: lightGrey;
  padding: 60px 100px;
  font-family: sans-serif;
}

.top{
  padding: 60px;
  background: white;
  margin-bottom: 60px;
}

.text{
  font-size: 26px;
  line-height: 35px;
  margin-bottom: 60px;
}

.button{
  height: 90px;
  width: 225px;
  color: white;
  font-size: 40px;
  margin-right: 20px;
  border: none;
}

.red{
  background: #D0021B;
}

.blue{
  background: #4A90E2;
}

.middle{
  padding: 60px;
  background: white;
  margin-bottom: 60px;
}

.image{
  width: 100%;
  margin-bottom: 60px;
}

.footer{
  width: 100%;
  height: 125px;
  background: #333333;
  padding: 0 100px;
}

.footer-link{
  color: white;
  font-size: 30px;
  font-family: sans-serif;
  line-height: 125px;
  margin-left: 75px;
  float: right;
  text-decoration: none;
}

```

</details>


## Third

### Directions

Below are the very broad directions to finishing the clone of the image in the 'third' folder. We encourage you to try to finish this project with as little help as possible. But if you need more guidance there is a 'Follow Along' section right below these directions that will be a little more in dept. Have Fun!

* Open 'third' folder.
* Create an index.html file in the 'third' folder.
* Create a style.css file in the 'third' folder.
* Create a reset.css file in the 'third' folder.
* Add reset css styles inside reset.css.
* Create your index.html boiler plate.
* Link your style.css in your index.html file.
* Create a HTML structure using semantic elements.
* Add CSS to give each element a height, width, position, etc. to make your webpage look as close as you can to the image provided.

### Follow Along

* Open 'third' folder.
* Create an index.html file in the 'third' folder.
* Create a style.css file in the 'third' folder.
* Create a reset.css file in the 'third' folder.
* Add reset css styles inside reset.css.
  * <details>

    <summary> <code> reset.css </code> </summary>

    ```css
    html, body, div, span, applet, object, iframe,
    h1, h2, h3, h4, h5, h6, p, blockquote, pre,
    a, abbr, acronym, address, big, cite, code,
    del, dfn, em, img, ins, kbd, q, s, samp,
    small, strike, strong, sub, sup, tt, var,
    b, u, i, center,
    dl, dt, dd, ol, ul, li,
    fieldset, form, label, legend,
    table, caption, tbody, tfoot, thead, tr, th, td,
    article, aside, canvas, details, embed,
    figure, figcaption, footer, header, hgroup,
    menu, nav, output, ruby, section, summary,
    time, mark, audio, video {
    	margin: 0;
    	padding: 0;
    	border: 0;
    	font-size: 100%;
    	font: inherit;
    	vertical-align: baseline;
    }

    html {
      box-sizing: border-box;
    }
    *, *:before, *:after {
      box-sizing: inherit;
    }
    /* HTML5 display-role reset for older browsers */
    article, aside, details, figcaption, figure,
    footer, header, hgroup, menu, nav, section {
    	display: block;
    }
    body {
    	line-height: 1;
    }
    ol, ul {
    	list-style: none;
    }
    blockquote, q {
    	quotes: none;
    }
    blockquote:before, blockquote:after,
    q:before, q:after {
    	content: '';
    	content: none;
    }
    table {
    	border-collapse: collapse;
    	border-spacing: 0;
    }

    ```

    </details>
* Open `index.html`.
* Inside index.html, create your index.html boiler plate.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
      </head>
      <body>
      </body>
    </html>
    ```

    </details>
* Inside index.html, link the index.html file to the style.css file.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
      </body>
    </html>

    ```

    </details>
* Inside index.html, link the index.html file to the reset.css file. Make sure it comes before your style.css file.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
      </body>
    </html>

    ```

    </details>
* Inside index.html, create a header and give it a class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">

        </header>
      </body>
    </html>

    ```

    </details>
* Inside index.html, inside the header create two anchor tags the first should be a link to the Google home page. The second should be a link to the Apple homepage. Give both anchor tags the same class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">
          <a class="header-link" href="http://google.com">Google</a>
          <a class="header-link" href="http://apple.com">Apple</a>
        </header>
      </body>
    </html>

    ```

    </details>
* Inside index.html, below the header create a main section and give it a class name so we can style it later.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">
          <a class="header-link" href="http://google.com">Google</a>
          <a class="header-link" href="http://apple.com">Apple</a>
        </header>
        <main class="main">

        </main>
      </body>
    </html>

    ```

    </details>
* Inside index.html, inside the main section create two sections one for the left side of the main section and the other for the right side of the main section. Make sure the left section comes before the right section in the html. Give them each a different class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">
          <a class="header-link" href="http://google.com">Google</a>
          <a class="header-link" href="http://apple.com">Apple</a>
        </header>
        <main class="main">
          <section class="left">

          </section>
          <section class="right">

          </section>
        </main>
      </body>
    </html>

    ```

    </details>
* Inside index.html, inside the left section create a header and insert the correct text. Give it a class name to style it later.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">
          <a class="header-link" href="http://google.com">Google</a>
          <a class="header-link" href="http://apple.com">Apple</a>
        </header>
        <main class="main">
          <section class="left">
            <h1 class="title">Type Something</h1>
          </section>
          <section class="right">

          </section>
        </main>
      </body>
    </html>

    ```

    </details>
* Inside index.html, inside the left section create five paragraphs and give them all the same class name.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">
          <a class="header-link" href="http://google.com">Google</a>
          <a class="header-link" href="http://apple.com">Apple</a>
        </header>
        <main class="main">
          <section class="left">
            <h1 class="title">Type Something</h1>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
          <section class="right">

          </section>
        </main>
      </body>
    </html>

    ```

    </details>
* Inside index.html, inside the right section create a div and give it a class name so we can style it later.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">
          <a class="header-link" href="http://google.com">Google</a>
          <a class="header-link" href="http://apple.com">Apple</a>
        </header>
        <main class="main">
          <section class="left">
            <h1 class="title">Type Something</h1>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
          <section class="right">
            <div class="gray-box"></div>
          </section>
        </main>
      </body>
    </html>

    ```

    </details>
* Inside index.html, inside the right section create two paragraphs and give them the same class name as the previous paragraphs.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">
          <a class="header-link" href="http://google.com">Google</a>
          <a class="header-link" href="http://apple.com">Apple</a>
        </header>
        <main class="main">
          <section class="left">
            <h1 class="title">Type Something</h1>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
          <section class="right">
            <div class="gray-box"></div>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
        </main>
      </body>
    </html>

    ```

    </details>
* Inside index.html, below the main section create a footer and give it a class name to style it later.
  * <details>

    <summary> <code> index.html </code> </summary>

    ```html
    <!DOCTYPE html>
    <html>
      <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>third Solution</title>
        <link rel="stylesheet" href="reset.css">
        <link rel="stylesheet" href="style.css">
      </head>
      <body>
        <header class="header">
          <a class="header-link" href="http://google.com">Google</a>
          <a class="header-link" href="http://apple.com">Apple</a>
        </header>
        <main class="main">
          <section class="left">
            <h1 class="title">Type Something</h1>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
          <section class="right">
            <div class="gray-box"></div>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </section>
        </main>
        <footer class="footer"></footer>
      </body>
    </html>

    ```

    </details>
* Open style.css
* Inside style.css, select the header by class and give it a height, background color, padding, and font family.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .header{
      height: 125px;
      background: #333333;
      padding: 0 60px;
      font-family: sans-serif;
    }
    ```

    </details>
* Inside style.css, select the links in the header by class and give them a font color, font size, line-height, and margin. Also make the elements float to the left side of the page. Lastly remove the default text-decoration.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .header-link{
      color: white;
      font-size: 30px;
      line-height: 125px;
      margin-right: 60px;
      float: left;
      text-decoration: none;
    }
    ```

    </details>
* Inside style.css, select the main section and give it a padding, font family, a display that will let you manipulate the child elements, and a css property to space the children evenly by the space between them. HINT: We'll be using flex-box in this step.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .main{
      padding: 120px 60px;
      font-family: sans-serif;
      display: flex;
      justify-content: space-between;
    }
    ```

    </details>
* Inside style.css, select the left section of the main and give it a width.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .left{
      width: 48%;
    }
    ```

    </details>
* Inside style.css, select the right section of the main and give it a width.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .right{
      width: 48%;
    }
    ```

    </details>
* Inside style.css, select the title in the left section and give it a font size, and a margin to keep space between it and the elements below it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .title{
      font-size: 75px;
      margin-bottom: 30px;
    }
    ```

    </details>
* Inside style.css, select the paragraph in the left section and give it a font size, and a margin to keep space between it and the elements below it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .paragraph{
      font-size: 24px;
      margin-bottom: 30px;
    }
    ```

    </details>
* Inside style.css, select the div in the right section and give it a width, height, background color, and a margin to keep space between it an the elements below it.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .gray-box{
      width: 100%;
      height: 450px;
      background: #D8D8D8;
      margin-bottom: 30px;
    }
    ```

    </details>
* Inside style.css, select the footer by class and give it a height and a background color.
  * <details>

    <summary> <code> style.css </code> </summary>

    ```css
    .footer{
      height: 125px;
      background: #333333;
    }
    ```

    </details>

### Solution

<details>

<summary> <code> index.html </code> </summary>

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>third Solution</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header class="header">
      <a class="header-link" href="http://google.com">Google</a>
      <a class="header-link" href="http://apple.com">Apple</a>
    </header>
    <main class="main">
      <section class="left">
        <h1 class="title">Type Something</h1>
        <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </section>
      <section class="right">
        <div class="gray-box"></div>
        <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p class="paragraph">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </section>
    </main>
    <footer class="footer"></footer>
  </body>
</html>

```

</details>

<details>

  <summary> <code> style.css </code> </summary>

  ```css
  .header{
    height: 125px;
    background: #333333;
    padding: 0 60px;
    font-family: sans-serif;
  }

  .header-link{
    color: white;
    font-size: 30px;
    line-height: 125px;
    margin-right: 60px;
    float: left;
    text-decoration: none;
  }

  .main{
    padding: 120px 60px;
    font-family: sans-serif;
    display: flex;
    justify-content: space-between;
  }

  .left{
    width: 48%;
  }

  .right{
    width: 48%;
  }

  .title{
    font-size: 75px;
    margin-bottom: 30px;
  }

  .paragraph{
    font-size: 24px;
    margin-bottom: 30px;
  }

  .gray-box{
    width: 100%;
    height: 450px;
    background: #D8D8D8;
    margin-bottom: 30px;
  }

  .footer{
    height: 125px;
    background: #333333;
  }

  ```

  </details>

# End of project

Congratulations you have finish this project.


## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2015. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<img src="https://devmounta.in/img/logowhiteblue.png" width="250">
