# HTML_Introduction

## Please note that this tutorial was created for Polygon Africa bootcamp Web2 beginners(this means people who want to learn HTML, CSS, Javascript and React), and we meet by 7pm every day on the discord voice channel.

# Video Tutorial - https://youtu.be/9xUM1iDDR-E

If you miss the live HTML class, then we've probably moved on to CSS, there's a video link at the top of this text to help you.

Also, Web2 developers who are getting started with Web3 meet by 9pm, every Monday, Wednesday, and Friday on the discord voice channel.

This tutorial was drawn from codeacademy.com, so feel free to have more hands-on learning there, it's free.

HTML is the backbone of the Web. The HyperText Markup Language or HTML is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript.

HTML stands for HyperText Markup Language:

A markup language is a computer language that defines the structure and presentation of raw text.


HyperText is text displayed on a computer or device that provides access to other text through links, also known as hyperlinks. You probably clicked on a couple of hyperlinks on your way to this Codecademy course.

Learning HTML is the first step in creating websites, but even a bit of knowledge can help you inject code snippets into newsletter, blog or website templates. As you continue learning, you can layer HTML with CSS and JavaScript to create visually compelling and dynamic websites. But for now, we’re going to focus on how to add and modify basic content on a page, like text, images, and videos. Don’t worry if the websites look ugly — we’re just getting started.

# Class 1

In this introductory session, you will be getting started with buiding mini websites with HTML.

First steps:

-Open a new folder and name it 'HTML'.
-Inside this folder, create text document(with notepad) and name it index.txt
-Now open index.txt and write the following code:

```
<html>

</html>
```

This is an opened HTML tag and closed HTML tag. Every website on the internet starts with an opened and closed HTML tag.

Next give it an head and body tag:

```
<html> 

<head>

</head>

<body>

</body>

</html>
```

Notice how we open a tag with ```<>``` and close the tag with ```</>```

Now inside the head tag, let's give it a title tag:

```
<html>

<head>

<title>
My first site
</title>

</head>

<body>

<h1>
Welcome to my first Website.
</h1>

</body>

</html>
```

Now save the index.txt file.

Next us the 'save as' option and save as index.html.

This will create a webpage in the HTML folder. Go to the folder and click on the web page.

Congratulations, you just designed your first web page.

# HTML Anatomy

![Screenshot 2022-10-11 at 16 19 10](https://user-images.githubusercontent.com/29931071/195134365-5da51b77-d517-442b-a1f6-28afa8c460f2.png)

The diagram to the right displays an HTML paragraph element. As we can see, the paragraph element is made up of:

An opening tag ```<p>```
The content ```(“Hello World!” text)```
A closing tag ```</p>```

A tag and the content between it is called an HTML element. 

There are many tags that we can use to organize and display text and other types of content, like images.

# The Body

One of the key HTML elements we use to build a webpage is the body element. 

Only content inside the opening and closing body tags can be displayed to the screen. Here’s what opening and closing body tags look like:

```
<body>
 
</body>
```

Once the file has a body, many different types of content – including text, images, and buttons – can be added to the body.

```
<body>
  <p>What's up, doc?</p>
</body>
```

## Class Work:

Now open your index.txt file and add the following code to the body element:

```
<p> Here's how i'm learning to build websites at Polygon Africa Bootcamp </p>
```

Now your entire code should look like this:

Index.txt:
```
<html>

<head>

<title>
My first site
</title>

</head>

<body>

<h1>
Welcome to my first Website.
</h1>

<p> Here's how i'm learning to build websites at Polygon Africa Bootcamp </p>

</body>

</html>
```

Save index.txt.
Now use the 'save as' option and save as index.html

Now you can refresh your website to see the changes.

#Class 2

# HTML Structure

HTML is organized as a collection of family tree relationships. 

As you saw in the last class, we placed ```<p>``` tags within ```<body>``` tags. When an element is contained inside another element, it is considered the child of that element. 
  
The child element is said to be nested inside of the parent element.
  
```
<body>
  <p>This paragraph is a child of the body</p>
</body>
```
  
In the example above, the ```<p>``` element is nested inside the <body> element.
  
Let’s consider a more complicated example that uses some new tags:
  
```
<body>
  <div>
    <h1>Sibling to p, but also grandchild of body</h1>
    <p>Sibling to h1, but also grandchild of body</p>
  </div>
</body>
```

In this example, the ```<body>``` element is the parent of the ```<div>``` element. 
  
Both the ```h1``` and ```p``` elements are children of the ```<div>``` element. 
  
Because the ```h1``` and ```p``` elements are at the same level, they are considered siblings and are both grandchildren of the ```<body>``` element.
  
# Class work 2
  
Open your index.txt file, make a ```<div>``` element a parent of the ```h1``` and ```p``` element.
  
Your index.txt file would look like this:
  
```
<html>
 
<head>
 
<title>
My first site
</title>
 
</head>
 
<body>
 
<div>
 
<h1>
Welcome to my first Website.
</h1>
 
<p> Here's how i'm learning to build websites at Polygon Africa Bootcamp </p>
 
</div>
 
</body>
 
</html>
```

## The Head Element.

Several things can go inside the head element but one of the most import elements that goes there is the title element.  

This determines what you see at the very top of your webpage.

## Class Work:

Now change the text in your title element to 'mywebsite.com'
 
Your index.html file should now be:
 
```
<html>
 
<head>
 
<title>
mywebsite.com
</title>
 
</head>
 
<body>
 
<div>
 
<h1>
Welcome to my first Website.
</h1>
 
<p> Here's how i'm learning to build websites at Polygon Africa Bootcamp </p>
 
</div>
 
</body>
 
</html>
```
 


# Headings

 You've already used an heading element in ```h1``` above.
 
In HTML, there are six different headings, or heading elements. 
 
Headings can be used for a variety of purposes, like titling sections, articles, or other forms of content.
 
 They are ordered from largest to smallest in size.

- h1— used for main headings. All other smaller headings are used for subheadings.
- h2
- h3
- h4
- h5
- h6

## Class work
 
Now add this to your body element:
 
```
 <h1>Polygon Africa Bootcamp</h1>
 <h2>My first time building responsive websites</h2>
 <h3>HTML seems so beautiful</h3>
 <h3>I think i'm enjoying this</h3>
 ```
 
 What you will discover is the size difference of the differing tags.
 
 Your index.html file will be:
 
 ```
<html>
 
<head>
 
<title>
mywebsite.com
</title>
 
</head>
 
<body>
 
<div>
 
<h1>
Welcome to my first Website.
</h1>
 
<p> Here's how i'm learning to build websites at Polygon Africa Bootcamp </p>
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
</body>
 
</html>
```
 
 # Div Element

 One of the most popular elements in HTML is the ```div``` element. ```<div>``` is short for “division” or a container that divides the page into sections.
 
 These sections are very useful for grouping elements in your HTML together. Like:
 
 ```
 <body>
  
  <div>
   
    <h1>Why use divs?</h1>
    <p>Great for grouping elements!</p>
   
  </div>
  
</body>
 ```
 
 ```div``` don’t inherently have a visual representation, but they are very useful when we want to apply custom styles to our HTML elements.
 
 ```div```s allow us to group HTML elements to apply the same styles for all HTML elements inside.
 
 Also, ```div```s can contain any text or other HTML elements, such as links, images, or videos.
 
 ## Class Work
 
 Now nest the headings you wrote last into a new ```div``` element.
 
 This is your index.html:
 
 ```
<html>
 
<head>
 
<title>
mywebsite.com
</title>
 
</head>
 
<body>
 
<div>
 
<h1>
Welcome to my first Website.
</h1>
 
<p> Here's how i'm learning to build websites at Polygon Africa Bootcamp </p>
 
</div>
 
<div>
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
</body>
 
</html>
 ```
 
 You can see that all the elements in the body are nested into a ```div``` element.
 
 Now create another ```div``` element, open and close it and insert another heading and paragraph:
 
 ```
 <h1>
  This is the new heading under the new div element
 </h1>
 <p>
 This just explains how to structure an HTML site with divs.
 </p>
 ```

So your final html file should be:
 
```
<html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div>
 
<h1>
Welcome to my first Website.
</h1>
 
<p> Here's how i'm learning to build websites at Polygon Africa Bootcamp </p>
 
 </div>
 
 <div>
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div>
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 This just explains how to structure an HTML site with divs.
 </p>
 
</div>
 
</body>
</html>
 ```

 Now note that we've grouped our elements under 3 ```div```s.
 
# Attributes
 
If we want to expand an element’s tag, we can do so using an attribute. 
 
Attributes are content added to the opening tag of an element and can be used in several different ways, from providing information to changing styling. 
 
Attributes are made up of the following two parts:

- The name of the attribute
- The value of the attribute
 
 One commonly used attribute is the id.
 
 For example:
 
 ```
 <div id="intro">
  <h1>Introduction</h1>
</div>
 ```
 
 See how we gave this div an attribute of name=id and value="intro".
 
 ## Class work
 
 In your index.html file, you have 3 ```div```s, now add an id attrubute to the 3 divs. 
 
 Give the first a value of "first attribute"
 
 Give the second a value of "second attribute"
 
 Give the third a value of "third attribute"
 
 Now your index.html file should look like this:
 
 ```
 <html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div id="first attribute">
 
<h1>
Welcome to my first Website.
</h1>
 
<p> Here's how i'm learning to build websites at Polygon Africa Bootcamp </p>
 
 </div>
 
 <div id="second attribute">
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div id="third attribute">
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 This just explains how to structure an HTML site with divs.
 </p>
 
</div>
 
</body>
</html>
 ```
 
 Did you notice that attributes always appear at the opening of the tag?
 
 Exactly.
 
 Also ```div``` is not the only element that can take an attribute, every other element can.
 

# Displaying Text

If you want to display text in HTML, you can use a paragraph or span:

Paragraphs ```p``` contain a block of plain text.
 
```span``` contains short pieces of text or other HTML. 
 
 They are used to separate small pieces of content that are on the same line as other content.
 
 For example:
 
```
<div>
 
  <h1>Technology</h1>
 
</div>
 
<div>
 
  <p> <span>Self-driving cars</span> are anticipated to replace up to 2 million jobs over the next two decades.</p>
 
</div>
```
 

# Styling Text
 
You can also style text using HTML tags. 
 
 The ```<em>``` tag emphasizes text, while the ```<strong>``` tag highlights important text.
 
Browsers, however, have built-in style sheets that will generally style these tags in the following ways:

- The ```<em>``` tag will generally render as italic emphasis.
- The ```<strong>``` will generally render as bold emphasis.
 
## Class Work
 
 Style the paragraph in the first div with an ```<em>``` tag
 
 Style the paragraph in second div with a ```<strong>``` tag
 
 ```
<html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div id="first attribute">
 
<h1>
Welcome to my first Website.
</h1>
 
 <p><em> Here's how i'm learning to build websites at Polygon Africa Bootcamp </em></p>
 
 </div>
 
 <div id="second attribute">
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div id="third attribute">
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 <strong>
 This just explains how to structure an HTML site with divs.
 </strong>
 </p>
 
</div>
 
</body>
</html>
 ```
 
 
 # Line Breaks
 
The spacing between code in an HTML file doesn’t affect the positioning of elements in the browser. 
 
If you are interested in modifying the spacing in the browser, you can use HTML’s line break element: <br>.
 
Example:
 
```
<p>The Nile River is the longest river <br> in the world, measuring over 6,850 <br> kilometers long (approximately 4,260 <br> miles).</p>
```
 
 
# Class Work:
 
Add two line breaks (<br>) to any paragraph in the index.html file and see the effect.
 
This is my index.html:
 
```
<html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div id="first attribute">
 
<h1>
Welcome to my first Website.
</h1>
 
 <p><em> Here's how i'm learning to build <br> websites at Polygon Africa Bootcamp </em></p>
 
 </div>
 
 <div id="second attribute">
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div id="third attribute">
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 <strong>
 This just explains how to <br> structure an HTML site with divs.
 </strong>
 </p>
 
</div>
 
</body>
</html>
 ```
 
 Notice that ```br``` does not need a closing tag.
 
 
 # Unordered List
 
In HTML, you can use an unordered list tag (<ul>) to create a list of items in no particular order. 

An unordered list outlines individual list items with a bullet point.

The <ul> element should not hold raw text and won’t automatically format raw text into an unordered list of items. 

Individual list items must be added to the unordered list using the <li> tag. The <li> or list item tag is used to describe an item in a list.

For example:

```
<ul>
  <li>Limes</li>
  <li>Tortillas</li>
  <li>Chicken</li>
</ul>
```

## Class Work

In your index.html file, create a new div and nest:

1. A paragraph: "This are the web2 technologies i'm learning at the Polygon Africa Bootcamp"

2. An unordered list containing
-  HTML
- CSS
- JavaScript
- React
 
 
 Your index.html will look like this:
 
```
<html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div id="first attribute">
 
<h1>
Welcome to my first Website.
</h1>
 
 <p><em> Here's how i'm learning to build <br> websites at Polygon Africa Bootcamp </em></p>
 
 </div>
 
 <div id="second attribute">
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div id="third attribute">
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 <strong>
 This just explains how to <br> structure an HTML site with divs.
 </strong>
 </p>
 
</div>

<div>

<p>
This are the web2 technologies i'm learning at the Polygon Africa Bootcamp
</p>

<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>React</li>
</ul>

</div
 
</body>
</html>
 ```


# Ordered List

Ordered lists ```<ol>``` are like unordered lists, except that each list item is numbered.

It looks like this:

```
<ol>
  <li>Preheat the oven to 350 degrees.</li>
  <li>Mix whole wheat flour, baking soda, and salt.</li>
  <li>Cream the butter, sugar in separate bowl.</li>
  <li>Add eggs and vanilla extract to bowl.</li>
</ol>
```

## Class Work:

Now change the unordered list in your index.html file to an ordered list.

Your index.html file will look like this:


```
<html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div id="first attribute">
 
<h1>
Welcome to my first Website.
</h1>
 
 <p><em> Here's how i'm learning to build <br> websites at Polygon Africa Bootcamp </em></p>
 
 </div>
 
 <div id="second attribute">
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div id="third attribute">
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 <strong>
 This just explains how to <br> structure an HTML site with divs.
 </strong>
 </p>
 
</div>

<div>

<p>
This are the web2 technologies i'm learning at the Polygon Africa Bootcamp
</p>

<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>React</li>
</ol>

</div
 
</body>
</html>
 ```

# Images

All of the elements you’ve learned about so far (headings, paragraphs, lists, and spans) share one thing in common: they’re composed entirely of text!

What if you want to add content to your web page that isn’t composed of text, like images?

The ```<img>``` tag allows you to add an image to a web page. 

Most elements require both opening and closing tags, but the <img> tag is a self-closing tag. 

Note that the end of the <img> tag has a forward slash /. Self-closing tags may include or omit the final slash — both will render properly.

```
<img src="image-location.jpg" />
```

The <img> tag has a required attribute called src. 

The src attribute must be set to the image’s source, or the location of the image. 

In this case, the value of src must be the uniform resource locator (URL) of the image. A URL is the web address or local address where a file is stored.

## Class Work

Inside your index.html, use this url as source for your image. Put the image inside the first div container.

URL = https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg

Your code will look like this:


```
<html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div id="first attribute">
 
<h1>
Welcome to my first Website.
</h1>
 
 <p><em> Here's how i'm learning to build <br> websites at Polygon Africa Bootcamp </em></p>
 
 <img src="https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg" />
 
 </div>
 
 <div id="second attribute">
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div id="third attribute">
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 <strong>
 This just explains how to <br> structure an HTML site with divs.
 </strong>
 </p>
 
</div>

<div>

<p>
This are the web2 technologies i'm learning at the Polygon Africa Bootcamp
</p>

<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>React</li>
</ol>

</div
 
</body>
</html>
 ```
 
 # Image Alts
 
If an image fails to load on a web page, a user can mouse over the area originally intended for the image and read a brief description of the image. This is made possible by the description you provide in the ```alt``` attribute.

## Class Work

Gi]ve the image element in index.html an alt attribute.

Your index.html will look it this:

```
<html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div id="first attribute">
 
<h1>
Welcome to my first Website.
</h1>
 
 <p><em> Here's how i'm learning to build <br> websites at Polygon Africa Bootcamp </em></p>
 
 <img src="https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg" alt="this is the image's description" />
 
 </div>
 
 <div id="second attribute">
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div id="third attribute">
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 <strong>
 This just explains how to <br> structure an HTML site with divs.
 </strong>
 </p>
 
</div>

<div>

<p>
This are the web2 technologies i'm learning at the Polygon Africa Bootcamp
</p>

<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>React</li>
</ol>

</div
 
</body>
</html>
 ```
 
 # Videos
 
In addition to images, HTML also supports displaying videos. 

Like the <img> element, the <video> element requires a src attribute with a link to the video source. 

Unlike the <img> element however, the <video> element requires an opening and a closing tag.

```
<video src="myVideo.mp4" width="320" height="240" controls>
  Video not supported
</video>
```

In this example, the video source (src) is "myVideo.mp4". 

The source can be a video file that is hosted alongside your webpage, or a URL that points to a video file hosted on another webpage.

After the src attribute, the width and height attributes are used to set the size of the video displayed in the browser. 

The controls attribute instructs the browser to include basic video controls such as pausing and playing.

## Class Work

In index.html, under the image, create a <video> tag and add the following video url as the source:

https://content.codecademy.com/courses/freelance-1/unit-1/lesson-2/htmlcss1-vid_brown-bear.mp4

Be sure to create a closing tag as well with </video>.

Now your final index.html should look like this:



```
<html>
<head>
 
<title>
My first site
</title>
 
</head>
  
<body>
 
<div id="first attribute">
 
<h1>
Welcome to my first Website.
</h1>
 
 <p><em> Here's how i'm learning to build <br> websites at Polygon Africa Bootcamp </em></p>
 
 <img src="https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg" alt="this is the image's description" />
 
 <video src="https://content.codecademy.com/courses/freelance-1/unit-1/lesson-2/htmlcss1-vid_brown-bear.mp4" 
 width="320" 
 height="240" 
 controls>
 Video not supported
 </video>
 
 </div>
 
 <div id="second attribute">
 
<h1>Polygon Africa Bootcamp</h1>
<h2>My first time building responsive websites</h2>
<h3>HTML seems so beautiful</h3>
<h3>I think i'm enjoying this</h3>
 
</div>
 
<div id="third attribute">
 
  <h1>
  This is the new heading under the new div element
 </h1>
 
 <p>
 <strong>
 This just explains how to <br> structure an HTML site with divs.
 </strong>
 </p>
 
</div>

<div>

<p>
This are the web2 technologies i'm learning at the Polygon Africa Bootcamp
</p>

<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>React</li>
</ol>

</div
 
</body>
</html>
 ```

 
