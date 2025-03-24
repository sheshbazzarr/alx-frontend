# 0x00. Advanced HTML

concepts html-elements of a web page ()

- [HTML elements of a webpage](HTML-elements-of-a-webpage.md)

<details>
    <summary>HTML - elements of a web page </summary>
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

## Rersources 
- [Meta: The Document-level Metadata Element - HTML: Hypertext Markup Language | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta#attr-charset)  
- [Declaring Character Encodings in HTML - W3C](https://www.w3.org/International/questions/qa-html-encoding-declarations)  
- [Meta Charset - Bitsofco.de](https://bitsofco.de/meta-charset/)  





</details>