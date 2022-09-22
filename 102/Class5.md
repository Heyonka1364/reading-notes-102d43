# CSS

## What is CSS

CSS is a language used to style websites in HTML. You can style this in different ways but to most reccomeneded way is to use an *external style*. This dedicates a file to code in CSS. The extension must be ".css".

The other style is call interal CSS. This is a way to code CSS throughout a HTML file. But with that being said things can get very confusing this way.

Lastly, Inline CSS also can be coded in the HTML file but all of the code you do in CSS is on  one line. This is also confusing because if you have fifty lines of code you can get lost on what code does what.

## CSS Color

 In CSS every color has a number. And CSS has various method for protary that color. There many way to code color in CSS listed below:

- body {color: hashtag92a8d1}(easier)
  The code after the hashtag is called a Hex Code

- body {color: rgb round bracket 201, 76, 76 close bracket;}

- body {color: rgba round bracket 201, 76, 76,  0.6 close bracket;}

- body {color: hsl round bracket 89, 43%, 51% close bracket;}

- body {color: hsla round bracket 89, 43%, 51%,  0.6 close bracket;}

## Basic sytax rules

- CSS will change things according to which part of HTML. Along with the areas for the webpage when you `right click` on the webpage and hit `inspect`. So if you wanted to change the body or any other part, you would type something similar to the examples below.

`body {
    text-align: center;
   background-color: rgba(184, 76, 0, 72) ;
}
`

`header {
    border: 20px solid #BEC1C2;
}`

- Every line except  brackets that look like this ,`{}`, must end with a semicolon `;`.

- If you would like to target a specific section you have to type class = a variable in HTML. For example

`<section class="mid-section">
    what ever is in the section
    </section>`

This variable can be used for more than one section. Then in CSS type:

`.mid-section img {
    color: rgba(185, 245, 250, 98);
    border: 10px solid #FF9142;
}`

For targeting one section name the variable something different and replace the period with a hashtag. You would also have make a different variable each section you would like to target. For example:

`#other-mid-section img {
    color: rgba(195, 200, 300, 50);
    border: 10px solid #FF9142;
}`

`#other-mid-section-2 img {
    color: rgba(195, 200, 300, 50);
    border: 10px solid #FF9142;
}`

[Back to home page](../reading-notes-102d43/README.md)