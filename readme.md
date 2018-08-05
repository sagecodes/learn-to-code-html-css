# Introduction to HTML and CSS

## Do these things first!
- Download and install a text editor
    - [VS Code](https://code.visualstudio.com/)
    - [Atom](https://atom.io/)
- I also recommend using [chrome](https://www.google.com/chrome/) as a web browser

###### Download the files for this class:
1. Go to [https://github.com/GalvanizeOpenSource/l2c-html-css-2018](https://github.com/GalvanizeOpenSource/l2c-html-css-2018)
2. Click on the button on the right-hand side that says "Download ZIP"
3. Go to your downloads folder and double click on the .zip file to unzip it
4. IMPORTANT! Leave all the individual files in the downloaded folder (if you would like to move it out of the downloads folder move the entire folder, not individual items)
5. From Atom: File > open, select the folder and then click "Open"
6. From Atom: If the file tree does not appear on the left hand View > Toggle Tree View -- this will show you the entire folder within Atom
7. *Now if you already know some of what we're talking about,* you're all set to poke around in the files -- `index.html` and `CSS/style.css` are the two files we will using.
8. The `examples` folder contains an example of a simple web page using HTML and CSS. If you get stuck you might want to refer to the example page.

 
## What this workshop is

A super friendly introduction to web development with HTML and CSS! No previous experience expected!

- This course is for absolute beginners
- Ask Questions!
- Its ok to get stuck, just ask for help!
- Feel free to move ahead
- Help others when you can
- Be patient and nice

## About me:
Hello I'm [Sage Elliott](http://sageelliott.com/). I'm a Technology Evangelist here at Galvanize! Previously I've worked as a software and hardware engineer with Startups and Agencies in Seattle, WA and Melbourne, FL. 

- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)


## About you!

Give a quick Intro!

- Whats your name?
- Whats your background?
- Why are you interested in Web Development?

## What is HTML and CSS?

Two of the main building block of the web!

- HTML (Hyper Text Markup Language)
- CSS (Cascading Style Sheets)

An analogy you can think of for the scope of this workshop:

HTML is sort of like bones. Its the structure of the web page.

CSS is similar to skin. It adds style and changes the appearance of the page. 

JavaScript is like the Muscle. It can change and move elements around on the page(not covered in this workshop). 

Is there a "brain"? Yes! There are many languages that can used to access databases, perform complicated calculations and send/receive information. Some common languages: Javascript, Python, Ruby, PHP. 


## HTML Basics

###### Some common Tags(Elements):

- `<html>`	designates an HTML document
- `<head>`	contains undisplayed information about the document
- `<title>`	Creates a title for the document
- `<body>`	contains displayed information
- `<header>, <main>, <footer>` denotes which part of the page elements belong

- `<h1> - <h6>` create section headings (h1 biggest, h6 Smallest)
- `<p>` creates paragraphs
- `<a href=""></a>` (anchor), activates a link in the page
- `<ul>, <ol>` creates lists
  - `<li>` contains items in lists
- `<br>`	Inserts a single line break
- `<hr>`	Defines a thematic change in the content

###### Self-closing Tags:
most HTML tags require an opening and a closing tag. There are a few however that do not:

- `<img src="">` creates an image in the page
- `<br>` creates a break in the content
- `<input type="">` creates an input field

###### IDs, Classes
IDs and classes are very similar.
These are used to target specific elements(You'll see more examples in CSS section).
- `<h1 id="profile-header"></h1>`
- `<h1 class="subject-header"></h1>`

- IDs should only be used once on a page. IDs can also be used to bring the user to a specific part of the page. `your-site/#profile-picture` will load the page near the profile picture. 
- Classes can be used multiple times on a page. 


See More tags [here](https://www.w3schools.com/tags/ref_byfunc.asp)

Learn more HTML [here](https://www.w3schools.com/Html/)

## Lets Write some HTML!
- Make a large header with the name of your site using an `<h1>` element
- add a photo using the `<img>` element (remember `img` doesn't need a closing tag)
- make a paragraph using the `<p>` element
- make a smaller page header using the `<h2>` element
- make an ordered or unordered list using the `<ol>`,``ul``, and `<li>` elements

## CSS Basics


###### CSS Examples:

this example targets an element `h1` and changes the font size, font weight, and color. 

```
h1 {
    font-size: 24px;
    font-weight: bold;
    color: #000000;
}
```
This example targets a class `btn` to change the background color and add padding

```
.btn {
  background: #829aa8;
  padding: 10px;
}
```
This example targets an ID `profile-picture` to change the width:

```
#profile-picture {
  width: 200px;
  }
  
```


Learn more CSS [here](https://www.w3schools.com/css/)

## Lets Write some CSS!
- change the width of your image
- change the background color
- change the font color
- style our link
- align everything center (did everything align center?)

## Upcoming Events!
[Galvanize Web Development Foundations with JavaScript - 7/23 - 8/29](https://www.eventbrite.com/e/galvanize-web-development-foundations-with-javascript-seattle-723-829-tickets-45261516414) - Use Coupon code `learn2code` for 10% off

[Galvanize Seattle Web Development Capstone Showcase (7/19)](https://www.eventbrite.com/e/galvanize-seattle-web-development-capstone-showcase-719-tickets-46775091558?aff=ebdssbdestsearch) See final projects of our graduating class!

## What is Galvanize?
###### We are a community!
#### Immersive Bootcamp
- [Data Science](https://www.galvanize.com/seattle/data-science)
- [Web Development](https://www.galvanize.com/seattle/web-development)

#### Part-Time Courses
- [Data Analytics](https://www.galvanize.com/seattle/data-analytics)
- [Web Development Foundations with JavaScript](https://www.galvanize.com/seattle/web-development-foundations)
- [Data Science Fundamentals](https://www.galvanize.com/seattle/data-science-fundamentals)
- [Front End Web Development](https://www.galvanize.com/seattle/front-end-web-development)
- [React Intensive](https://www.galvanize.com/seattle/react-intensive)

#### Co-working Space
[work in our building!](https://www.galvanize.com/entrepreneur)

#### Events 
We host sooo many events! check out out [calendar](https://www.galvanize.com/seattle/events)

## Questions:
Please feel free to reach out to me with any questions!

- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)
