
# HTML

This repo is all about getting started with intro to HTML to exploring its advanced features and what are the syntax's used,etc.



## Authors

- [@adityahongal](https://www.github.com/adityahongal)


## 🚀 About Me
I'm a front end developer


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]https://www.linkedin.com/in/adityahongal/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)]


## Roadmap

🚀 **"HTML Basics: Getting Started"**

Learn the fundamental concepts of HTML, including elements, attributes, and page structure. 

🚀 **"In the Head: HTML Metadata Simplified"**

Explore the unseen part of an HTML document—its head. Discover crucial metadata, including page title, CSS links for styling, custom favicons, and essential information about the document.

🚀 **Understanding HTML Text Semantics**

HTML's primary role is to give text meaning, enabling proper display in browsers. Explore breaking up text with headings, paragraphs, adding emphasis, creating lists, and more using HTML.

🚀 **Mastering Hyperlinks in HTML**

Explore the crucial role of hyperlinks in shaping the web. Learn the syntax for creating links and discover best practices for effective hyperlinking.

🚀 **Unveiling Advanced Text Formatting in HTML**

Delve into lesser-known HTML elements for text formatting beyond the basics. Explore markup for quotations, description lists, code, subscript, superscript, contact information, and more.

🚀 **Crafting Document and Website Structure with HTML**

Beyond individual elements, HTML is key to defining the structure of your website. Learn how to plan a basic website structure and write HTML to represent sections like the header, navigation menu, and main content column.

🚀 **HTML Debugging Essentials**

Writing HTML is one thing, but what if errors arise? Explore tools to troubleshoot and debug HTML code effectively in this informative article.


## Documentation

🌎 **Anatomy of a HTML**

```html
<p>My cat is very grumpy</p>
```

An element in HTML has three parts:

1. **Opening tag:** It marks the beginning of the element and is enclosed in angle brackets. For example, `<p>` is the opening tag for a paragraph.

2. **Content:** This is the actual text or information within the element. For a paragraph element, it's the text of the paragraph.

3. **Closing tag:** Similar to the opening tag but with a forward slash before the element name. It marks the end of the element. For a paragraph, the closing tag is `</p>`.

So, an HTML element is a combination of the opening tag, content, and closing tag.

🌎 **NESTING ELEMENTS**

In HTML, elements can be nested, meaning one element can be placed inside another. For example, if we want to emphasize that our cat is very grumpy, we can use the `<strong>` element to make the word "very" bold within the paragraph:

```html
<p>My cat is <strong>very</strong> grumpy.</p>
```

🌎 **VOID ELEMENTS**

It's important that the opening and closing tags are properly nested, meaning they are inside each other without overlapping.

Some HTML elements don't follow the usual pattern of an opening tag, content, and closing tag. They are called "void elements." An example is the `<img>` element, which is used to embed an image. It consists of a single tag and is used like this:

```html
<img src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png" alt="Firefox icon" />
```

In this example, the `<img>` element embeds an image onto the page, and it doesn't have a closing tag.

🌎 **ATTRIBUTES**

In HTML, attributes provide extra information about an element. Here's how to use them with the `<img>` element:

```html
<img src="https://raw.githubusercontent.com/mdn/beginner-html-site/gh-pages/images/firefox-icon.png" alt="The Firefox icon" width="300" height="300" />
```

Attributes are added to the element tag and include information such as the image source (`src`), alternative text (`alt`), width (`width`), and height (`height`). Each attribute is separated by spaces and follows the pattern: `attribute="value"`.


🌎 **BOOLEAN ATTRIBUTES**

In HTML, some attributes are written without values and are called Boolean attributes. They can only have one value, usually the same as the attribute name. For example, the disabled attribute can be used with form input elements to prevent user entries. It can be written with or without a value:
```html
<input type="text" disabled="disabled" />
```
As shorthand, it is acceptable to write this as follows:

```html
<!-- using the disabled attribute prevents the end user from entering text into the input box -->

<input type="text" disabled />

<!-- text input is allowed, as it doesn't contain the disabled attribute -->

<input type="text" />

```

🌎 **OMITTING QUOTES AROUND ATTRIBUTES VALUES**

The provided HTML code features an anchor element (<a>) creating a hyperlink. Initially, only the href attribute is used:

```html
<a href=https://www.mozilla.org/>favorite website</a>
```

However, issues arise when adding a title attribute without quotes:

```html
<a href=https://www.mozilla.org/ title=The Mozilla homepage>favorite website</a>
```

The absence of quotes causes the browser to misinterpret the title attribute, leading to errors. To correct this, use quotes around attribute values:

```html
<a href="https://www.mozilla.org/" title="The Mozilla homepage">favorite website</a>
```

This ensures proper attribute handling and avoids potential problems in the markup.

🌎 **SINGLE OR DOUBLE QUOTES**

You can use either single or double quotes for HTML attribute values based on your preference. Both are equivalent:

```html
<a href='https://www.example.com'>A link to my example.</a>
<a href="https://www.example.com">A link to my example.</a>
```

However, it's crucial not to mix single and double quotes, as shown in the problematic example below:

```html
<a href="https://www.example.com'>A link to my example.</a>
```

Ensure consistency by using either single or double quotes throughout your HTML code.

🧵 **Anatomy of an HTML Document**

The provided code is a basic HTML document with the following structure:

```html
<!doctype html>
<html lang="en-US">
  <head>
    <meta charset="utf-8" />
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```

Here's a breakdown of each section:

- `<!doctype html>`: This declaration defines the document type and version of HTML being used (HTML5 in this case).

- `<html lang="en-US">`: The opening tag for the HTML document, indicating the language as English (United States).

- `<head>`: This section contains meta-information about the document, such as character encoding and the document's title.

- `<meta charset="utf-8" />`: Specifies the character encoding for the document as UTF-8, which is widely used for supporting various characters.

- `<title>My test page</title>`: Sets the title of the HTML document to "My test page."

- `<body>`: The main content of the HTML document goes within this section.

- `<p>This is my page</p>`: A paragraph of text inside the body, stating "This is my page."

- `</html>`: The closing tag for the HTML document.

This example represents a simple HTML document structure with a title and a paragraph of text.


🧵 **Creation of an Sample HTML Document**

```html
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>My test page</title>
  </head>
  <body>
    <h1>This is my First HTML Intro Page</h1>
    <p>You can listen to the music which is <strong><a href="https://www.youtube.com/watch?v=msokY714Wzg/">composed by me</a></strong>. It is streaming on all platforms.</p>
  </body>
</html>

```






![Logo](https://github.com/adityahongal/html/blob/main/images/Screenshot%20(2).png)

🧵 **Entity references: Including special characters in HTML**

In HTML, certain characters like `<`, `>`, `"`, `'`, and `&` have special meanings in the syntax. To include them as regular text, use character references. These references start with `&` and end with `;`:

- `<` is represented as `&lt;`
- `>` is represented as `&gt;`
- `"` is represented as `&quot;`
- `'` is represented as `&apos;`
- `&` is represented as `&amp;`

The character reference equivalent could be easily remembered because the text it uses can be seen as less than for &lt;, quotation for &quot; and similarly for others.

In the example below, there are two paragraphs:
```html
<p>In HTML, you define a paragraph using the <p> element.</p>

<p>In HTML, you define a paragraph using the &lt;p&gt; element.</p>
```
In the output below, you can see that the first paragraph has gone wrong. The browser interprets the second instance of <p> as starting a new paragraph. The second paragraph looks fine because it has angle brackets with character references.

```html
In HTML, you define a paragraph using the

element.

In HTML, you define a paragraph using the <p> element.
```

🧵 **HTML comments**

In HTML, comments are a way to include notes in the code for explanation or documentation purposes. Browsers ignore comments, making them invisible to users. Comments are useful for explaining logic, especially when revisiting code after some time, and they serve as valuable documentation when multiple people are working on the codebase.

To write an HTML comment, wrap it in the special markers <!-- and -->. For example:

```html
<p>I'm not inside a comment</p>

<!-- <p>I am!</p> -->

```


## What's in the head? Metadata in HTML

☝️ **What is HTML Head ?**

The HTML head is the contents of the <head> element. Unlike the contents of the <body> element (which are displayed on the page when loaded in a browser), the head's content is not displayed on the page. Instead, the head's job is to contain metadata about the document.
```html
<head>
  <meta charset="utf-8" />
  <title>My test page</title>
</head>
```

☝️ **Adding a title**

We've already seen the <title> element in action — this can be used to add a title to the document. This however can get confused with the h1 element, which is used to add a top level heading to your body content — this is also sometimes referred to as the page title. But they are different things!

1. **`<h1>`** Element:
   - Appears on the loaded page in the browser.
   - Should be used once per page to mark up the main title of your content, such as a story title or news headline.

2. **`<title>`** Element:
   - Represents metadata for the overall HTML document.
   - Reflects the title of the entire HTML document, not the content within the document.

Example code and screenshot:
```html
<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>&lt;title&gt; element</title>
  </head>
  <body>
    <h1>&lt;h1&gt; element</h1>
  </body>
</html>
```

![Logo](https://github.com/adityahongal/html/blob/main/images/diff%20between%20title%20%26%20h1.png)


☝ **Metadata: the <meta> element**

Metadata is data that describes data, and HTML has an "official" way of adding metadata to a document — the ```<meta>``` element.

Specifying your document's character encoding

```html 
<meta charset="utf-8" /> 
```
In the above example,this element specifies the document's character encoding — the character set that the document is permitted to use. utf-8 is a universal character set that includes pretty much any character from any human language. This means that your web page will be able to handle displaying any language; it's therefore a good idea to set this on every web page you create!

☝ **Applying CSS and Javascript to HTML**

To enhance the appearance and functionality of websites, CSS and JavaScript are commonly used. In HTML, you employ the `<link>` element for CSS and the `<script>` element for JavaScript.

For CSS:

```html
<link rel="stylesheet" href="my-css-file.css" />
```

This goes inside the `<head>` of your document.

For JavaScript:

```html
<script src="my-js-file.js" defer></script>
```

Also placed in the `<head>`, the `defer` attribute ensures that the JavaScript is loaded after the HTML is parsed, preventing potential errors.

☝ **Setting Primary language of the Document**

Set your webpage's language by adding the "lang" attribute to the opening HTML tag, like this:

```html
<html lang="en-US">
  <!-- Your content goes here -->
</html>
```

This not only helps search engines index your document more effectively but also enhances accessibility for users, especially those with visual impairments who rely on screen readers.


## HTML Text Fundamentals

One of HTML's main jobs is to give text structure so that a browser can display an HTML document the way its developer intends.

🖋️ **The basics - Headings and Paragraphs**

Most structured text consists of headings and paragraphs, whether you are reading a story, a newspaper, a college textbook, a magazine, etc.

Structured content makes the reading experience easier and more enjoyable.

In HTML, each paragraph has to be wrapped in a <p> element, like so:
```html
<p>I am a paragraph, oh yes I am.</p>
```

Each heading has to be wrapped in a heading element:
```html
<h1>I am the title of the story.</h1>
```

There are six heading elements: h1, h2, h3, h4, h5, and h6. Each element represents a different level of content in the document; <h1> represents the main heading, <h2> represents subheadings, <h3> represents sub-subheadings, and so on.

🖋️ **Implementing structural hierarchy**

For example, in this story, the <h1> element represents the title of the story, the <h2> elements represent the title of each chapter, and the <h3> elements represent sub-sections of each chapter:

```html
<h1>The Crushing Bore</h1>

<p>By Chris Mills</p>

<h2>Chapter 1: The dark night</h2>

<p>
  It was a dark night. Somewhere, an owl hooted. The rain lashed down on the…
</p>

<h2>Chapter 2: The eternal silence</h2>

<p>Our protagonist could not so much as a whisper out of the shadowy figure…</p>

<h3>The specter speaks</h3>

<p>
  Several more hours had passed, when all of a sudden the specter sat bolt
  upright and exclaimed, "Please have mercy on my soul!"
</p>
```

When creating structural hierarchies in HTML, consider these best practices:

1. Use a single `<h1>` per page as the top-level heading.
2. Ensure the correct order of headings in the hierarchy. Avoid using, for instance, `<h3>` elements for subheadings followed by `<h2>` elements for sub-subheadings.
3. Aim to use no more than three heading levels per page, unless absolutely necessary. Too many levels can make the document complex and challenging to navigate. In such cases, consider spreading the content across multiple pages.

These guidelines help maintain a logical and organized structure for your content.

🖋️ **Lists**

Now, let's talk about lists. Lists are ubiquitous in daily life, from your shopping list to the steps you follow to reach your home. Similarly, on the web, there are three main types of lists to consider.

**Unordered Lists**

Unordered lists are for items where the order doesn't matter. For instance, a shopping list:

Start with a `<ul>` element that wraps around all the list items:

Wrap each item in a `<li>` (list item) element:

```html
<ul>
  <li>milk</li>
  <li>eggs</li>
  <li>bread</li>
  <li>hummus</li>
</ul>
```

**Ordered Lists**

Ordered lists are used when the order of items matters, like a set of directions:

Markup is similar to unordered lists, but use `<ol>` (ordered list) instead of `<ul>`:

```html
<ol>
  <li>Drive to the end of the road</li>
  <li>Turn right</li>
  <li>Go straight across the first two roundabouts</li>
  <li>Turn left at the third roundabout</li>
  <li>The school is on your right, 300 meters up the road</li>
</ol>
```

**Nested Lists**

It is perfectly OK to nest one list inside another one. You might want to have some sub-bullets sitting below a top-level bullet.

```html
<ol>
  <li>Remove the skin from the garlic, and chop coarsely.</li>
  <li>Remove all the seeds and stalk from the pepper, and chop coarsely.</li>
  <li>Add all the ingredients into a food processor.</li>
  <li>
    Process all the ingredients into a paste.
    <ul>
      <li>
        If you want a coarse "chunky" hummus, process it for a short time.
      </li>
      <li>If you want a smooth hummus, process it for a longer time.</li>
    </ul>
  </li>
</ol>
 
```

🖋️ **Emphasis & Importance**

HTML offers semantic elements to emphasize and mark up textual content, allowing you to convey importance or alter the meaning of sentences.

**Emphasis**

In HTML, the `<em>` (emphasis) element is used to mark up text when you want to add emphasis, similar to how we stress words in spoken language. This not only enhances readability but is also recognized by screen readers, which may convey the emphasized text differently. While browsers typically style `<em>` text as italic, it's important to note that this element is not meant for styling purposes alone.

Example:

```html
<p>I am <em>glad</em> you weren't <em>late</em>.</p>
```

**Importance**

In HTML, the `<strong>` element is used to emphasize important words, similar to stressing them in spoken language and bolding them in written language. This not only enhances the document's usefulness but is also recognized by screen readers, allowing them to convey the emphasized text differently. Although browsers typically style `<strong>` text as bold, it's crucial to note that this element serves a semantic purpose beyond styling.

Example:

```html
<p>This liquid is <strong>highly toxic</strong>.</p>

<p>I am counting on you. <strong>Do not</strong> be late!</p>
```


You can nest strong and emphasis inside one another if desired:

```html
<p>This liquid is <strong>highly toxic</strong> — if you drink it, <strong>you may <em>die</em></strong>.</p>
```

🖋️ **Italic,Bold and Underline**

In HTML, the `<b>`, `<i>`, and `<u>` elements were originally introduced for styling text with bold, italics, or underline in a time when CSS support was limited. However, these are considered presentational elements, influencing appearance rather than semantics. With HTML5, they were redefined with new semantic roles, but their use is now discouraged in favor of more meaningful and accessible elements like `<strong>`, `<em>`, `<mark>`, or `<span>`.

Here's a rule of thumb: Use `<b>`, `<i>`, or `<u>` only when there's no more suitable element, and always consider alternatives for better semantics. Accessibility is crucial, and elements like `<i>` may not be helpful for screen readers or users of different writing systems.

- `<i>` conveys meaning traditionally expressed in italics, such as foreign words, taxonomic designations, technical terms, or thoughts.
- `<b>` conveys meaning traditionally expressed in bold, like keywords, product names, or lead sentences.
- `<u>` conveys meaning traditionally expressed with underline, such as proper names or misspellings.