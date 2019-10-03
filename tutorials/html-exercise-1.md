# HTML

HTML is short for hyper text markup language and it makes up what will appear on your web page!
Every website starts out the same:

```
<!DOCTYPE html>
    <head>
        <title></title>
    </head>
    <body>
    </body>
</html>
```

What you see in the angle brackets are called **elements** and they help tell the browser how to display its content.

## Jumping On In To Code

Everything that appears on your site goes in the `<body>` element

Let's make our own site about your favorite animal! I *love* **cats**!

First, let's decide on a heading for our page.

 * My Thoughts On Cats!

In HTML, headings are put in `<h>` tags. To differentiate between headings, they start at `<h1>`, being the biggest, and decrease in size by increasing in number.

  `<h1><h2><h3><h4><h5><h6>`

To put our heading on our page, we'll go in the `<body>` element and place our heading text in an `h1` tag.

```
<!DOCTYPE html>
    <head>
        <title>Cats</title>
    </head>
    <body>
        <h1>My Thoughts On Cats!</h1>
    </body>
```

Next, let's write an introductory paragraph about our animals.

'I love cats! They are my favorite animal. Their little toe beans and the way they purr are just the cutest. My first cat was named Ariel because I loved the 'Little Mermaid' when I was growing up. Now, I have Fuzz, who I call Rex sometimes, and Ziggy, who's named after David Bowie's stage ego Ziggy Stardust. They're my little monsters. I am also against declawing.'

Although a heading is text, not all of your text should be in a heading element tag. Instead, we use `<p>` tags! `<p>` is short for paragraph. To put our paragraph on our page, we'll put the text in `<p>` tags in the `<body>` underneath our `<h1>`.

```
<!DOCTYPE html>
    <head>
        <title>Cats</title>
    </head>
    <body>
        <h1>My Thoughts On Cats!</h1>
        <p>I love cats! They are my favorite animal. Their little toe beans and the way they purr are just the cutest. My first cat was named Ariel because I loved the 'Little Mermaid' when I was growing up. Now, I have Fuzz, who I call Rex sometimes, and Ziggy, who's named after David Bowie's stage ego Ziggy Stardust. They're my little monsters. I am also against declawing.</p>
    </body>
```

And finally, let's add some pictures!

In HTML, there is a special tag for images, `<img>`.
What's different about this tag is that instead of wrapping our image in the tag, it instead goes inside the tag as an **attribute value**. The attribute that goes in the image tag is `@src`, which stands for source.

An example of what the complete tag looks like
```
<img src="image goes here">
```

Let's add our image to tour page in `<body>` and underneath our `<p>`

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

### What's next?

You'll see that everything we put on our site is there, but it's not styled. This is because the styling of a webpage is handled separately from the html file itself. Instead, we use CSS (cascading style sheets) to style webpage however we want!



