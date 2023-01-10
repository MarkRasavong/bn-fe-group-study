# HTML
1.	What do HTML and CSS stand for? 
* Hypertext Markup Language & Cascading Style Sheets 
2.	Would you rather use HTML or CSS, for putting paragraphs of text on a webpage?
* You would need to use HTML as a structure for putting paragraphs of text on a webpage. The webpage will identify that the opening and closing tags of ‘p’ are paragraphs. For positioning, styling, and aesthetics of paragraphs can be manipulated through CSS.
3.	Would you rather use HTML or CSS, to change the font and background colour of a button? 
* Obviously, you will need CSS because CSS only deals with style and not structure. 
4.	What is an HTML tag?
* A HTML tag is a structure normally with open ``<>`` and ``</>`` tags that identify the content what it is. Some HTML tags can be self-closing ``</> || <>``
5.	What are the three parts of a HTML element?
* It normally consists of an open and closing tag as mentioned above and the content you want to render in between. Also, can only contain just a closing tag.
* E.g.) ``<p>There is happy hour somewhere 🤷‍♂️</p>``
* E.g.) ``<SomeComponent  /> || <link src:`protocol://domain/path` > || <link src:`protocol://domain/path` />``
6.	What is the propose of doctype declaration?
* Not considered a HTML element, but helps the web browser identify the HTML 
7.	What is an HTML element?
* The root element of a document, any other elements will be a descendant of it.
8.	What is the purpose of the head element?
* For placing meta-information (web-crawling, SEO, etc..), title element, external links/libraries, and stylesheets.
9.	What is the purpose of the body element?
* Mostly all the elements that will be displayed to the user.
10.	How do you create a paragraph in HTML?
* ``<p>{your content here}</p>``
11.	How do you create a heading in HTML?
* ``<h1>{your heading here}</h2>``
* Limits from h1 - h6
12.	How many different levels of headings are there and what is the difference between theme?
* As mentioned above h1-h6
* The difference is the font-size for each. (largest = h1, smallest= h6)
13.	What element should you use to make a text bold and important?
* ``<strong>{content}</strong>``
* It was a ``b`` tag but due to accessibility, we now use `strong` tags.
14.	What element should you use to make text italicized to add emphasis to it?
* ``<em>{content}</em>``
* It was an I tag but due to accessibility, we now use ``em`` tags.
15.	What relationship does an element have with any nested elements within it?
* One element is the parent and the other is a children element.
16.	What relationship do two elements have if there ate in the same level of nesting?
* They are considered to be sibling elements. 
17.	How do you create HTML comments?
* ``<!-- {comments goes here} -->``
18. What HTML tag is used to create an unordered list?
* ``<ul> {li elements} </ul>``
19.	What HTML tag is used to create an ordered list?
* ``<ol> {li elements} </ol>``
20.	What HTML tag is used to create list items within both unordered and ordered lists
* ``<li> {content} </li>``
21.	What element is used to create a link?
* ``<a href={absolute, relative, or root-relative} > </a>``
22.	What is an attribute?
* It provides information/details about an HTML element.
23.	What attribute tells links where to go?
* ``href``
24.	What is the difference between an absolute and relative links?
* Absolute: can be `absolute`ly anything that has a protocol ``(http | https)``, domain ``(duckduckgo.com)``, ``path(?q=shibas)``
* Relative: anything within the local directory or domain. 
* E.g.) ``about.html || /secondPage || ../misc/gallery.html || /gallery.html``
25.	Which element is used to display an image?
* ``<img src={relative/absolute}  alt=’some necessary text here’ />``
26.	What two attributes do images always need to have?
* ``src`` = the source of the image either local or external and normally in an image format.
* ``alt`` = a text description of the image if the image fails to load or for accessibility for the visually impaired. 
27.	How do you access a parent directory in a file path?
* 	``../`` => goes one level up of the current file’s directory.
* Going to the root may require you to go more than one 
** E.g.) ``../../index.html``
28.	What are the four main image formats that you can use for images on the web?
* jpg: great for handling large colour palettes but doesn’t allow transparent pixels
* png: great for anything not a photo or animated. (qr, vector images, etc). Great for manipulating opacity or transparency of an image. File size is bigger than a jpg
* svg: vector-based graphics => can cale up or own to any dimension without loss of quality. 
* gif: animated images. Has a limited colour palette. Can be transparent but may contain some white pixels in the background 
