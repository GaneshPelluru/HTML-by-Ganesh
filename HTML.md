# HTML-by-Ganesh

## This tutorial is about the HTML Course


## - Contents
   - What is HTML
   - Tags Used in HTML
   - History of HTML
   - Overview of HTML
   - world without HTML
   - Writing Code by using HTML



- ### `What is HTML?`


  - `HyperText Markup Language`, or HTML. It is a markup language that is utilized to design and generate web pages. To describe the text, pictures, links, and multimedia on a webpage, it employs a set of tags and attributes.

  - HTML pages are made up of several elements that are contained in tags. Tags are used to specify how the material is formatted and organized. The tag, for instance, is used to insert an image as well as specify headings, paragraphs, and paragraphs.


  - Additionally, HTML enables you to link between other web sites and incorporate multimedia elements like audio and video into your webpages.

  - Anyone interested in developing websites or online apps must have a solid understanding of HTML, which is the foundation of web development. It is simple to use and has a sizable developer community that contributes to its continuous growth and improvement.

### `Tags That are used in Html:`
HTML uses tags to define the structure and formatting of content within a webpage. Here are some of the most commonly used HTML tags:

1. `<html>` - Defines the beginning and end of an HTML
              document
2. `<head>` - Defines the head section of an HTML document, 
         which contains metadata such as the title of the webpage
3.  `<body>` - Defines the body section of an HTML document, 
         which contains the visible content of the webpage
4.  `<p>` -    Defines a paragraph
5.  `<h1> to <h6>` - Defines headings of different sizes and
                     levels
6.  `<a>` -    Defines a hyperlink
7. `<img>` -   Inserts an image
8. `<ul>` -    Defines an unordered list
9. `<ol>` -   Defines an ordered list
10. `<li>` - Defines a list item
11. `<table>` - Defines a table
12. `<tr>` - Defines a table row
13. `<td>` - Defines a table cell
14. `<form>` - Defines a form for user input
15. `<input>` - Defines an input field within a form
16. `<select>` - Defines a dropdown list within a form
17. `<button>` - Defines a clickable button
18. `<div>` - Defines a section or division within a webpage
19. `<span>` - Defines a small section of text
20. `<br>` - Inserts a line break


There are many more HTML tags available, but these are some of the most commonly used ones.

- ### `Creators of HTML:`


   - HTML was developed by `Tim Berners-Lee and his team at CERN (European Organization for Nuclear Research) in the early 1990s`. The initial version of HTML, HTML 1.0, was released in 1993, and it was followed by several other versions, each introducing new features and improvements.

   - `Berners-Lee developed HTML as a means of sharing scientific information among researchers across different computer systems`. He wanted to create a way for scientists to easily exchange documents and data over the internet, regardless of the platform or software they were using.

- ### `History of HTML:`

  - At the CERN (European Organisation for Nuclear Research) in Switzerland, `Tim Berners-Lee and his colleagues originally invented HTML, or HyperText Markup Language, in the early 1990s`. The World Wide Web was a project that Berners-Lee was working on that sought to establish a worldwide network of connected information and resources that could be accessed online.

  - `1993 saw the introduction of HTML 1.0, the first version of HTML`. Users could build simple web pages with text, links, and images using this straightforward language's constrained set of tags and properties. With the addition of new tags and features to allow more sophisticated web design and functionality.
  -  HTML experienced a number of changes and upgrades during the following several years.

  - Tables, form elements, and image maps were among the new capabilities added to HTML `2.0 in 1995`. In `1997, HTML 3.2 was released`, adding even more sophisticated capabilities including frames and style sheets.

  - A significant upgrade to HTML, `HTML 4.0 was launched in 1997` and included new tags and properties for `multimedia, scripting, and sophisticated layout and formatting`. Additionally, it supported cascading style sheets (CSS), enabling more adaptable and effective web design.

  -  HTML is a vital tool for online designers and developers today, and it is always developing with new iterations and upgrades to meet the web's shifting requirement.
 
 
 
 # world without html:
   - A world without HTML would be a very different place, especially in terms of how we interact with information on the internet. HTML, or Hypertext Markup Language,      is the standard markup language used to create web pages, and it allows developers to structure and format content on the web.
   - Without HTML, it would be difficult to create web pages as we know them today. Websites would likely be much more basic, consisting mostly of text and simple
     images. There would be no hyperlinks to other pages, no embedded videos, and no interactive elements such as forms or animations.
   - In this world without HTML, other technologies would likely emerge to fill the gap. Perhaps a new markup language would be developed, or alternative ways of   
     structuring web content would be created. However, the way we interact with information on the web would be fundamentally different, and we would have to adapt to
     a new way of consuming and sharing content.
     
 ## world without HTML:
 
   - A world with HTML is the world we live in today, where we rely heavily on the internet for communication, commerce, entertainment, and much more. HTML, along with       other web technologies such as CSS and JavaScript, allows us to create complex and dynamic web pages that can be accessed by anyone with an internet connection.
   - Thanks to HTML, we can browse the web and navigate between different websites through hyperlinks, which allow us to access a vast network of information and            resources. HTML also enables us to structure and format content on the web, making it easier to read and more visually appealing. For example, headings,                paragraphs, lists, and tables can be used to organize information and create clear hierarchies.
   - Moreover, HTML is the foundation for creating interactive web pages that allow users to perform a variety of actions, such as filling out forms, watching videos,      playing games, and engaging with social media. This level of interactivity is made possible by technologies such as JavaScript and AJAX, which can be used t0          create dynamic user interfaces that respond to user input in real-time.
   - In summary, HTML plays a crucial role in shaping the way we access, consume, and interact with information on the internet, and it will continue to be an              essential technology as the web evolves and expands.


 # _Now let's try to write a code by using the html tags in the HTML Programming_:

        <html>
             <head>
              <title>
                  This is my first webpage!!!!
              </title>
            </head>
            <body>
                <h1>----Hi to Every one----</h1> 
                <p>.....This is my first web page about  
                         about the HTML.....</p>
           </body>
        </html>


- Note: To get the output we need to Install the Live server in the source editior

- The output for the above html code will be like

  - <img width="408" alt="Picture1" src="https://user-images.githubusercontent.com/128490912/232207209-76328d5b-f9b1-4797-94fd-87946e48c570.png">


  - The brief explaination about the output is;

  - ![Picture2 html](https://user-images.githubusercontent.com/128490912/233066847-5d65b617-4b23-4f3d-bfbd-8ed75318381e.jpg)

## THE BELOW EXAMPLE IS OF THE FAMILY TREE DIAGRAM  
## - THE CODE IS ABOUT IN FORM OF HTML 

          
              <!DOCTYPE html>
               <html>
               <head>
              <title>Family Tree Diagram</title>
               <style>
               .tree ul {
                padding-top: 20px;
               position: relative;
               text-align: center;
      white-space: nowrap;
    }
    .tree ul::before {
      content: '';
      position: absolute;
      top: 0;
      bottom: 0;
      left: 50%;
      border-left: 1px solid #ccc;
    }
    .tree li {
      display: inline-block;
      vertical-align: top;
      text-align: center;
      list-style-type: none;
      position: relative;
      padding: 20px 5px 0 5px;
    }
    .tree li::before, .tree li::after {
      content: '';
      position: absolute;
      top: 0;
      right: 50%;
      border-top: 1px solid #ccc;
      width: 50%;
      height: 20px;
    }
    .tree li::after {
      right: auto;
      left: 50%;
      border-left: 1px solid #ccc;
    }
    .tree li:only-child::after, .tree li:only-child::before {
      display: none;
    }
    .tree li:only-child {
      padding-top: 0;
    }
    .tree li:first-child::before, .tree li:last-child::after {
      border: 0 none;
    }
    .tree li:last-child::before {
      border-right: 1px solid #ccc;
      border-radius: 0 5px 0 0;
    }
    .tree li:first-child::after {
      border-radius: 5px 0 0 0;
    }
    .tree ul ul::before {
      content: '';
      position: absolute;
      top: 0;
      left: 50%;
      border-left: 1px solid #ccc;
      width: 0;
      height: 20px;
    }
    .tree li a {
      border: 1px solid #ccc;
      padding: 5px 10px;
      text-decoration: none;
      color: #666;
      font-family: arial, verdana, tahoma;
      font-size: 14px;
      display: inline-block;
      background-color: lightgray;
      border-radius: 5px;
    }
    .tree h1 {
      text-align: center;
      font-size: 24px;
      margin-bottom: 20px;
    }
             </style>
             </head>
             <body>
             <div class="tree">
    <h1>My Family Tree</h1>
    <ul>
      <li>
        <a href="#">Balamurali (Father)</a>
        <ul>
          <li>
            <a href="#">Ganesh (Child 1)</a>
          </li>
          <li>
            <a href="#">Lavanya (Child 2)</a>
          </li>
        </ul>
      </li>
                 <li>
                <a href="#">Varalakshmi (Mother)</a>
             </li>
            </ul>
            </div>
            </body>
              </html>


 - This is one of the example of html 

 - Output:     
  <img width="611" alt="Capture" src="https://github.com/GaneshPelluru/HTML-by-Ganesh/assets/128490912/d72b8e6f-823e-4e8c-b998-ccf5803acb1d">
