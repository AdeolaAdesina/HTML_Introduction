# HTML_Introduction

## Please note that this tutorial was created for Polygon Africa bootcamp Web2 beginners(this means people who want to learn HTML, CSS, Javascript and React), and we meet by 7pm every day on the discord voice channel.

If you miss the live HTML class, then we've probably moved on to CSS, there's a video link at the end of this text to help you.

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

Notice how we open a tag with <> and close the tag with </>

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

An opening tag (<p>)
The content (“Hello World!” text)
A closing tag (</p>)

A tag and the content between it is called an HTML element. 

There are many tags that we can use to organize and display text and other types of content, like images.

# The Body

One of the key HTML elements we use to build a webpage is the body element. Only content inside the opening and closing body tags can be displayed to the screen. Here’s what opening and closing body tags look like:

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

As you saw in the last class, we placed <p> tags within <body> tags. When an element is contained inside another element, it is considered the child of that element. 
  
The child element is said to be nested inside of the parent element.
  
```
  <body>
  <p>This paragraph is a child of the body</p>
</body>
```
  
In the example above, the <p> element is nested inside the <body> element.
  
Let’s consider a more complicated example that uses some new tags:
  
```
<body>
  <div>
    <h1>Sibling to p, but also grandchild of body</h1>
    <p>Sibling to h1, but also grandchild of body</p>
  </div>
</body>
```

In this example, the <body> element is the parent of the <div> element. 
  
Both the h1 and p elements are children of the <div> element. 
  
Because the h1 and p elements are at the same level, they are considered siblings and are both grandchildren of the <body> element.
  
# Class work 2
  
Open your index.txt file, make a <div> element a parent of the h1 and p element.
  
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


# Headings

 You've already used an heading element in h1 above.
 
In HTML, there are six different headings, or heading elements. 
 
Headings can be used for a variety of purposes, like titling sections, articles, or other forms of content.
 
 They are ordered from largest to smallest in size.

- h1— used for main headings. All other smaller headings are used for subheadings.
- h2
- h3
- h4
- h5
- h6

Now add this to your body element:
 
```
 <h1>Polygon Africa Bootcamp</h1>
 <h2>My first time building responsive websites</h2>
 <h3>HTML seems so beautiful</h3>
 <h3>I think i'm enjoying this</h3>
 ```
 
 What you will discover is the size difference of the differing tags.
 
 # Div Element

 One of the most popular elements in HTML is the ```div``` element. <div> is short for “division” or a container that divides the page into sections. These sections are very useful for grouping elements in your HTML together.

