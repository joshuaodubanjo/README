# What is HTML ?
###### HTML(HyperText Markup Language) is the most basic building block of all web pages. It provides structure to the content appearing on a website, such as images, text, or videos by creating a basic skeleton. HTML is still very useful today, the reason being no matter the framework or language we use to develop the web page, the output would be rendered in HTML.

# What is HTML Cheat Sheet ?
###### Web developers starting sometimes need a simple, quick reference list of basic HTML tags, codes, and attributes, that’s when HTML Cheat Sheet comes into the picture. The whole purpose of the Cheat Sheet is to provide you with some quick accurate ready-to-use code snippets and necessary HTML tags and attributes to help you with your webpage.

## Table of Content
- [Heading Tags](#Heading-Tags)
- [Container Tags](#Container-Tags)
- [Document Section](#Document-Section)
- [Container Tags](#Sectioning-Tags)

## Main root
###### The <html> element represents the root (top-level element) of an HTML document also called the document element as it defines the whole HTML document. It has a start tag <html> and an end tag </html>All other elements must be descendants of this element.

`<html>...</html>`

 ## Boilerplate
  ```html
  <!DOCTYPE html>
  <html lang="en">
    <head>
	   <!-- Description of the document -->
	  <meta charset="UTF-8" />
	  <title>
		  <!-- title goes here -->
		  Anchorsoft Academy
	  </title>
  </head>
  <body>
    <!-- your content goes here -->
    Welcome to Anchorsoft Academy
  </body>
</html>
```
## Sectioning Root 
## Body
###### The HTML <body> Element represents the content of an HTML document. There can be only one <body> element in a document

### Heading Tags
###### There are six headings available in HTML.
1. H1 Tag: This is the largest heading among all.
`<h1>Anchorsoft Academy</h1>`

2. H2 Tag: This is the second largest heading among all.
`<h2>Anchorsoft Academy</h2>`

3. H3 tag: This is the third largest heading among all.	
`<h3>Anchorsoft Academy`

4. H4 Tag: This is the fourth largest heading among all.
`<h4>Anchorsoft Academy</h4>`

5. H5 Tag: This is the fifth largest heading among all.
`<h5>Anchorsoft Academy</h5>`

6. H6 Tag: This is the smallest among all.
`<h6>Anchorsoft Academy</h6>`
#### Example
```html
<!DOCTYPE html>
  <html>
    <head>
      <title>Heading Tags</title>
    </head>
    <body>
      <h1>Anchorsoft Academy</h1>
      <h2>Anchorsoft Academy</h2>
      <h3>Anchorsoft Academy</h3>
      <h4>Anchorsoft Academy</h4>
      <h5>Anchorsoft Academy</h5>
      <h6>Anchorsoft Academy</h6>
    </body>
  </html>
```

### Container Tags
###### The container tags are tags that have some data such as text, the image between their opening and closing tags. There are several container tags in HTML.
1. Div tag
  :The 'div' tag is a block element. It defines a division or a section in HTML document. Any sort of content can be put inside the 'div' tag.
  `<div>...</div>`
2. Span tag
  :The 'span' tag is an inline element. It is used to mark up a part of a text, or a part of a document.
  `<span>...</span>`
3. P tag
  :The 'p' tag represents a paragraph. HTML paragraphs can be any structural grouping of related content, such as images or form fields.
  `<p>...</p>`
4. Pre tag
  :The 'pre' tag represents pre-formatted text which is to be presented exactly as written in the HTML file. . It preserves the text spaces, line breaks, tabs, and other formatting characters which are ignored by web browsers.
  `<pre>...</pre>`
5. Code tag 
  :The 'code' tag is used to represent source codes. It is mainly used to display the code snippet into the web browser.	
  `<code>...</code>`
#### Example
```html
  <!DOCTYPE html>
  <html>
    <head>
      <!-- Title tag -->
      <title> Anchorsoft Academy </title>
      <!-- meta tag starts -->
      <meta name="keywords"
          content="Meta Tags, Metadata" />
      <meta name="description"
          content="Anchorsoft Academy is a tech school ." />
      <!-- meta tag ends -->
      <!-- html style tag starts -->
      <style type="text/css">
        body {
        background-color: powderblue;
        }
        h1 {
        color: black;
        font-family: arial;
        }
      </style>
      <!-- html style tag ends -->
    </head>
    <body>
    <p>
      Anchorsoft Academy is a
      <!-- span tag starts-->
      <span style="color:red;font-weight:bolder">
      Tech</span> school for
      <span style="background-color: lightgreen;">
        developers
      </span>
      <!-- span tag ends -->
      <!-- html pre tag starts here -->
      <pre>
        This
        is a pre tag.
      </pre>
    </p>
    <!-- html pre tag ends here -->
    <pre>
        <!--code Tag starts here -->
        code tag: Displays code snippets.
        <code>
        #include<stdio.h>
        int main() {
          printf("Hello Techies");
        }
        <!--code Tag starts here -->
        </code>
    </pre>
    <p>
      Click on the following link
      <!-- anchor tag starts -->
      <a href="https://www.anchorsoftacademy.com">
      Anchorsoft Academy
      </a>
      <!-- anchor tag ends -->
    </p>
    </body>
  </html>
```
  
## Document Section
###### This section involves tags which are used to describe the HTML document by giving an overview of what it includes.
1. Head tag
  :The `head` element is a container for metadata which is data about data. It is the first section in the code containing information about a web page’s properties and links to external related files.
  `<head>...</head>`
2. Link tag
  :The `link` tag is an empty element, it defines the relationship between the current document and an external resource. The `link` tag is most often used to link to external style sheets on your website.	
  `<link>`
3. Meta tag
  :The `meta` tag defines metadata about an HTML document. It is typically used to specify the character set, page description, keywords, author of the document, and viewport settings.	
  `</meta>`
4. Title tag
  :The `title` HTML element defines the document’s title that is shown in a browser’s title bar or a page’s tab.	
  `<title>...</title>`
5. Style tag
  :The `style` tag is used to define style information (CSS) for a document. It is used to specify how HTML elements should render in a browser.	
## Example
```html
<!DOCTYPE html>
<html>
  <!-- head tag starts here -->
  <head>
    <!-- title tag -->
    <title>Title goes here </title>

    <!-- link tag -->
    <link rel="stylesheet" type="text/css" href="style.css">

    <!-- meta tag starts -->
    <meta name="keywords" content="Meta Tags, Metadata" />
    <!-- meta tag ends -->

    <!-- style tag starts here -->
    <style>
      #first {
      font-family: Castellar;
      background-color: green;
      color: white;
      }
      .second {
      text-align: center;
      background-color: white;
      font-size: 30px;
      color: red;
      }
    </style>
    <!-- style tag ends here -->
  </head>
  <!-- head tag ends here -->
  <body>

  <p id="first">Hello Developers.</p>
  <p class="second">Welcome Anchorsoft Academy</p>
  </body>
</html>
```
## Sectioning Tags
###### Sectioning Content elements by default define ARIA landmark. These elements are mostly descendant of HTML body element.
1. Header tag: The `header` HTML5 element is used to give introductory content about the document. It may contain some heading elements and also a logo, a search form, an author name, and other elements.	
  `<header>...</header>`
2. Main tag: The `main` HTML element represents the main dominant content of the <body> of a document. The main content area consists of content that expands upon the central topic of a document, or the main functionality of an application.	
  `<main>...</main>`
3. Section tag: The HTML5 `section` element represents a standalone section. It is a structural HTML element used to group together related elements. Each `section` typically includes one or more heading elements and additional elements presenting related content.	
  `<section>...</section>`
4. Nav tag: The `nav` HTML element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents.
  `<nav>...</nav>`
5. Article tag: The HTML5 `article` element represents a self-contained composition in a document, page, application, or site, which is independently distributable or reusable.	
  `<article>...</article>`
6. Aside tag: The `aside` tag defines some content aside from the content it is placed in. Its content should be indirectly related to the surrounding content. The <aside> content is most often placed as a sidebar in a document.	
  `<aside>...</aside>`
7. Footer tag: The `footer` HTML element represents a footer for its sectioning root element. It typically contains information about the author of the section, copyright data or links to related documents.	
  `<footer>...</footer>`
8. Address tag: The HTML `address` element indicates that the enclosed HTML provides contact information for a person or people, or for an organization. It must not contain information other than contact information.	
  `<address>...</address>`
## Example
```html
  <!DOCTYPE html>
  <html>
    <body>
    <!-- main tag starts here -->
      <h3>HTML Header Tag</h3>
      <hr>
        <article>
          <!-- header tag starts -->
          <header>
            <h3>Anchorsoft Academy</h3>
            <h3> HTML nav Tag</h3>
            <!-- nav tag starts -->
            <nav>
              <a href="#">Home</a> |
              <a href="#">Interview</a> |
              <a href="#">Languages</a> |
              <a href="#">Data Structure</a> |
              <a href="#">Algorithm</a>
            </nav>
            <!-- nav tag ends -->
          </header>
          <!-- header tag ends -->
        </article>
        <main>
          <!-- HTML section tag is used here -->
          <section>
            <h1>Anchorsoft: Section 1</h1>
            <p>Content of section </p>
          </section>
          <!-- HTML section tag ends here -->
          <!-- aside tag starts here -->
            <aside>
              <h1>This is heading text in aside Tag</h1>
              <p>This is paragraph text in aside Tag</p>
            </aside>
            <!-- aside tag ends here -->
        </main>
        <!-- main tag ends here -->
      <!--HTML footer tag starts here-->
      <footer>
        <article>
          <!-- address tag starts from here -->
          <address>
            Organization Name: Anchorsoft Academy <br>
            Web Site:
            <a href="https://www.anchorsoftacademy.com/#sectioncontact">Anchorsoft Academy</a><br>
            visit us:<br>
            Anchorsoft Academy<br>
            A-118, Sector 136, Noida, <br>
            Uttar Pradesh (201305)
          </address>
          <!-- address tag ends here -->
        </article>
        <br>
        <a href="https://www.anchorsoftacademy.com/#about">About Us</a>|
        <a href="https://www.anchorsoftacademy.com/courses/">All Courses</a>|
        <p>@geeksforgeeks, Some rights reserved</p>
      </footer>
      <!-- footer tag ends here -->
    </body>
  </html>
```
