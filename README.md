# Web_Tech--PentagonSpace
Web Tech Learnings at pentagon space Pvt Ltd.

____________________________________________________________________________________

3 Tier Architecture :

* Frontend - whatever the user sees in the user interface (UI) is called frontend.

* Middleware / Server - Middleware is a place where a software is installed.

* Backend - Backend stores the information about the browser.

How the web works?

* User will open the browser and enter some data and tries to connect to the server, but the server will not understand the human readable format so we have DNS. DNS stands for Domain Name System which is used to convert human readable format to server understandable format that is IP Address. IP Address stands for Internet Protocol Address based on the IP Address server will give the output.

* Browser - Browser is the software application which helps to load the webpages, websites and web server.

_________________________________________________________________________________

HTML - 

* HTML - HTML stands for Hypertext Markup Language.

* It was developed by Tim Bernesly in 1995.

* It is one of the standard markup language.

* The latest version of HTML is - HTML 5

* It consists of series of Elements.

* Tells the browser what content should be displayed on UI.

* Standard markup Language has alternatives - XML(Extensible Markup Language), XHTML(Extensible Hypertext Markup Language),JSP(Java Servlet Page),JSX(Javascript XML).
  
Started with basic structure of HTML.
_______________________________________________________________________________

    <!DOCTYPE html> ----DOCUMENT type version of HTML-5

    <html> ---Root Element
  
        <head> ---meta information
    
            <meta>  ---browser information
     
            <title>DOCUMENT</title> ---tab data
     
        </head>
  
       <body>  ---All the elements are present
    
             HELLO WORLD HTML!
    
      </body>
  
    </html>

--------------------------------------------------------------------------

Tags:-

They are of two types -

1. Paired - They have both opening and closing tags.
   
   - Bold tag
     
          <b>
     
   - Strong tag
     
          <strong>
     
   - Italic tag
     
           <i>
     
   - Emphasis tag
     
           <em>
     
   - mark tag
     
           <mark>
     
   - Subscript tag
     
           <sub>
   
   - Superscript tag
     
           <sup>
   
3. Unpaired - They are self closing tags.
   
   - Paragraph tag
     
              <p>
     
   - Pre formatted tag
     
              <pre>
   
   - Image tag
     
              <img>


HTML Elements:

* HTML elements are the content enclosed with opening tag and closing tag.
* There are of two types -
    1. Block Elements
    2. Inline Elements

 1. Block Elements -

  * Elements which will consume the entire width of the browser is called Block level elements.
  * Ex: - <h>, <div>

 2. Inline Elements -

  * Elements which will consume the content width of the browser is called Inline level elements.
  * Ex: - <p>, <span>, formatting tags.

* Attributes:-

* Are additional info about the tag.
* All tags can have attributes.
* Each and every tag can have multiple Attributes.
* Thea re always used in openning tag.
* Ex: src="" in image tag, height=100px

1. Anchor Tag :

   * Anchor tag refers to link a webpage.
   * Syntax:

         <a href="" target="_blank"></a>

        _blank : targets the webpage into a new tab except all other targets such as - parent, self,top.
2. Image tag :

   * Syntax:

         <img src="path" alt="image1" height="200px" width="200px"/>
 * Path are of two types -
     * Absolute path - where we copy link online
     * Relative path - where we download and copy(downloaded image) path.

Tables :

 * Table is a collection of rows and columns.
 * Rows : Row is a horizontal representation of table.(tr)
 * Column : column is a vertical representation of table.(td)
 * Cell : Cell is the Intersection of rows and columns in a table.
 *  Syntax :
    2*1
       <table>
         <tr>
           <td>1</td>
         </tr>
         <tr>
           <td>2</td>
         </tr>
       </table>
