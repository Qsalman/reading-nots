#  Who want to learn how to design and build websites from scratch 
Anyone who has a website and want to make it better(that may be built using a content management system, blogging software or an e-commerce platform) and wants more control over
the appearance of their pages  The only things you need in order to use this book are a computer
with a web browser and a text editor(such as Notepad, which comes with Windows, or TextEdit, which comes with Macs).

**To explain  the pages will come next ahead in the book you are reading here is some definitions to help you :

**Introduction: pages come at the beginning of each chapter. They introduce the key topics you will learn about.

**Reference pages : introduce key pieces of HTML & CSS code. The HTML code is shown in blue and CSS code is shown in pink.

**Background pages appear on white; they explain the context of the topics covered that are discussed in each chapter.

**Diagram and infographics pages:  are shown on a dark background. They provide a simple, visual reference to topics discussed.

**Example pages:  put together the topics you have learned and demonstrate how they can be applied in each.

**Summary pages:  come at the end of each chapter. They remind you of the key topics that were covered in each chapter.


#### At work, when people look at the Programmer  screen and see it full of code, it's not unusual to get a comment about it looking very complicated or how clever he  must
#### be to understand it. The truth is, it's not that hard to learn how to write web pages and read the code used to create them; you certainly don't have to be a "programmer."
#### Understanding HTML and CSS can help anyone who works with the web; designers can create more attractive and usable sites, website editors can create better content
#### marketers can communicate with their audience more effectively, and managers can commission better sites and get the best out of their teams.

 **The Structure of This Book :

##### 1: HTML : stands for Hyper Text Markup Language. HTML is the standard markup language for creating Web pages one of the  core technologies for building Web pages.
#### 2: CSS : Cascading Style Sheets   one of the core technologies for building Web pages. 
#### 3: Practical : We end up with some helpful information that will assist you in building better websites, We look at some new tags that will be introduced in HTML5 to help describe the structure of your pages.
**we end up looking at topics that will help you once you have built your site, such as putting it on the web, search engine optimisation (SEO) and using analytics software to track who comes to your site and what they are looking at.

#### *How People Access the Web: Before we look at the code used to build websites it is important to consider the different ways in which people access the web and clarify some* *terminology:*

#### 1: Browsers : People access websites using software called a web browser. Popular examples include Firefox, Internet Explorer, Safari, Chrome, and Opera.
#### 2: Web Servers : When you ask your browser for a web page, the request is sent across the Internet to a special computer known as a web server which hosts the website.Web #### servers are special computers that are constantly 
#### connected to the Internet, and are optimized to send web pages out to people who request them.
#### 3: Screen readers :Screen readers are programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.
#### 4:Devices: People are accessing websites on an increasing range of devices including desktop computers, laptops, tablets, and mobile phones. It is important to
#### remember that various devices have different screen sizes and some have faster connections to the web than others.

##### How Websites Are Created: All websites use HTML and CSS, but content management systems  blogging software, and e-commerce platforms often add a few more technologies into the mix. 

#### How the Web Works: When you visit a website, the web server hosting that site could be anywhere in the
#### world. In order for you to find the location of the web server, your browser will first connect to a Domain Name System (DNS) server.





## Structure
**We come across all kinds of documents every day of our lives. Newspapers, insurance forms, shop catalogues ,the list goes on.

### In this chapter you will:
### See how HTML describes the structure of a web page  and  Learn how tags or elements are added to your document , Write your first web page.

**How Pages Use Structure:
Think about the stories you read in a newspaper: for each story, there will be a headline, some text, and possibly some images ,The structure is very similar when a news story is viewed
online (although it may also feature audio or video). This is illustrated on the right with a copy of a newspaper alongside the corresponding article on its website.

##### HTML Describes the Structure of Pages : The HTML code is made up of characters that live inside angled brackets these are called HTML elements. Elements are usually
##### made up of two tags: an opening tag and a closing tag. (The closing tag has an extra forward slash in it.) Each HTML element tells the browser something about the information that sits between its opening and closing tags.

#### HTML Uses Elements to Describe the Structure of Pages and Tags act like containers, They tell you something about the information that lies between their opening and closing tags.

#### Attributes Tell Us More About Elements :Attributes provide additional information about the contents of an element. 
#### They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.

### Body, Head & Title:
##### <body> You met the <body> element in the first example we created. Everything inside this element is shown inside the main browser window.
##### <head> Before the <body> element you will often see a <head> element. This contains information about the page (rather than information that is shown within
##### the main part of the browser window that is highlighted in blue on the opposite page). You will usually find a <title> element inside the <head> element.
##### <title> The contents of the <title> element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit
##### or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).


**let me guide you throght steps to Creating a Web Page  on a PC:
To create your first web page on a PC, start up Notepad. You can find this by going to:
Start
All Programs (or Programs)
Accessories
Notepad
You might also like to download a free editor called Notepad++ from notepad-plus-plus.org.
Go to the File menu and select Save as... You will need to save the file somewhere you can remember.
Save this file as test.html




**Looking at How Other sites are Built you can do that buy opening the page you want to look at and Once you have opened this
page, you can look for the View menu in your browser, and select  the option that says Source or View source.


*In end of theis chapter Here is some of the thinge you know about now: 
* HTML pages are text documents.
* HTML uses tags (characters that sit inside angled brackets) to give the information they surround special meaning.
* Tags are often referred to as elements.
* Tags usually come in pairs. The opening tag denotes the start of a piece of content; the closing tag denotes the end.
* Opening tags can carry attributes, which tell us more about the content of that element.
* Attributes require a name and a value.
* To learn HTML you need to know what tags are available for you to use, what they do, and where they can go.


### The Evolution of HTML:
**- HTML 4 Released 1997
**- XHTML 1.0 Released 2000
**- HTML5 Released 2000

** DOCTYPEs:Because there have beenseveral versions of HTML, each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML
the page is using (althoughbrowsers usually display the page even if it is not included). We will therefore be including one in each example for the rest of the book.

**There is a way to wright  Comments in HTML :  <!-- comment goes here -->

**ID Attribute: 
Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page.
The id attribute is known as a global attribute because it can be used on any element.

**Class Attribute:
Its value should describe the class it belongs to. In the example on the left, key paragraphs have a class attribute whose value is
important. The class attribute on any element can share the same value. So, in this example, the value of important could be used on headings and links, too.

**Block Elements: 
Some elements will always appear to start on a new line in the browser window. These are known as block level elements.

**Inline Elements: Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements.

**Grouping Text &Elements In a Block:
**<div> * : element allows you to group a set of elements together in one block-level box.
**<span>* : The <span> element acts like
*an inline equivalent of the <div> element. It is used to either:
1. Contain a section of text where there is no other suitable element to differentiate it from its surrounding text
2. Contain a number of inline elements.

* The most common reason why people use <span> elements is so that they can control the appearance of the content of these elements using CSS *

*<iframe> *:  An iframe is like a little window  that has been cut into your page — and in that window you can see another page. The term iframe is an abbreviation of inline frame.

-src : The src attribute specifies the URL of the page to show in the frame.
-height:  The height attribute specifies the height of the iframe in pixels.
-width:  The width attribute specifies the width of the iframe in pixels.

-scrolling: The scrolling attribute will not be supported in HTML5. In HTML 4 and XHTML, it indicates whether the iframe should
have scrollbars or not. This is important if the page inside the iframe is larger than the space you have allowed for it (using the height and width attributes). 
Scrollbars allow the user to move around the frame to see more content. It can take one of three values: yes (to show scrollbars), no (to hide scrollbars) and auto (to show them only if needed).

-frameborder: The frameborder attribute will not be supported in HTML5. In HTML 4 and XHTML, it indicates whether the frame should have
a border or not. A value of 0 indicates that no border should be shown. A value of 1 indicates that a border should be shown.

-seamless :In HTML5, a new attribute called seamless can be applied to an iframe where scrollbars are not desired. The seamlessattribute (like some other new
HTML5 attributes) does not need a value, but you will often see authors give it a value of seamless. Older browsers do not support the seamless attribute.

# Information About Your Pages:
* <meta> The <meta> element lives inside the <head> element and contains information about that web page.
* description This contains a description of the page. This description is commonly used by search engines to understand what the page is about and should be a maximum of 155 characters.
* keywords This contains a list of commaseparated words that a user might search on to find the page. In practice, this no longer has any noticeable effect on how search engines index your site.
* robots This indicates whether search engines should add this page to their search results or not. A value of noindex can be used if this page should not be added.
A value of nofollow can be used if search engines should add this page in their results but not any pages that it links to.
* author This defines the author of the web page.
* pragma This prevents the browser from caching the page. (That is, storing it locally to save time downloading it on subsequent visits.)
* expires Because browsers often cache the content of a page, the expires option can be used to indicate when the page should expire (and no longer be cached). Note that the date must be specified in the format shown.

### Escape Characters:There are some characters that are used in and reserved by HTML code. (For example, the left and right angled brackets.)

**DOCTYPES tell browsers which version of HTML you are using. 
**You can add comments to your code between the <!-- and --> markers.
**The id and class attributes allow you to identify particular elements.
**The <div> and <span> elements allow you to group block-level and inline elements together.
** <iframes> cut windows into your web pages through which other pages can be displayed.
** The <meta> tag allows you to supply all kinds of information about your web page.
** Escape characters are used to include special characters in your pages such as <, >, 





**HTML5 Layout:
HTML5 is introducing a new set of elements that help define the structure of a page.

**Traditional HTML Layouts :
For a long time, web page authors used <div> elements to grouptogether related elements on the page (such as the elements that form a header, an article, footer or sidebar). 
**Authors used class or id attributes to indicate the role of the <div> element in the structure of the page.

**New Html 5 Layout Elements:
HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not stopped many web page authors using them already.

**Headers & Footers <header> <footer> :
**The <header> and <footer> elements can be used for:
**The main header or footer that appears at the top or bottom of every page on the site.
**A header or footer for an individual <article> or <section> within the page

- Navigation <nav> : The <nav> element is used to contain the major navigational blocks on the site such as the primary site navigation.
- Articles <article> : The <article> element acts as a container for any section of a page that could stand alone and potentially be syndicated.
- Asides <aside> :  The <aside> element has two purposes, depending on whether it is inside an <article> element or not.
- Sections <section> : The <section> element groups related content together, and typically each section would have its own heading.
- Heading Groups <hgroup> : The purpose of the <hgroup> element is to group together a set of one or more <h1> through <h6> elements so that they are treated as one single heading.
- Figures <figure> <figcaption> :used when the content simply references the element (and not for something that is absolutely integral to the flow of a page).
- Sectioning El ements <div> : the <div> element will remain an important way to group together related elements, because you should not be using these new elements that you have just met for purposes other than those explicitly stated.
- Linking Around Block-Level El ements : HTML5 allows web page authors to place an <a> element around a block level element that contains child elements.  This allows you to turn an entire block into a link. 
This is not a new element in HTML5, but it was not seen as a correct usage of the <a> element in earlier versions of HTML.


#### The new HTML5 elements indicate the purpose of different parts of a web page and help to describeits structure.
#### The new elements provide clearer code (compared with using multiple <div> elements).
#### Older browsers that do not understand HTML5 elements need to be told which elements are block-level elements.
#### To make HTML5 elements work in Internet Explorer 8 (and older versions of IE), extra JavaScript is needed, which is available free from Google.




**Who is the Site For? *
**Every website should be designed for the target audience—not just for yourself or the**
**site owner. It is therefore very important to understand who your target audience is.**

**Every Websitew must have a Target Audience: individuals*
**What is the age range of your target audience?**
**Will your site appeal to more women or men? What is the mix?**
**Which country do your visitors live in?**
**Do they live in urban or rural areas?**
**What is the average income of visitors?**
**What level of education do they have?**
**What is their marital or family status?**
**What is their occupation?**
**How many hours do they work per week?**
**How often do they use the web?**
**What kind of device do they use to access the web?**

**Target Audience: Companies*
**What is the size of the company or relevant department?**
**What is the position of people in the company who visit your site?**
**Will visitors be using the site for themselves or for someone else?**
**How large is the budget they control?**

## Why People Visit YOUR Website :
## Now that you know who your visitors are, you need to consider why they are coming. While some people will simply chance across your website, most will visit for a specific reason.

#### What Your Visitors are Trying to Achieve :
#### It is unlikely that you will be able to list every reason why someone visits your site but you are looking for key tasks and motivations. This information can help guide your site designs.

##What Information Your Visitors Need :
You know who is coming to your site and why they are coming, so now you need to work out what information they need in order to achieve their goals quickly and effectively.

#### How Of ten People Will Visit Your Site :
#### Some sites benefit from being updated more frequently than others. Some information (such as news) may be constantly changing, while other content remains relatively static.

#### Site Maps :
####  Now that you know what needs to appear on your site, you can start to organize the information into sections or pages.

#### WireFrames :
#### A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.

#### Getting your message across using design :
#### The primary aim of any kind of visual design is to communicate. Organizing and prioritizing information on a page helps users understand its importance and what order to read it in.

#### Visual hierarchy :
#### Visual hierarchy refers to the order in which your eyes perceive what they see. It is created by adding visual contrast between the items being displayed. Items with higher contrast are recognized and processed first.

#### grouping and Similarity :
#### When making sense of a design, we tend to organize visual elements into groups. Grouping related pieces of information together can make a design easier to comprehend.
#### Here are some ways this can be achieved:
**Proximity
*Closure
*Continuance
*White Space
*color
*Borders

### We naturally observe similarities in design, and things that are similar are perceived to be more related than things that are dissimilar. 
### Repetitionof similar color, size, orientation, texture, font, or shape, suggests that matching elements have similar importance or meaning.

*Designing Navigation :
Site navigation not only helps people find where they want to go, but also helps them understand what your site is about and how it is organized.
 Good navigation tends to follow these principles: 
1-Concise: the navigation should be quick and easy to read.
2-Clear:Users should be able to predict the kind of information that they will find on the page before clicking on the link.
3-Selective:The primary navigation should only reflect the sections or content of the site.
4-Context :Good navigation provides context. It lets the user know where they are in the website at that moment.
5-Interactive :Each link should be big enough to click on and the appearance of the link should change when the user hovers over each item or clicks on it.
6-Consistent :The more pages a site contains, the larger the number of navigation items there will be. Although secondary navigation will change from page to page, it is best to keep the primary navigation exactly the same.

### *Summry:*
**It's important to understand w XX ho your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
**Site maps allow you to plan the structure of a site.
**Wireframes allow you to organize the information that will need to go on each page.
**Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
**You can differentiate between pieces of information using size, color, and style.
**You can use grouping and similarity to help simplify the information you present.






# How JavaScript Makes Web Pager Moreintractive:
#### - ACCESS CONTENT You can use JavaScript to select any element, attribute, or text from an HTML page. For example:
##### • Select the text inside all of the <hl> elements on a page
#####• Select any elements that have a c1ass attribute with a value of note
##### • Find out what was entered into a text input whose id attribute has a value of email
#### - MODIFY CONTENT : You can use JavaScript to add elements, attributes, and text to the page, or remove them. For example:
• **Add a paragraph of text after the first <hl> element
• **Change the value of c 1 ass attributes to trigger new CSS rules for those elements
• **Change the size or position of an <i mg> element 
- PROGRAM RULES:
 You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page. For example:
• A gallery script could check which image a user clicked on and display a larger version of that image.
• A mortgage calculator could collect values from a form, perform calculation, and display repayments.
• An animation could check the dimensions of the browser window and move an image to the bottom of the viewable area (also known as the viewport).
- REACT TO EVENTS :
You can specify that a script should run when a specific event has occurred. For example, it could be run when:
• A button is pressed
• A link is clicked (or tapped) on
• A cursor hovers over an element
• Information is added to a form
• An interval of time has passed
• A web page has finished loading

### Being able to change the content of an HTML page while it is loaded in the browser is very powerful. The examples below rely on the ability to:
- Access the content of the page
- Modify the content of the page
- Program rules or instructions the browser can follow
- React to events triggered by the user or browser

### In order to teach you JavaScript, this book is divided into two sections:
1-CORE CONCEPTS The first nine chapters introduce you to the basics of programming and the JavaScript language. Along
the way you will learn how it is used to create more engaging, interactive, and usable websites.
2-PRACTICAL A PPLICATIONS By this point you will already have seen many examples of how JavaScript is used on popular
websites. This section brings together all of the techniques you have learned so far, to give you practical demonstrations of how JavaScript is used
by professional developers. Not only will you see a selection of in-depth examples, you will also learn more about the process of designing and writing
scripts from scratch.





#### Before you learn how to read and write the JavaScript language itself, you need to become familiar with some key
#### concepts in computer programming. They will be covered in three sections:

A- What is a script and how do I  create one?
B- How do computers fit in with the world around them?
C- How do I write a script for a web page?


**Once you have learned the basics you will be able to understand how the JavaScript
**language can be used to tell browsers what you want them to do.*

### what is a script and how do I  create one : A script  is a series of instructions that a computer can follow to achieve a goal.
 #### WRITING A SCRIPT To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.


#### Start with the big picture of what you want to achieve, and break that down into smaller steps :
1- DEFINE THE GOAL First, you need to define the task you want to achieve. You can think of this as a puzzle for the computer to solve.
2- DESIGN THE SCRIPT To design a script you split the goal out into a series of tasks that are going to be involved in solving this puzzle. This can be represented using a flowchart.
3- CODE EACH STEP Each of the steps needs to be written in a programming language that the compu ter understands. In our case, this is JavaScript.


#### You need to learn to "think" like a computer because they solve tasks in different ways than you or I might approach them.

### A- What is a script and how do I  create one? 
 **A script is a series of instructions that the computer can follow in order to achieve a goal.**
 **Each time the script runs, it might only use a subset of all the instructions.**
 **Computers approach tasks in a different way than humans, so your instructions must let the computer solve the task prggrammatically.**
 **To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help).**

### B- How do computers fit in with the world around them?
COMPUTERS CREATE MODELS OF THE WORLD USING DATA :
- OBJECTS (THINGS) each  one can have its own :  -Properties  -Events -Methods
- PROPERTIES (CHARACTERISTICS) :Each property has a name and a value, and each of these name/value pairs tells you something about each individual instance of the object.

### METHODS:
**WHAT IS A METHOD : Methods typically represent how people (or other things) interact with an object in the real world.**
** WHAT DOES A METHOD DO? The code for a method can contain lots of instructions that together represent one task.**

### PUTTING IT ALL TOGETHER:
Computers use data to create models of things in the real world. The events, methods, and properties of an object all relate to each other.

### WEB BROWSERS ARE PROGRAMS BUILT USING OBJECTS.
Web browsers create similar models of the web page they are showing and of the browser window that the page is being shown in. 
WINDOW OBJECT
- On the right-hand page you can see a model of a computer with a browser open on the screen.
DOCUMENT OBJECT
- The current web page loaded into each window is modelled using a document object.

THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE:
- Using the document object, you can access and change what content users see on the page and respond to how they interact with it.

#### Like other objects that represent real-world things, the document object has:
** PROPERTIES Properties describe characteristics of the current web page (such as the t itle of the page).**
** METHODS Methods perform tasks associated with the document currently loaded in the browser (such as getting information from a specified element or adding new content).**
**EVENTS You can respond to events, such as a user clicking or tapping on an element. **
#### HOW A BROWSER SEES A WEB PAGE::
In order to understand how you can change the content of an HTML page using JavaScript, you need to know how a browser interprets the HTML code and applies styling to it:
1- RECEIVE A PAGE AS HTML CODE Each page on a website can be seen as a separate document .
So, the web consists of many sites, each made up of one or more documents.
2- CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY The model shown on the right
hand page is a representation of one very basic page. Its structure is reminiscent of a family tree. At the top of the
model is a document object, which represents the whole document.
3- USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN If there is no CSS, the rendering
engine will apply default styles to HTML elements. However, the HTML code for this example
links to a CSS style sheet, so the browser requests that file and displays the page accordingly.

### B- How do computers fit in with the world around them:
1-computer creates models of the world using data 
To make web pages interactive you need to write code that uses the browsers model of the web page 
2-the models use objects to represents physical things  objects cans have properties that tell us about the object 
3-programmers can weite code to say when this event occurs and run that code 
4-web browsers use HTML markup to create a model of the web page and each element creates its own node which is a kind of object



### C- How do I write a script for a web page:

HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER?
- CONTENT LAYER . html files This is where the content of the page lives. The HTML gives the page structure and adds semantics.
- PRESENTATION LAYER .css files The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).
- BEHAVIOR LAYER .js files This is where we can change how the page behaves, adding interact ivity. We will aim to keep as much of our JavaScript as possible in separate files.

#### PROGRESSIVE ENHANCEMENT:
1- HTML ONLY Starting with the HTML layer allows you to focus on the most important thing about your site: its content.
2- HTML+CSS Adding the CSS rules in a separate file keeps rules regarding how the page looks away from the content itself.
3- HTML+CSS+JAVASCRIPT The JavaScript is added last and enhances the usability of the page or the experience of interacting with the site.


##### CREATING A BASIC JAVASCRIPT:
##### JavaScript is written in plain text, just like HTML and CSS, so you do not need any new tools to write a script.


#### LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE :
When you want to use JavaScript with a web page, you use the HTML <script> element to tell the browser it is coming across a script. Its s re attribute tells people where the JavaScript file is stored.




Table of Content  | source
------------ | -------------
Introduction  | Duckett HTML book 
Chapter 1 | Duckett HTML book 
Chapter 8 | Duckett HTML book 
Chapter 17 | Duckett HTML book 
Chapter 18 | Duckett HTML book 
Introduction |  Duckett JS book 
Chapter 1 |  Duckett JS book 


 
