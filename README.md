HTML (Hyper Text Markup Language)
-----------------------------------
### About HTML
* HTML stands for Hyper Text Markup Language.
* HTML is the standard markup language for creating Static Web Pages.
* HTML describes the structure of Web Page.
* HTML elements label pieces of cintent such as "this is a heading", "this is a paragraph", "this is a link", etc.
* An HTML element is defined by a start tag, some content, and an end tag: `<tagname>Content goes here...</tagname>`

### Basic Tags
* The <!DOCTYPE html> declaration defines that this document is an HTML5 document.
* The <html> element is the root element of an HTML page.
* The <head> element contains contains meta information about the HTML page.
* The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab).
* The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
* The <h1> element defines a large heading.
* The <p> element defines a paragraph. 

### HTML Paragraphs
* <p> tag: The <p> tag in HTML defines a pargraph. These have both opening and closing tag. So anything mentioned within <p> and </p> is treated as a paragraph
* A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.
* `<p> Content </p>`

### HTML headings
* HTML headings are titles or subtitles that you want to display on a webpage.
* HTML headings are defined with the <h1> to <h6> tags.
* <h1> defines the most important heading. 
* <h6> defines the least important heading.

```html
<h1> Heading 1 </h1>
<h2> Heading 2 </h2>
<h3> Heading 3 </h3>
<h4> Heading 4 </h4>
<h5> Heading 5 </h5>
<h6> Heading 6 </h6>
```
### Syntax
* An HTML file must have some essential tags so that web browser can differentiate between a simple text and HTML text. You can use as many tags you want as per your code requirement.
* All HTML tags must enclosed within < > these brackets.
* Every tag in HTML perform different tasks.
* If you have used an open tag <tag>, then you must use a close tag </tag> (except some tags)
* `<tag> content </tag>`

### Tags
* <br> Tag `br` stands for break line, it breaks the line of the code.
* <pre> Tag for pre formatting the text.
* <code> Tag for coding.
* <i> Tag for italic text formatting.
* <mark> Tag to mark important texts.
* <u> Tag to underline the text.
* <sup> Tag superscript.
* <sub> Tag subscript.
* <small> Tag for showing text as small.
* <big> Tag for showing text as big.
* <del> Tag to delete(cross line) the text.

### Background in html
* By default, webpage background is white in color. HTML provides following two good ways to decorate web page background.
    * HTML Background with Colors.
        * The `bgcolor` attribute is used to control the background of an HTML element, specifically page body and table backgrounds.
        * Ex: <body bgcolor = "red">
              <body bgcolor = "#f1f1f1">
              <body bgcolor = "rgb(0,0,120)">  
    * HTML Background with Images.
        * <tagname background = "Image URL"...>
          <table background ="/images/html.gif" width = "100%" height = "100">
        * Text colors
        * Ex: <body text="red">
              Hello everyone
              </body>  

        * HTML img tag is used to display image on the webpage. HTML img tag is an empty tag that contains attributes only, closing tags are not used in HTML image element.
        * The src and alt are important attributes of HTML img tag.
            * src: It is a necessary attribute that describes the source or path of the image.
            * alt: The alt attribute defines an alternate text for the image, if it can't be displayed.
            * width: It is an attribute which is used to specify the width to display the image.
            * height: It is used to specify the height to display the image.
        * Syntax: <img src="" alt=""/>

### HTML - Tables
* The HTML tables allow web authors to arrange data like text, images, links, other tables, etc. into rows and columns of cells.
* The HTML tables are created using the <table> tag in which the <tr> tag is used to create table rows and <td> tag is used to create data cells. The elements under <td> are regular and left aligned by default.

### HTML - Lists
* HTML Lists are used to specify lists of information. All lists may contain one or more list elements. There are three different types of HTML of HTML list
    * Ordered List or Numbered List (ol)
        * In the ordered HTML lists, all the list items are marked with numbers by default. It is known as numbered list also. The ordered list starts with <ol> tag and the list items start with <li> tag. 
    * Unordered List or Bulleted List (ul)
        * In HTML Unordered list, all the list items are marked with bullets. It is also known as bulleted list also. The Unordered list starts with <ul> tag and list items start with the <li> tag. 
    * Description List or Definittion List (dl)       

### Marquee tag in html
* The Marquee HTML tag is a non-standard HTML element which is used to scroll a image or text horizontally or vertically.
* In simple words, you can say that it scrolls the image or text up, down, left or right automatically.


### HTML - Links
* A web page can contain various links that take you directly to other pages and even specific parts of a given page. These links are known as hyperlinks.
* Hyperlinks allow visitors to navigate between Web sites by clicking on words, phrases, and images. Thus you can create hyperlinks using text or images available on a webpage.
* A link is specified using HTML tag <a>. This tag is called anchor tag and anything between the opening <a> tag and the closing </a> tag becomes part of the link and a user can click that part to reach to the linked document. Following is the simple syntax to use <a> tag.
* `<a> href = "Document URL" ...attributes-list>Link Text</a>`


### HTML - Audio and Video
* The HTML <audio> and <video> tags make it simple to add media to a website. You need to set src attribute to identify the media.

### HTML - Forms
* HTML Forms are required. When you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name. Email address, credit card, etc.
* There are various form elements available like text fields. Textarca fields, drop-down menus, radio buttons, cheekboxes, etc.
* The HTML, <form> tag is used to create an HTML form and it has following syntax
```html
<form action - "Script URL" method - "GET POST">
    form elements like input, textarea etc.
</form>    
```        


