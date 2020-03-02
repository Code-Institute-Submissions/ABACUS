# ABIKAS
User-Centric-Frontend-Development-Milestone-Project

ABIKAS
Acquired Brain Injury Katz Adjustment Scale

I have been asked to create a web page which includes and allow users to complete an online form called the ABIKAS.  

To suite the milestone project's requirements I will be making adjustments to the code I use to keep the focus on the project rather than incorporating the 
functions that use languages other than html and css.


LAYOUT


Content


index.html

As this service will be offered to members only, the index page will be used for logging in so will include a log in form as well as a hyperlink to go to a 
registration page.

With this being a html & css milestone project, there will be no JavaScript or PHP code included for completing the log in.  Instead I will be using a temporary 
<a> tag to send the user to the home page (home.html) with clicking on the log in button.

<head>

I have used the standard meta tags; as well as incorporated the <link> and <script> tags that I found when looking for a template with creating the log in form from 
https://bootsnipp.com/snippets/z8MPd.  I have also added a <link> to my style.css and the necessary jquery <script> meta tags for each page.

I have also included a cdn for hover.css enabling me to add hover effects to certain elements within the project.

I have not added a font setting as I am happy with the setting of the font as it is using the bootstrap 4 cdn.

<body>

I have used the .container-fluid class from the bootstrap cdn to utilize 100% width of the viewport across all device sizes.  With incorporating this into the 
<body> tag I can be confident that ALL of my page's width will "fit to size".

<header>

I have created a logo using a standard paint programme and used this as the heading for this page.

I have used a <h2> tag for the subheading, and not felt a need to change the font from that which is the standard.

I incorporated both the heading and subheading in one <div> tag element, separating my heading and subheading vertically; and the .text-center class from the 
bootstrap cdn to show these elements in the center of the page.

As you will see I have also used the .card-header class from the bootstrap cdn for the <header> tag as I wanted the background color to match the background colour 
of the log in form's header.

<section>
 
This is the form to log.  Using <div> elements from a template on http:// bootsnipp.com the form is separated into a username and password <input> element; with 
a <button> tag to log in and the option to register using an <a> tag.

I have centred and justified the form using the .justify-content-center the from bootstrap classes.

Inspired form the template from http:// bootsnipp.com; the <div> elements divide the .card-header from the .card-body.; and the .form-group and .form-control
classes to create a front end design for a future from.  As you will see the heading of the log in <label> & <input> tags that make up the form parts are titled
using a <h4> tag.  A <button> tag is used to log in (however this has been set as an <a> tag to send the user straight to the home.html page; and I have 
put a <label> tag in place with the type="checkbox" labelled 'Remember Me'.  This for the user to eventually have the ability to save their log in details when 
the site incorporates the necessary coding.  Next to the <button> tag I have included an <a> tag with a hyperlink for the user to go to the registration page.

<footer>

I've created a footer inspired from a gallery template from http:// bootsnip.com. I have added other companys 'logos as an <img>, this is to draw the user's 
attention to the companies associated to the website's service creator; and with adding the url of the companies' site as a href this allows the user to use the 
images as links to the companies' websites.  Above the links I have used a <h3> heading to notify the user that these images are associated with the service 
creator.  

I have used the same bootstrap classes to separate and cantered my images and text.  I have added a hover class for effect, and to show that the images are 
links.


register.html

With using associated companies' links within the <footer> and a clear header of which both identifies the site within the index.html page; I have used the 
same <header> and <footer> throughout the rest of my project to maintain access to the links and to avoid any confusion that the user may have with navigating 
the site.

<section>

This is the form to register. The user can navigate to this page from the log in page using the hyper link within the <a> tag stating: Register Here.

I have used the same method of incorporating the .justify-content-center the from bootstrap classes to center and justify the form.

I have tried to keep the same theme as the log in form for the registration form, again, using a template from http:// bootsnipp.com; the <div> elements 
divide the .card-header from the .card-body.; and the .form-group and .form-control classes to create a front end design for a future from. Again using the 
same method as in the log in form, however running the form's elements heading to the side of the <label> & <input> tags (as was on the template).  I did 
this to create a different experience for the user as to save any confusion and in slightly adjusting the layout to avoid repetitiveness and maintaining the
users attention.


home.html

This is a mock up of what will be the user's portal. 

<nav>

Using a bootstrap template from http:// bootsnipp.com; I have constructed a basic navbar and edited it to suit the site pages' layout. As you will see the 
navbar consists of a main heading (ABIKAS) which it's href is set to home.html and 2 sub tabs- one being a mock to redirect the user to the ABIKAS 'form' 
(which I will add at a later date) and one to take the user to a 'contact' page. <a> (href - contact.html).  I will add more sub tabs in the future to suit
the users' needs of which some will incorporate a dropdown function broaden their individual directories.  This navbar will be used throughout the users' 
'portal'.

I have also added hover classes for effect; showing the user that the tabs are applicable.

<section>

Here I have set 3 <div> elements to show the use of the rule of 3 within my project.  Each <div> has a heading <h3> with a paragraph <p> below each heading. 
As the headings show this page is intended to give an overview of the uses of the ABIKAS form.  I have used the Lorem Ipsum text in the <p> element.  This is 
so to not divulge any sensitive information at this time.  (This information will be added at a later date.) 


contact.html

<section>

This is where the ABIKAS users' contact options are. Here the user has the ABIKAS teams' contact information and a contact form of which will direct the 
users' issue or query using a drop box, allowing the user to input their details and a short message.  I used a template from http:// bootsnipp.com as this 
incorporates bootstrap classes and used the rule of 3 which I want to use within my project.  The template was set to bootstrap 3, however through trail and 
error I found that using the bootstrap 4 cdn better suited this page to the project.  Some classes may not be relative.  I have also incorporated the <link> 
for the jquery template within the <head> on this html.


assets/
------------
css/
style.css

/* INDEX */


/* REGISTER */


/* HOME */

I have used css to design the positioning of the <section> element and its child elements on the home.html page to make the page more attractive to the 
user.  This includes styling the headings and the positioning of the headings and paragraphs.


/* CONTACT */

I have used the css to give space between the contact form and the <footer>; as well as emphasizing some of the font on the contact.html page.

------------
images/
abikas.jpg
ntracslogo.jpg
trulogo.jpg

-------------
documents/
form.docx