# Cascading Style Sheets

In our previous exercise, we went over and built a simple webpage on our favorite animals. Now, we're going to use CSS to style it! First we have to go over how you choose, or *select*, the different parts of your page to style.
Whenever I run into a problem with CSS, my favorite place to look for an answer is [W3Schools.com](https://www.w3schools.com/css/default.asp).

There are three ways to insert a style sheet into your HTML; external, internal, and inline. Internal CSS uses the `<style>` element tag (located in the head element) to style the page. Inline CSS uses the `@style` attribute within the HTML page itself to style it. We'll be using the external method! This means that our whole site will be styled by a separate file. The perk of using external CSS is you don't have to rewrite styles for each separate page because they are all in your CSS file itself. We then just link the CSS file to your site page by using the `<link>` element in the head element!

**One CSS to rule them all** *maniacal laughter*


## Selectors

In CSS, the way we choose between a paragraph and image is by using a selector. For elements like `<body>, <p>, & <img>` we actually just use the element tag name. There are three different selectors we can choose; element tag name, class name, and id name. We didn't go over classes and IDs in the last exercises, but they are used to differentiate between similar element tags. For example, if we have two paragraphs and you only want one to be selected, you can assign it a class.

```
    <p> Lorem ipsum...</p>
    <p class="special"> Lorem ipsum...</p>
```

Now, in your css, you say you only wnat the paragraph with class="special" have a purple backgrund!

 * The class selector in CSS is a period (.).
 * The ID selector in CSS is a pound sign (#).

We can go over selectors more when we start using them more in our pages.

## Properties
In CSS there are many different properties to use for your pages!
Some common ones are:

 * **background-color** -- this changes the background clor for that element
 * **color** -- this changes the text color for that element
 * **font-size** -- this changes the text size for that element
 * **border** -- this puts a border around that element

Each of these properties has a list of acceptable values that can be used for it. For example, any property that affects color can only predefined color names, or RGB, HEX, HSL, RGBA, HSLA values. For my pages, I usually use HEX values because I like the [color picker on W3Schools](https://www.w3schools.com/colors/colors_picker.asp?color=80ced6)

### Animal Page
Now, let's style our animal page.

Here is the code from our HTML page that I wrote.

```
<!DOCTYPE html>
    <head>
        <title>Cats</title>
    </head>
    <body>
        <h1>My Thoughts On Cats!</h1>
        <p>I love cats! They are my favorite animal. Their little toe beans and the way they purr are just the cutest. My first cat was named Ariel because I loved the 'Little Mermaid' when I was growing up. Now, I have Fuzz, who I call Rex sometimes, and Ziggy, who's named after David Bowie's stage ego Ziggy Stardust. They're my little monsters. I am also against declawing.</p>
        <img src="cat.jpg">
    </body>
```

First let's go in and style our `<body>`
```
body{
    background-color: mediumSeaGreen;
    color: white;
    font-size: 18px;
}
```
This declaration made my background color for the site a light green with white, 18 pixel text.

Next, the `<h1>`
```
h1{
    background-color: LightGray;
    color: MediumSeaGreen;
}
```
With heading elements, you do not want to resize the font-size because it is based off the size of the body element text.


