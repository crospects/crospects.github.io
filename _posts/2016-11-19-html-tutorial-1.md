---
title: "HTML Tutorial 1: Getting Started"
layout: page
date: 2016-11-19 9:00:00 -0800
---

So, you want to learn HTML. Maybe you want to make an awesome website, chat app, or just progress your programming skills to the next level. Either way, you've come to the right place.

In order to get started programming, you'll need something to write your code in. For this, you need a plain text editor. You could use a program like TextEdit on Mac or Notepad on Windows, but I preffer to use an application called [Brackets](http://brackets.io).

Brackets will automatically highlight your code to make it easier to read, and will give you suggestions on what to type, wich greatly speeds up development.

The first thing you'll need to do is create a folder on your computer. This is where all of your HTML will be stored. Call it `My Awesome Website`.

Next, open up the folder in Brackets, or a text editor of your choice, and create a new file (`cmnd + N` on a Mac, `cntrl + N` on a PC) and title it `index.html`. This tells the computer that this is the "index" file, wich will be the file that is rendered first when you open the website. Think of it as the homepage. You allways need an `index.html` file in any website you make, or it won't work.

Now, click the lightning bolt icon in Brackets to launch live preview mode (You will need chrome installed for this to work), a blank white page should open up in Chrome. Congratulations, you have a (really borring) website!

Ok, now for the fun stuff. Inside your `index.html` file, add the following to your site:
``` html
<!doctype html>
<html lang="en">

</html>
```
The HTML language uses tags, wich is basically a fancy way of saying that everything follows this basic syntax:

```html
<tagname>
    Tag Content
</tagname>
```
There are tons of different tags, and each does something different, but for now, lets go over the tags you just learned.

The `<!doctype>` tag tells the browser what type of document this is. In our hase it is `<!doctype html>`. You need to have this at the beginning of every HTML document you make, or the browser won't understand what language you're writing in.

Next, the `<html>` tag tells the browser that you're starting to write in HTML, everything within this tag will be rendered as HTML. We also tell the browser that we're wrighting in English, with `<html lang="en">`. Now we can start adding in some cool content:

``` html
<!doctype html>
<html lang="en">
    <head>
        
    </head>
    <body>
        
    </body>
</html>
```

Ok, now we've added in a `<head>` tag and a `<body>` tag. The `<head>` tag has all the meta-data, everything that's not shown, but that the browser needs to know, like the pages title. The `<body>` tag has everything that you want to show on the website. Now, let's add a title to our website:

``` html
<!doctype html>
<html lang="en">
    <head>
        <title>
            My Awesome Website
        </title>
    </head>
    <body>
        
    </body>
</html>
```

What we just added is pretty simple. We told the browser that the title of our website is My Awesome Website. You should see this pop up on the tap name in Chrome, using live preview. 
> Hint: You can just keep Live Preview running while you work, and it will automatically show the site updated as you work! If you accidentally closed it, just click the lightning bolt icon in the top-right corner again to re-launch it.

Now that you know how to title the website, try adding your own cool title to it.

Ok, let's start adding some content to our website. In HTML if you put text somewhere without a tag around it, it will be rendered as plain text. So just add your own text to the `<body>` of the website:

``` html
<!doctype html>
<html lang="en">
    <head>
        <title>
            My Awesome Website
        </title>
    </head>
    <body>
        I am learning HTML!
    </body>
</html>
```

You could do this, but it usually a better idea to use a `<p>` tag, wich is short for paragraph. This way, their will automatically be spaces between `<p>` tags.

``` html
<!doctype html>
<html lang="en">
    <head>
        <title>
            My Awesome Website
        </title>
    </head>
    <body>
        <p>Paragraph 1</p>
        <p>Paragraph 2</p>
        <p>Paragraph 3</p>
    </body>
</html>
```

Try out adding your own content to your website, using `<p>` tags. Now, if you want to add a title, or just some larger text, you can use a header tag. Their are six types of header tags, ragning from `<h1>`, the largest to `<h6>`, the smallest. Using this scale, you have a lot of options as to wich size to use. Try it out for yourself

``` html
<!doctype html>
<html lang="en">
    <head>
        <title>
            My Awesome Website
        </title>
    </head>
    <body>
        <h1>Header size 1</h1>
        <h2>Header 2</h2>
        <h3>Header 3</h3>
        <h4>Header 4</h4>
        <h5>Header 5</h5>
        <h6>Header 6</h6>
    </body>
</html>
```
Try this out, and check out how the different header sizes look. Now let's move on to lists. Lists are slightly more complicated. First you need to put the list in either an unordered list `<ul>` or ordered list `<ol>`. Then you put each item in the list in a list item tag `<li>`.

``` html
<!doctype html>
<html lang="en">
    <head>
        <title>
            My Awesome Website
        </title>
    </head>
    <body>
        <ul>
            <li>List item 1 (un ordered list)</li>
            <li>List item 2</li>
        </ul>
        
        <ol>
            <li>List item 1 (ordered list)</li>
            <li>List item 2</li>
        </ol>
    </body>
</html>
```
Now all you need to do is mix and match these tags to make your own website. In the next tutorial,  I will show you how to add tables, and a littles styling. If you want more information, I recommend checking out [Stack Overflow](http://stackoverflow.com), a community of programmers, where you can ask questions, and talk to expert developers. You can also email me if you have any questions.