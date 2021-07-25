# Summary of CSS

**CSS (Cascading Style Sheets)**: allows you to create beautiful web pages, but how does it work? This article explains what CSS is through a simple syntax example and also introduces some key terms about the language.

 **Why use CSS?**

 CSS helps you separate the information content of a document from the details of how to display it. The details of how to display a document are called its style. Separate style and content so you can: 
* Avoid duplication 
* Make it easy to maintain 
 Use the same content in different styles for different purposes 
 Your website can have thousands of pages that look similar. With CSS, you can store style information in a common file shared by all pages. When the user displays a web page, the user's browser loads the page content and style information. When users print a web page, you can provide different style information to make the printed page easier to read. 
 Generally uses HTML to describe the content of a document, not its style; use CSS to specify its style, not its content. Of course, there are exceptions to this rule, and HTML also provides some ways to specify styles. For example, in HTML, you can use the tag to make text bold and you can specify the background color of the page in your <body>. hashtag. When you use CSS, you generally avoid using these HTML styling features to collect all the styling information from your document in one place.


 **Three Ways to Insert CSS**
* External CSS
* Internal CSS
* Inline CSS

External CSS
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.

Inline CSS
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

![](https://www.w3docs.com/uploads/media/default/0001/05/6d07a36ebe6d55273b39440f2391f1d7e6d4092a.png)