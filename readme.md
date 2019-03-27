# Introduction to HTML and CSS

## Repo short URL [htmlrepo.sage.codes](https://github.com/sagecodes/learn-to-code-html-css)

## Do these things first!
- Download and install a text editor
    - [VS Code](https://code.visualstudio.com/)
    - [Atom](https://atom.io/)
    - Or use an onlone editor like [codepen](https://codepen.io/) 
- I also recommend using [chrome](https://www.google.com/chrome/) as a web browser.


WIFI: `Galvanize Guest Seattle` (no password)

<!--###### Download the files for this class:
1. Go to [https://github.com/GalvanizeOpenSource/l2c-html-css-2018](https://github.com/GalvanizeOpenSource/l2c-html-css-2018)
2. Click on the button on the right-hand side that says "Download ZIP"
3. Go to your downloads folder and double click on the .zip file to unzip it
4. IMPORTANT! Leave all the individual files in the downloaded folder (if you would like to move it out of the downloads folder move the entire folder, not individual items)
5. From Atom: File > open, select the folder and then click "Open"
6. From Atom: If the file tree does not appear on the left hand View > Toggle Tree View -- this will show you the entire folder within Atom
7. *Now if you already know some of what we're talking about,* you're all set to poke around in the files -- `index.html` and `CSS/style.css` are the two files we will using.
8. The `examples` folder contains an example of a simple web page using HTML and CSS. If you get stuck you might want to refer to the example page.
-->
 
## What this workshop is

A super friendly introduction to web development with HTML and CSS! No previous experience expected! 

You can't learn EVERYTHING in ~2 hours. But you can learn enough to get excited and comfortable to keep working and learning on your own! Come to our weekly code hours [meetups](https://www.meetup.com/Learn-Code-Seattle/events/) to ask questions if you get stuck and show off what you've been working on!

- This course is for absolute beginners
- Ask Questions!
- Answer Questions!
- Its ok to get stuck, just ask for help!
- Feel free to move ahead
- Help others when you can
- Be patient and nice


## About me:
Hello I'm [Sage Elliott](http://sageelliott.com/). I'm a Technology Evangelist at Galvanize Seattle. Previously I've worked as a software and hardware engineer with Startups and Agencies in Seattle, WA and Melbourne, FL. I love technology! I'm currently learning more about how to build AI and VR projects (I can't wait to do a workshop round these topics)! 

*caveat* I'm not an Galvanize instructor, they're much better at teaching than I am! :D

If you have an event you would like to see or put on let me know! I'm always looking for ideas. Talk to me after the workshop or find me online at one of these:

- Website: [sageelliott.com](http://sageelliott.com/)
- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)


## About you!

Give a quick Intro!

- Whats your name?
- Whats your background?
- Why are you interested in Web Development?

## What is HTML and CSS?

Two of the main building blocks of the web!

- HTML (Hyper Text Markup Language)
- CSS (Cascading Style Sheets)

An analogy you can think of for the scope of this workshop:

HTML is sort of like bones. Its the structure of the web page.

CSS is similar to skin. It adds style and changes the appearance of the page. 

JavaScript is like the Muscle. It can change and move elements around on the page(not covered in this workshop). 

Is there a "brain"? Yes! There are many languages that can used to access databases, perform complicated calculations and send/receive information. Some common languages: Javascript, Python, Ruby, PHP. 

### Who uses HTML & CSS?

Some Professional Roles that work with HTML & CSS:

- Full-Stack Web Developer
- Front-End Developer
- Web Designer

Some Companies that use HTML & CSS:

- Google
- Facebook
- Microsoft
- Pretty much anyone with web products

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


###### Self-closing Tags:
most HTML tags require an opening and a closing tag. There are a few however that do not:

- `<img src="">` creates an image in the page
- `<br>` creates a break in the content
- `<input type="">` creates an input field
- `<hr>`	Creates a line in the page 

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
- 1. Make a large header with the name of your site using an `<h1>` element

`<h1>Sage Elliott</h1>`

- 2. add a photo using the `<img>` element (remember `img` doesn't need a closing tag) Use a image URL from social media or elsewhere! We're going to add an ID for styling later!

`<img id="profile-picture" src="http://sageelliott.com/img/sage2016.jpg" title="Sage Elliott" alt="photo of Sage">`

- 3. make a paragraph using the `<p>` element

`<p>Hello I'm Sage Elliott!</p>`

- 4. Create a link to another page (twitter, other)

`<a class="btn" href="https://twitter.com/@sagecodes" title="@Sagecodes">Twitter</a>`

- 5. make a smaller page header using the `<h2>` element

`<h2>Projects:</h2>`

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

###### CSS Grid

Its best practice now days to make sure your site if mobile responsive. It used to be common to use a 3rd party library like Bootstrap to make a grid system to change where content is placed on a website depending on the size of the screen. It was also possible to do this using some simple math and [media queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp), but now its even simpler and easy to do with [CSS Grid](https://www.w3schools.com/css/css_grid.asp)!



Basic Grid example:

```
  .grid {
    max-width: 800px;
    margin: 45px auto;
    display: grid;
    grid-gap: 20px;
    grid-template-columns: 100px 100px 100px;
    grid-template-rows: 200px 200px 200px 200px;
    padding: 20px;
}

```

Flexible space implicit example:

```
  .grid {
    max-width: 800px;
    margin: 45px auto;
    display: grid;
    grid-gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-auto-rows: 200px;
    padding: 20px;
}
```

Use repeat function

repeat(3, 1fr)



Learn more CSS [here](https://www.w3schools.com/css/)

## Lets Write some CSS!

- 1. change the background and font color and look at some other styling options


```
body {
    padding-top: 30px;
    text-align: center;
    font-family: Georgia, serif;
    font-weight: normal;
    color: #333;
    font-size: 20px;
    background: #fff;
  }
```


- 2. change the width of your image  and look at some other styling options

```
  #profile-picture {
    width: 200px;
    padding: 15px 0;
    margin: 0 auto 0px;
    border-radius: 20%;
  }
  
```

- 3. Style our link into a button & and add a hover affect

```
  .btn {
    background: #829aa8;
    border: solid 1px #829aa8;
    color: #fff;
    padding: 10px;
    text-decoration: none;
    border-radius: 5%;
  }
  
  .btn:hover {
    background: #e8e8e8;
    color: #829aa8;
  }
  
```

- 4. Add some style to our Projects

```
  .project {
    text-align: center;
    color: #fff;
    padding: 25px;
    background:#5e9eff;
    border-radius: 0.3em;
    box-shadow: 3px 3px 5px #888888;
    text-decoration: none;
}

```

- 5. Create a responsive Grid

```
  .grid {
    max-width: 800px;
    margin: 45px auto;
    display: grid;
    grid-gap: 20px;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    grid-auto-rows: 200px;
    padding: 20px;
}
```


## Congratulations

Awesome job! You made a web page! You're a web developer! :)

you can see the completed codepen example [here](https://codepen.io/sagecodes/pen/PBvLvY?editors=1100) or look in the example folder in this repo.

## Challenge:
The best way to learn is to keep practicing and challenge yourself! Here are some ideas!

- Design a new layout
- Use multiple CSS grids on your site!
- use CSS [transitions](https://www.w3schools.com/css/css3_transitions.asp) and [animations](https://www.w3schools.com/css/css3_animations.asp)

Show off your project at the next [code hours](https://www.meetup.com/Learn-Code-Seattle/events/)!

## Keep Learning! 
Start learning Software Engineering with our FREE online prep course!
[https://www.galvanize.com/web-development/prep](https://www.galvanize.com/web-development/prep)

Start learning Data Science with our FREE online prep course!
Premium option is free if you sign up today! [http://bit.ly/2u0cahU](http://bit.ly/2u0cahU)

[https://www.w3schools.com/](https://www.w3schools.com/) is a great resource for learnig more about web development!


## Upcoming Events!
We host many events! check out out our [meetup](https://www.meetup.com/Learn-Code-Seattle/events/) to stay up to date.


- Intro to Machine Learning with Python - 3/28 6:30 - 8:30pm
- JavaScript Mini Bootcamp: Fundamentals II - 3/30 10am - 4:30pm
- Intro to Data Analytics with Tableau - 4/04 6:30 - 8:30pm
- JavaScript Mini Bootcamp: Fundamentals I - 4/13 10am - 4:30pm
- JavaScript 101 - 4/17 6:30 - 8:30pm


## What is Galvanize?

#### Immersive Bootcamp

- [Software Engineer](https://www.galvanize.com/web-development) - 4/8/19 - 7/5/19
- [Data Science](https://www.galvanize.com/data-science) - 5/6/19 - 8/6/19


#### Part-Time Courses

- [Digital Marketing](https://www.galvanize.com/part-time/digital-marketing) - 5/13/19 - 6/7/19

#### Co-working Space

[work in our building!](https://www.galvanize.com/entrepreneur)

## Questions

Please feel free to reach out to me with any questions! Let me know what you're planning to do next and how I can help!


- Website: [sageelliott.com](http://sageelliott.com/)
- Twitter: [@sagecodes](https://twitter.com/@sagecodes)
- LinkedIn: [sageelliott](https://www.linkedin.com/in/sageelliott/) 
- Email: [sage.elliott@galvanize.com](mailto:sage.elliott@galvanize.com)