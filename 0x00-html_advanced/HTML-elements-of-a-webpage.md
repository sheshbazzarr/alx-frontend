# HTML - elements of a web page 
    Create the foundation of any HTML page.

HTML is about content. CSS is about the look and feel.

## Doctype
The <doctype> is necessary at the top of every HTML page to force the browser to render the page according to relevant specifications.
`<!-- Doctype HTML5 -->
    <!DOCTYPE html>
    <!-- Lowercase is also valid -->
    <!doctype html>`
## Resources
- [Doctype - MDN Web Docs Glossary: Definitions of Web-related terms | MDN](https://developer.mozilla.org/en-US/docs/Glossary/Doctype)

- [HEAD - A free guide to head elements](https://htmlhead.dev/)


## HTML TAG 
The <html> HTML tag tells the browser that the document is an HTML webpage. It is used as a container for all the HTML elements.

Warning!

The doctype is the only element living outside the html tag.
`<html lang="fr" dir="ltr">`

## Language and reading direction
- [Building RTL-Aware Web Apps & Websites: Part 1 - Mozilla Hacks - the Web developer blog](https://hacks.mozilla.org/2015/09/building-rtl-aware-web-apps-and-websites-part-1/?ref=frontendchecklist)



## Head Tag  

The `<head>` element contains all the metadata related to your page. All the elements placed inside the `<head>` are not visible in the browser window.  

Many types of metadata exist, some of which are specific to certain CMS platforms.  

### Usage  

You can find the following inside the `<head>`:  

- **Title of the webpage**  
- **Asynchronous script calls**  
- **Metadata**  
- **Embedded CSS code** (critical CSS)  
- **Embedded JavaScript code**  

## Resources  

[HEAD – A free guide to head elements](https://htmlhead.dev/)  

## Meta Charset  

The `<meta charset>` tag declares the page’s character encoding.  

### Example Usage  

    ```html
    <head>
        <!-- Set character encoding for the document -->
        <meta charset="utf-8">
    </head>

## Resources
- [Meta: The Document-level Metadata Element - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#attr-charset)  
- [Declaring Character Encodings in HTML - W3C](https://www.w3.org/International/questions/qa-html-encoding-declarations)  
- [Meta Charset - Bitsofco.de](https://bitsofco.de/meta-charset/)  


## Viewport

The meta viewport gives information about the initial size of the viewport.

Tip: The viewport is used by mobile devices only.

Accessibility tip: Never use maximum-scale=1.0. [It prevents the user from zooming in on the website](https://www.a11yproject.com/posts/never-use-maximum-scale/). It causes an accessibility issue.
    ```html
    
    <head>
        ...
        <!-- Viewport for responsive web design -->
        <meta name="viewport" content="key=value, key=value">
    </head>

### Resources
- [Responsive Design With Viewport Control](https://bitsofco.de/responsive-design-viewport/)

## Title 

- The title meta tag defines the title of the web page.

- Tip: The title is only visible on the tab/window of your browser.

Warning! The title should always have less than 56 characters.

    ```html
    <head>
        ...
        <!-- Document Title -->
        <title>Page title</title>
    </head>

### Resources 

[The ideal width of the SEO title • Yoast](https://yoast.com/page-titles-seo/)

## Meta description

    ``` html 
    <head>
        ...
        <!-- Meta Description -->
        <meta name="description" content="Description of the page less than 150 characters">
    </head>

### Resources

[How to create the right meta description](https://yoast.com/meta-descriptions/)

## Favicons
    ```html 
    <head>
        ...
        <!-- Standard favicon -->
        <link rel="icon" type="image/x-icon" href="https://example.com/favicon.ico">
        <!-- Recommended favicon format -->
        <link rel="icon" type="image/png" href="https://example.com/favicon.png">
        ...
    </head>

### Resources

- [Favicon & App Icon Generator](https://www.favicon-generator.org/)
- [Favicon Generator for all platforms: iOS, Android, PC/Mac…](https://realfavicongenerator.net/)
- [Obsessive cheat sheet to favicon sizes/types.](https://github.com/audreyfeldroy/favicon-cheat-sheet)
- [Favicons, Touch Icons, Tile Icons, etc. Which Do You Need? | CSS-Tricks](https://css-tricks.com/favicon-quiz/)
- [PNG favicons - caniuse](https://caniuse.com/link-icon-png)

## Tag attributes

Attributes provide additional information or instruction for an HTML element. It is always included inside the opening tag.

### Data-attribute

It is possible to declare any attribute using the data- prefix
    ``` html 
    <tag data-extra-attr="value">some content</tag>

### Resources 

[HTML attribute reference - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)

### header Tag 
- The <header> HTML tag element is used to identify the top of a webpage, article, section, or other segment of a page. The header is normally always the same across all pages of your website.

![header](header.jpg)

### Usage

- Logo of the website
- Navigation
- Search form
- ...

#### HTML Example

    ```html
    <body>
        <header>This is my header</header>
    </body>
#### Resources 
-[header - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)

## main tag 
- The <main> HTML tag is a structural element located generally between the <header> and the <footer> and contains the content of your web page.

![main tag](main.jpg)
```html
        ...
    <body>
        <header>This is my header</header>
        <main>
            This is where I put my content
        </main>
    </body>

## footer tag 
The <footer> HTML tag is a structural element used to identify the footer of a page, article, or section.

![footer tag](footer.jpg)

### Usage

- Copyright information
- Authorship information
- Navigation elements
- Social icons or links
- ...

### HTML Example

    ```html
    <body>
        <header>This is my header</header>
        <main>
            This is where I put my content
        </main>
        <footer>This is the footer of my page</footer>
    </body>
## Resources
- [footer - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer)

## aside tag 
The <aside> HTML tag contains additional information related to the main content.

![aside tag](aside.jpg)

### Usage

- Monthly archives
- List of categories
- ...

### HTML Example

```html
<body>
    ...
    <main>
        <section>
            <article>This is my article 1</article>
            <article>This is my article 2</article>
            <article>This is my article 3</article>
        </section>
        <aside>
        </aside>
    </main>
    ...
</body>

## section tag
- The <section> tag element allows the grouping of related elements. You can usually find a <header> and <footer> attached to a section.

![section tag](section.jpg)

### Usage

- ...

### HTML Example

```html
<body>
    ...
    <main>
        <section>This is my section 1</section>
        <section>This is my section 2</section>
        <section>This is my section 3</section>
    </main>
    ...
</body>
### Resources

[section: The Generic Section element - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section)

## article tag

An <article> HTML tag represent a self-contained piece of content which could theoretically be distributed to other websites and platforms as a stand-alone unit.
![article](article.jpg)

### Usage

- Blog posts
- News articles
- Product cards
- Forum posts
- ...

### HTML Example

```html
<body>
    ...
    <main>
        <section>
            <article>This is article 1</article>
            <article>This is article 2</article>
        </section>
    </main>
    ...
</body>
### Resources
[article: The Article Contents element - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article)

## nav tag
The <nav> HTML tag is a structural element with navigation links.
![nag tag](nav.jpg)
```html
<body>
    <header> I'm inside the header
        <nav>
          <!-- This is an example of links -->
          <a href="/">Home</a>
          <a href="/about">About</a>
          <a href="/contact">Contact</a>
          <!-- / -->
        </nav>
    <header/>
    ...
</body>
### Resources
- [nav: The Navigation Section element - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav)

## Headings


Headings are used to define a section heading.

- **Type**: Self-closing
- **Block**: No

> **Warning!** Browsers apply different sizes for each heading in their default CSS rules. Keep in mind that HTML is about content and not the styling. Never use an `h4` after an `h2`. For example, always keep a descendant order (`h1 > h2 > h3…`).

> **Accessibility tip**: Headings are used by voice browsers to help navigate through the webpage.

### HTML Example

```html
<h1>This is my title level 1</h1>
<h2>This is my title level 2</h2>



### Resources
- [h1–h6: The HTML Section Heading elements - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)


## `<p>` Tag

A `<p>` HTML tag defines a paragraph of text.

- **Type**: Self-closing
- **Block**: No

> **Warning!** If you need a container to wrap multiple elements, use a `div` instead of `p`. Only use the paragraph tag if your content could be considered a paragraph of text.

### HTML Example

```html
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
