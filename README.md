
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
## Creating Hyperlinks

🔗 **What is a Hyperlink ?**

Hyperlinks are a fundamental feature of the Web, defining its interconnected nature. Since the inception of the Web, hyperlinks have enabled the linking of documents or resources, directing to specific sections or making applications accessible through web addresses (URLs). By converting web content into clickable links, users can seamlessly navigate between different web locations.

🔗 **Anatomy of a Link**

A basic link is created by wrapping the text or other content inside an <a> element and using the href attribute, also known as a Hypertext Reference, or target, that contains the web address.

```html
<p>
  I'm creating a link to
  <a href="https://www.mozilla.org/en-US/">the Mozilla homepage</a>.
</p>
```

**Block Level Links**

Almost any content can be made into a link, even block-level elements. If you want to make a heading element a link then wrap it in an anchor (<a>) element as shown in the following code snippet:

```html
<a href="https://developer.mozilla.org/en-US/">
  <h1>MDN Web Docs</h1>
</a>
<p>
  Documenting web technologies, including CSS, HTML, and JavaScript, since 2005.
</p>
```

**Image Link**

If you have an image you want to make into a link, use the <a> element to wrap the image file referenced with the <img> element. The example below uses a relative path to reference a locally stored PNG image file.

```html
<a href="https://developer.mozilla.org/en-US/">
  <img src="mdn_logo.png" alt="MDN Web Docs" />
</a>
```

**Adding supporting information with the title attribute**

Another attribute you may want to add to your links is title. The title contains additional information about the link, such as which kind of information the page contains, or things to be aware of on the website.

```html
<p>
  I'm creating my first hyperlink to my YOUTUBE
  <a
    href="https://www.youtube.com/watch?v=msokY714Wzg"
    title="Checkout my Music Video on Youtube"> click here for link
    </a>.
  </p>
```

This gives us the following result and hovering over the link displays the title as a tooltip:

![Alt hyperlinkexample](https://github.com/adityahongal/html/blob/main/images/Creating%20first%20hyperlink.png)


🔗 **URLs and Paths**

A URL, short for Uniform Resource Locator, is a text string specifying the location of something on the Web. For instance, Mozilla's English homepage is at https://www.mozilla.org/en-US/.

URLs utilize paths to locate files, defining their position in the filesystem. Consider a directory structure, like the one in the "creating-hyperlinks" directory. The root, "creating-hyperlinks," encompasses an index.html file and a contacts.html file. In a live website, index.html typically serves as the home or landing page.

Inside the root, there are two directories, "pdfs" and "projects," each containing a file—project-brief.pdf and index.html, respectively.

1. **Same directory:**
   To hyperlink from index.html to contacts.html, which is in the same directory, you directly specify the filename:
   ```html
   <p>Want to contact us? Visit our <a href="contacts.html">contacts page</a>.</p>
   ```

2. **Moving down into subdirectories:**
   To link from index.html to projects/index.html, you navigate into the "projects" directory and then specify the file:
   ```html
   <p>Explore my <a href="projects/index.html">project homepage</a>.</p>
   ```

3. **Moving back up into parent directories:**
   To link from projects/index.html to pdfs/project-brief.pdf, you go up a level and then into the "pdfs" directory:
   ```html
   <p>Access the <a href="../pdfs/project-brief.pdf">project brief</a>.</p>
   ```

This way, URLs help establish the structure and accessibility of files within a website.


**Document Fragment**

You can link to specific parts of an HTML document, known as document fragments, by assigning an `id` attribute to the desired element. Typically, linking to a heading is practical, like this:

```html
<h2 id="Mailing_address">Mailing address</h2>
```

To create a hyperlink to this specific id, append it to the URL preceded by a hash/pound symbol (#), as shown:

```html
<p>Write us a letter using our <a href="contacts.html#Mailing_address">mailing address</a>.</p>
```

You can also use the document fragment reference on its own to link to another part of the current document:

```html
<p>The <a href="#Mailing_address">company mailing address</a> is at the bottom of this page.</p>
```

This technique allows for precise navigation within a document.


**Absolute Vs Relative URLs**

There are two types of URLs: absolute and relative.

**Absolute URL:**
- Points to a location defined by its absolute web location, including the protocol and domain name.
- Always refers to the same location, regardless of where it's used.
- Example: `https://www.example.com/projects/index.html` or `https://www.example.com/projects/`.

**Relative URL:**
- Points to a location relative to the file you are linking from.
- Example: If linking from `https://www.example.com/projects/index.html` to a PDF file in the same directory, the relative link is just the filename, like `project-brief.pdf`. If the PDF is in a subdirectory called `pdfs`, the relative link would be `pdfs/project-brief.pdf`.
- The location it points to depends on the file's actual location; if you move the file, the link destination changes accordingly.
- Be cautious when moving files, as it might lead to broken links if not managed carefully.

**Best Practices for Writing Links:**

1. **Use Clear Link Wording:**
   - Provide descriptive link text that is meaningful out of context.
   - Good: `<a href="https://www.mozilla.org/firefox/">Download Firefox</a>`
   - Bad: `<a href="https://www.mozilla.org/firefox/">Click here</a> to download Firefox`

2. **Avoid Repetitive or Redundant Link Text:**
   - Don't repeat the URL in the link text.
   - Don't include unnecessary phrases like "link" or "links to."

3. **Keep Link Text Short:**
   - Short link text is more manageable for screen readers.

4. **Minimize Duplicating Link Text:**
   - Avoid linking the same text to different destinations, especially when labeled with generic terms like "click here."

5. **Linking to Non-HTML Resources — Clear Signposts:**
   - When linking to downloadable, streamed, or content with unexpected effects, provide clear wording.
   - Example: `<a href="https://www.example.com/large-report.pdf">Download the sales report (PDF, 10MB)</a>`

6. **Use the Download Attribute for Downloads:**
   - When linking to downloadable resources, use the download attribute to set a default save filename.
   - Example: `<a href="download-link" download="filename">Download Latest Firefox for Windows (64-bit) (English, US)</a>`

**Simple Navigation page example**

The code -

```html
<!DOCTYPE html>
<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Homepage</title>
  </head>

  <body>
    <!-- Navigation menu -->

    <ul>
      <li>Home</li>
      <li><a href="pictures.html">Pictures</a></li>
      <li><a href="projects.html">Projects</a></li>
      <li><a href="social.html">Social</a></li>
    </ul>

    <h1>Homepage</h1>

    <p>Welcome to my exciting homepage</p>
  </body>
</html>

```

screenshot 

![Alt navigationpage](https://github.com/adityahongal/html/blob/main/images/simple%20navigation%20page.png)

🔗 **Email Links**

To create links or buttons that open a new outgoing email message, you can use the `<a>` element with the `mailto:` URL scheme. In its basic form, a `mailto:` link indicates the email address of the intended recipient. Here's an example:

```html
<a href="mailto:nowhere@mozilla.org">Send email to nowhere</a>
```

This creates a link that, when clicked, opens the user's email client to send an email to the specified address. If you omit the email address and use "mailto:", a new outgoing email window will be opened with no destination address. This can be useful for "Share" links, allowing users to choose their own email recipient.





## Advanced Text Formatting

🌂 **Description Lists**

Description lists in HTML are used to mark up a set of items and their associated descriptions. They are typically used for terms and definitions, or questions and answers.

Here's a simple example:

```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>

  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>

  <dt>JavaScript</dt>
  <dd>A programming language that enables interactive web pages</dd>
</dl>
```

In this example:

- `<dl>` is the description list container. (description list)
- `<dt>` is used for the term or item.      (description term)
- `<dd>` is used for the description or definition associated with the term.                                   (description definition)

This creates a structured list where each term is followed by its corresponding description.

🌂 **Quotations**

**Blockquotes**

Blockquotes are used in HTML to indicate that a section of content is quoted from another source. If you have a block of content, like a paragraph or multiple paragraphs, that is a quote, you can wrap it in a `<blockquote>` element. You can also include a `cite` attribute with a URL pointing to the source of the quote. Here's an example:

```html
<p>Here is a blockquote:</p>
<blockquote cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
  <p>
    The <strong>HTML <code>&lt;blockquote&gt;</code> Element</strong> (or
    <em>HTML Block Quotation Element</em>) indicates that the enclosed text is
    an extended quotation.
  </p>
</blockquote>
```

The browser will typically render this with default styling, such as indentation, to visually distinguish the blockquote from the surrounding content.

**Inline quotes**

Inline quotations work in exactly the same way, except that they use the <q> element. For example, the below bit of markup contains a quotation from the MDN <q> page:

```html
<p>
  The quote element — <code>&lt;q&gt;</code> — is
  <q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">
    intended for short quotations that don't require paragraph breaks.
  </q>
</p>
```

Browser default styling will render this as normal text put in quotes to indicate a quotation.

```html
The quote element — <q> — is ❝ intended for short quotations that don't require paragraph breaks. ❞
```

**Citations**

The cite attribute is not widely utilized by browsers, screen readers, etc. It doesn't directly affect how the browser displays the content. To make the source of a quotation visible on the page, it's recommended to include it in the text, perhaps by linking the citation. The `<cite>` element can be used to contain the title of the resource being quoted, like the name of a book. However, you can link the text inside `<cite>` to the source of the quote. Here's an example:

```html
<p>
  According to the
  <a href="/en-US/docs/Web/HTML/Element/blockquote">
    <cite>MDN blockquote page</cite>
  </a>:
</p>

<blockquote
  cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote">
  <p>
    The <strong>HTML <code>&lt;blockquote&gt;</code> Element</strong> (or
    <em>HTML Block Quotation Element</em>) indicates that the enclosed text is
    an extended quotation.
  </p>
</blockquote>

<p>
  The quote element — <code>&lt;q&gt;</code> — is
  <q cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/q">
    intended for short quotations that don't require paragraph breaks.
  </q>
  — <a href="/en-US/docs/Web/HTML/Element/q"><cite>MDN q page</cite></a>.
</p>
```

Citations are styled in italic font by default.


🌂 **Abbreviations**

The `<abbr>` element is used to mark up an abbreviation or acronym. It's recommended to provide a full expansion of the term in plain text on first use along with the `<abbr>` element. If adding the expansion seems impractical, especially for short terms, you can use the `title` attribute to provide the full expansion. Here's an example:

```html
<p>
  The <abbr title="World Health Organization">WHO</abbr> is a specialized agency
  of the United Nations responsible for international public health.
</p>
```

In this example, the `<abbr>` element is used to mark the abbreviation "WHO," and the `title` attribute provides the full expansion, "World Health Organization." This helps user agents and informs users about the meaning of the abbreviation.

**Marking up contact details**

HTML has an element for marking up contact details — <address>. This wraps around your contact details, for example:

```html
<address>Chris Mills, Manchester, The Grim North, UK</address>
```
It could also include more complex markup, and other forms of contact information, for example:

```html
<address>
  <p>
    Chris Mills<br />
    Manchester<br />
    The Grim North<br />
    UK
  </p>

  <ul>
    <li>Tel: 01234 567 890</li>
    <li>Email: me@grim-north.co.uk</li>
  </ul>
</address>
```


🌂 **Superscript and Subscript**

You will occasionally need to use superscript and subscript when marking up items like dates, chemical formulae, and mathematical equations so they have the correct meaning. The <sup> and <sub> elements handle this job. For example:

```html
<p>My birthday is on the 25<sup>th</sup> of May 2001.</p>
<p>
  Caffeine's chemical formula is
  C<sub>8</sub>H<sub>10</sub>N<sub>4</sub>O<sub>2</sub>.
</p>
<p>If x<sup>2</sup> is 9, x must equal 3 or -3.</p>

```

🌂 **Representing computer code**

There are a number of elements available for marking up computer code using HTML:

**<code>**: For marking up generic pieces of computer code.

**<pre>**: For retaining whitespace (generally code blocks) — if you use indentation or excess whitespace inside your text, browsers will ignore it and you will not see it on your rendered page. If you wrap the text in **<pre></pre>** tags however, your whitespace will be rendered identically to how you see it in your text editor.

**<var>**: For specifically marking up variable names.

**<kbd>**: For marking up keyboard (and other types of) input entered into the computer.

**<samp>**: For marking up the output of a computer program.


🌂 **Marking up Times and Dates**

The `<time>` element in HTML is used for marking up times and dates in a machine-readable format. Here's a simplified example with various options:

```html
<!-- Standard simple date -->
<time datetime="2016-01-20">20 January 2016</time>

<!-- Just year and month -->
<time datetime="2016-01">January 2016</time>

<!-- Just month and day -->
<time datetime="01-20">20 January</time>

<!-- Just time, hours and minutes -->
<time datetime="19:30">19:30</time>

<!-- You can do seconds and milliseconds too! -->
<time datetime="19:30:01.856">19:30:01.856</time>

<!-- Date and time -->
<time datetime="2016-01-20T19:30">7.30pm, 20 January 2016</time>

<!-- Date and time with timezone offset -->
<time datetime="2016-01-20T19:30+01:00">
  7.30pm, 20 January 2016 is 8.30pm in France
</time>

<!-- Calling out a specific week number -->
<time datetime="2016-W04">The fourth week of 2016</time>
```

The `<time>` element helps make dates and times machine-readable, allowing for better automation and interpretation by computers. The `datetime` attribute provides a standardized format for these machine-readable values.


## Document and Website structure

HTML uses block-level elements to define different sections of a website, such as the header, navigation menu, and main content column. This involves planning the basic structure of your website and creating HTML code to represent these sections.

🏙️ **Basic sections of a Document**

Webpages typically share common components, including:

1. **Header:**
   - Located at the top.
   - Contains a prominent heading, logo, and possibly a tagline.
   - Generally remains consistent across different pages.

2. **Navigation Bar:**
   - Features links to the main sections of the site.
   - Represented by menu buttons, links, or tabs.
   - Often remains consistent across various pages for user familiarity.

3. **Main Content:**
   - Central area that holds the unique content of a specific webpage.
   - Varied content, such as videos, articles, maps, or headlines.

4. **Sidebar:**
   - Located on the side.
   - Contains additional information, links, quotes, or ads.
   - Contextual to the main content, providing supplementary details.

5. **Footer:**
   - Positioned at the bottom of the page.
   - Includes fine print, copyright notices, or contact information.
   - Sometimes utilized for SEO with links to popular content.

While webpages may differ in appearance, these components form a standard structure, ensuring a consistent and user-friendly experience.

🏙️ **HTML for structuring content**

HTML provides specific tags to semantically mark up sections of content based on their functionality. Here are the main elements:

1. **Header:**
   - `<header>`

2. **Navigation Bar:**
   - `<nav>`

3. **Main Content:**
   - `<main>` for unique content on the page.
   - `<article>` for a block of standalone content (e.g., a blog post).
   - `<section>` for grouping related content or functionality.
   - `<div>` for generic divisions.

4. **Sidebar:**
   - `<aside>` (often placed inside `<main>`)

5. **Footer:**
   - `<footer>`

**HTML Layout Elements in Detail:**

- `<main>`: For content unique to the page. Use only once per page, directly inside `<body>`. Avoid nesting within other elements.

- `<article>`: Encloses a block of related content that makes sense on its own (e.g., a blog post).

- `<section>`: Groups together a single part of the page, representing functionality or a theme. Consider using headings within each section.

- `<aside>`: Contains content indirectly related to the main content (e.g., glossary entries, related links).

- `<header>`: Represents a group of introductory content. Global header if a child of `<body>`, specific header if a child of `<article>` or `<section>`.

- `<nav>`: Contains the main navigation functionality for the page.

- `<footer>`: Represents a group of end content for a page.

These elements aid in creating a structured and accessible HTML document. For detailed information on each element, refer to the "HTML element reference" section.

🏙️ **Non Semantic Wrappers**

When you encounter situations without an ideal semantic element to group or wrap content, HTML provides `<div>` and `<span>` for such cases. Use these with a class attribute for easy targeting with CSS or JavaScript.

- **`<span>`:**
  - Inline, non-semantic element.
  - Use when a better semantic element is unavailable or when no specific meaning is desired.
  - Example:

    ```html
    <p>
      The King walked drunkenly back to his room at 01:00.
      <span class="editor-note">
        [Editor's note: At this point in the play, the lights should be down low].
      </span>
    </p>
    ```

- **`<div>`:**
  - Block-level, non-semantic element.
  - Use when a better semantic block element is unavailable or when no specific meaning is desired.
  - Example (shopping cart widget):

    ```html
    <div class="shopping-cart">
      <h2>Shopping cart</h2>
      <ul>
        <li>
          <p>
            <a href=""><strong>Silver earrings</strong></a>: $99.95.
          </p>
          <img src="../products/3333-0985/thumb.png" alt="Silver earrings" />
        </li>
        <li>…</li>
      </ul>
      <p>Total cost: $237.89</p>
    </div>
    ```

In the shopping cart example, a `<div>` is suitable as it doesn't necessarily relate to the main content and can be viewed from anywhere on the site. The included heading aids screen reader users in locating it.

🏙️ **Line breaks and horizontal rules**

**<br>: the line break element**

The `<br>` element creates a line break within a paragraph, providing a way to force a rigid structure, particularly useful for situations where fixed short lines are desired, such as in a postal address or a poem. Here's an example:

```html
<p>
  There once was a man named O'Dell<br />
  Who loved to write HTML<br />
  But his structure was bad, his semantics were sad<br />
  and his markup didn't read very well.
</p>
```

Without the `<br>` elements, the paragraph would be rendered as one long line.

**<hr>: the thematic break element**

The `<hr>` element creates a horizontal rule in the document, serving as a visual separator to denote a thematic change in the text, such as a shift in topic or scene. Here's an example:

```html
<p>
  Ron was backed into a corner by the marauding netherbeasts. Scared, but
  determined to protect his friends, he raised his wand and prepared to do
  battle, hoping that his distress call had made it through.
</p>
<hr />
<p>
  Meanwhile, Harry was sitting at home, staring at his royalty statement and
  pondering when the next spin-off series would come out when an enchanted
  distress letter flew through his window and landed in his lap. He read it
  hazily and sighed; "better get back to work then," he mused.
</p>
```

The `<hr>` element visually represents a horizontal line, indicating a clear separation between the paragraphs.

## Multimedia and Embedding

📷 **Images in HTML**

The <img> element is a fundamental part of web development, allowing the incorporation of images into web pages. In addition to covering the basics of using the <img> element, we'll explore advanced features such as captioning with <figure>, its connection to CSS background images, and introduce various other graphics available for the web platform.

📷 **How do we put an image on a webpage?**

To add a simple image to a web page, use the <img> element. This is a void element (meaning, it cannot have any child content and cannot have an end tag) that requires two attributes to be useful: src and alt. The src attribute contains the URL pointing to the image you want to embed, and alt provides alternative text for accessibility. For instance, if your image is named "dinosaur.jpg" in the same directory as your HTML page, you can include it like this:

```html
<img src="dinosaur.jpg" alt="Dinosaur" />
```

If the image is in an "images" subdirectory within the same directory as the HTML page, the code would be:

```html
<img src="images/dinosaur.jpg" alt="Dinosaur" />
```

Adjust the file path accordingly based on the image's location.

You can also embed the image using its absolute URL, like this:

```html
<img src="https://www.example.com/images/dinosaur.jpg" alt="Dinosaur" />
```

However, it's generally not recommended to link via absolute URLs. It's better to host the images on your site, keeping them on the same server as your HTML. Using relative URLs is more efficient for maintenance; if you ever move your site to a different domain, you won't need to update all your URLs to include the new domain.

example -

![Alt Images in HTML](https://github.com/adityahongal/html/blob/main/images/images%20in%20html.png)


**Alternative Text**

The next attribute we'll look at is `alt`. Its value is supposed to be a textual description of the image, for use in situations where the image cannot be seen or takes a long time to render because of a slow internet connection. For example:

```html
<img
  src="images/dinosaur.jpg"
  alt="The head and torso of a dinosaur skeleton;
          it has a large head with long sharp teeth" />
```

The `alt` attribute provides a description of the image content, making it accessible in scenarios where the image is not visible.

Example - 

![Alt Alternative text](https://github.com/adityahongal/html/blob/main/images/alternative%20text%20in%20html.png)

`alt` **text serves various purposes:**

1. **Accessibility for Visually Impaired Users:** Users with visual impairments rely on screen readers to interpret web content. Providing descriptive `alt` text ensures these users can understand the content conveyed by images.

2. **Error Handling:** If an image fails to load due to a misspelled filename or a broken URL, the `alt` text is displayed instead, providing a meaningful description of the intended image.

3. **Compatibility with Text-Only Browsers:** Text-only browsers, like Lynx, can only display text content. `alt` text allows users of such browsers to comprehend the content of images.

4. **Search Engine Optimization (SEO):** Search engines use `alt` text to understand the content of images. Including relevant and descriptive `alt` text can improve the search engine ranking of a webpage.

5. **User Preference for Reduced Data Transfer:** Users may disable image loading, particularly on mobile devices or in regions with limited bandwidth. In such cases, `alt` text provides context and information about the images.

By incorporating descriptive `alt` text, web developers enhance the overall accessibility, usability, and search engine visibility of their content.

What exactly should you write inside your `alt` attribute? It depends on why the image is there in the first place. In other words, what you lose if your image doesn't show up:

1. **Decoration.** You should use CSS background images for decorative images, but if you must use HTML, add a blank `alt=""`. If the image isn't part of the content, a screen reader shouldn't waste time reading it.
2. **Content.** If your image provides significant information, provide the same information in a brief alt text – or even better, in the main text which everybody can see. Don't write redundant alt text. How annoying would it be for a sighted user if all paragraphs were written twice in the main content? If the image is described adequately by the main text body, you can just use `alt=""`.
3. **Link.** If you put an image inside `<a>` tags, to turn an image into a link, you still must provide accessible link text. In such cases you may, either, write it inside the same `<a>` element, or inside the image's alt attribute – whichever works best in your case.
4. **Text.** You should not put your text into images. If your main heading needs a drop shadow, for example, use CSS for that rather than putting the text into an image. However, If you really can't avoid doing this, you should supply the text inside the alt attribute.

Essentially, the key is to deliver a usable experience, even when the images can't be seen. This ensures all users are not missing any of the content. Try turning off images in your browser and see how things look. You'll soon realize how helpful alt text is if the image cannot be seen.


📷 **Width and Height**

You can use the `width` and `height` attributes to specify the dimensions of your image. These attributes are expressed as integers, representing the image's width and height in pixels.

```html
<img
  src="images/dinosaur.jpg"
  alt="The head and torso of a dinosaur skeleton;
       it has a large head with long sharp teeth"
  width="400"
  height="341"
/>
```

Including these attributes is beneficial because the HTML and images are fetched as separate resources. When the browser receives the HTML, it starts rendering the page to the user even before the images are fully loaded. Specifying dimensions helps reserve space for the image, preventing sudden layout shifts when the image is eventually loaded.

Example -

![Alt width height](https://github.com/adityahongal/html/blob/main/images/width%20and%20height.png)


📷 **Image Titles**

As with links, you can also add `title` attributes to images, to provide further supporting information if needed. In our example, we could do this:

```html
<img
  src="images/dinosaur.jpg"
  alt="The head and torso of a dinosaur skeleton;
          it has a large head with long sharp teeth"
  width="400"
  height="341"
  title="A T-Rex on display in the Manchester University Museum" />
```

This gives us a tooltip on mouse hovering.

📷 **Media Assets and Licensing**

Images (and other media asset types) you find on the web are released under various license types. Before you use an image on a site you are building, ensure you own it, have permission to use it, or comply with the owner's licensing conditions.

Understanding license types

💲**All rights reserved**

When creators release their work with closed copyright protection (all rights reserved), it means they have exclusive rights. To use such content:

1. **Obtain Permission or Pay Fee:**
   - Get written permission or pay a license fee (one-time or rights-managed).
   - Fees may vary based on use details like time, region, industry, etc.

2. **Adhere to Fair Use:**
   - Limit use to what's considered fair use or fair dealing in your jurisdiction.

3. **Assume Copyright Protection:**
   - Authors aren't required to include notices.
   - If no copyright info is visible, assume it's protected; safest to assume all rights are reserved.

💲**Permissive**

If an image has a permissive license like MIT, BSD, or a Creative Commons license, you can use it without paying a fee or seeking permission. However, you must adhere to specific conditions:

1. **Credit and Link:**
   - Provide a link to the original source and credit the creator.

2. **Changes and Derivatives:**
   - Specify if you made changes.
   - Share derivative works under the same license.

3. **Usage Restrictions:**
   - Some licenses may restrict commercial use or sharing of derivatives.

4. **Include License:**
   - Include a copy of the license with any work using the image.

Check the specific license for detailed terms and conditions.

***NOTE -***

Copyleft licenses, common in the software world, require projects built with their code to adopt the same license. This means that any new project using this code, known as a "fork," must also be open-source. Examples include the GNU General Public License (GPL) and "Share Alike" Creative Commons licenses. It ensures that the source code remains accessible for study and modification. Note that software licenses like GPL are not suitable for non-software works as they were designed specifically for software.

💲**Public domain/CCO**

Public domain means there are no copyright restrictions on a work, allowing it to be used freely. One effective way to contribute to the public domain is by using CC0, a Creative Commons license designed for this purpose. When using public domain images, obtain proof of their status, like a screenshot with licensing details. Keep records and consider adding a page to your website listing acquired images and their license requirements. This ensures clarity and compliance.

📷 **Annotating images with figures and figure captions**


To add captions to images in HTML, you can use the `<figure>` and `<figcaption>` elements for better accessibility. Instead of placing the caption outside the image container, use these elements to semantically link the image and its caption:

```html
<figure>
  <img
    src="images/dinosaur.jpg"
    alt="The head and torso of a dinosaur skeleton;
            it has a large head with long sharp teeth"
    width="400"
    height="341" />

  <figcaption>
    A T-Rex on display in the Manchester University Museum.
  </figcaption>
</figure>
```

This structure is more accessible as it clearly associates the caption with the image, benefiting users of screen readers. A `<figure>` doesn't have to be just an image; it can represent various types of content, providing essential information supporting the main text in a compact, easy-to-grasp way.

📷 **CSS background images**

The CSS `background-image` property, and the other `background-*` properties, are used to control background image placement. For example, to place a background image on every paragraph on a page, you could do this:

```html
p {
  background-image: url("images/dinosaur.jpg");
}
```

The resulting embedded image is arguably easier to position and control than HTML images. So why bother with HTML images? As hinted to above, CSS background images are for decoration only. If you just want to add something pretty to your page to enhance the visuals, this is fine. Though, such images have no semantic meaning at all. They can't have any text equivalents, are invisible to screen readers, and so on. This is where HTML images shine!

📷 **Other graphics on the web**

Beyond static images, the web provides advanced graphics capabilities:

1. **Canvas:**
   - `<canvas>` element allows drawing 2D graphics with JavaScript.
   - Useful for creating dynamic visuals and animations.

2. **SVG (Scalable Vector Graphics):**
   - Utilizes geometric shapes for scalable 2D graphics.
   - Ideal for clean, resizable images.

3. **WebGL:**
   - WebGL API facilitates 3D graphics using standard OpenGL ES.
   - Enables immersive 3D experiences on the web.

4. **HTML Audio and Video:**
   - Similar to `<img>`, `<video>` and `<audio>` embed media for playback control.
   - Enhances web pages with multimedia content.

5. **WebRTC (Real-Time Communications):**
   - Enables real-time audio/video streaming and data sharing.
   - Facilitates communication between browser clients.

These advanced graphics technologies offer dynamic, interactive, and multimedia-rich experiences on the web.


🎥 **Video and Audio content**

The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight, but they had security and accessibility problems. Now, we use native HTML elements like `<video>` and `<audio>` along with JavaScript for better security and compatibility.

🎥 **The <video> content**

To easily embed a video using the `<video>` element, we use the following simple example:

```html
<video src="videos/rabbit320.webm" controls>

  <p>Your browser doesn't support HTML video. Here is a <a href="rabbit320.webm">link to the video</a> instead.
  </p>
</video>
```

Key features:

- **src:** Specifies the path to the video file, similar to the `<img>` element.
- **controls:** Adds the browser's control interface for users to manage playback.
- **Fallback Content:** The paragraph provides an alternative for browsers that don't support `<video>`, offering a direct link to the video.

The embedded video looks like 

![Alt basic video](https://github.com/adityahongal/html/blob/main/images/basic%20video%20element.png)


🎥 **Using multiple source formats to improve compatibility**

There's a problem with the above example. It is possible that the video might not play for you, because different browsers support different video (and audio) formats. Fortunately, there are things you can do to help prevent this from being an issue.

**Contents of a media file**

Media files use container formats like MP3, MP4, and WebM, organizing audio and video tracks with metadata. Each track uses specific codecs for encoding. Browser support varies based on these formats:

- **WebM Container:**
  - Typically contains Vorbis/Opus audio with VP8/VP9 video.
  - Supported in all modern browsers.

- **MP4 Container:**
  - Often packages AAC/MP3 audio with H.264 video.
  - Supported in all modern browsers.

- **Ogg Container:**
  - Uses Vorbis audio and Theora video.
  - Best supported in Firefox and Chrome but largely superseded by WebM.

Special Cases:

- **FLAC Codec:**
  - Commonly stored in FLAC files without containers.

- **MP3 File:**
  - MPEG-1 Audio Layer III audio in an MPEG/MPEG-2 container.
  - Widely supported, even if browsers don't fully support MPEG media.

Audio players can directly play audio tracks like MP3 or Ogg files without containers.

**Media file support in browsers**

Codecs compress audio and video for efficient file sizes, but browsers support different codecs and container formats. For widespread compatibility, media files may need to be provided in multiple formats. Compatibility issues arise when a user's browser and a website don't share a common media format.

Choosing the right combination of codecs and containers for broad accessibility is complex. Consider factors like browser support, platforms, and devices. For guidance, refer to resources on choosing the appropriate container and codecs for your content and audience.

Additionally, mobile browsers might support formats not found in desktop versions, and both may offload media playback to external software. Media support depends on the user's installed software.

To ensure video playback across various platforms and browsers, use the following HTML structure:

```html
<video controls>
  <source src="rabbit320.mp4" type="video/mp4" />
  <source src="rabbit320.webm" type="video/webm" />
  <p>Your browser doesn't support this video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```

In this example:

- Separate `<source>` elements are used, pointing to different video sources (MP4 and WebM).
- The browser will play the first supported source based on available codecs.
- The optional `type` attribute in each `<source>` element specifies the MIME type, helping browsers skip unsupported formats.
- A fallback `<p>` element provides a link if the browser can't play the video.

This approach maximizes compatibility and ensures a better user experience.

**Other <video> features**

To enhance the display of an HTML video, consider additional features as shown in the example below:

```html
<video
  controls
  width="400"
  height="400"
  autoplay
  loop
  muted
  preload="auto"
  poster="images/poster.png">
  <source src="videos/rabbit320.mp4" type="video/mp4" />
  <source src="videos/rabbit320.webm" type="video/webm" />
  <p>Your browser doesn't support this video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```

The resulting will look like - 

![Alt video features](https://github.com/adityahongal/html/blob/main/images/video%20features.png)

Here are explanations of the additional features used in the video example:

- **width and height:**
  - Control the video size, maintaining the aspect ratio.
  - If the aspect ratio is not maintained, the video will fill the space horizontally, with unfilled space receiving a default background color.

- **autoplay:**
  - Initiates audio or video playback as soon as the page starts loading.
  - It's generally advised not to use autoplay to avoid user annoyance.

- **loop:**
  - Causes the video or audio to restart automatically when it finishes playing.
  - Use sparingly, as constant looping can be disruptive.

- **muted:**
  - Defaults the media to play with the sound turned off.

- **poster:**
  - Specifies the URL of an image displayed before video playback.
  - Useful for a splash screen or advertising screen.

- **preload:**
  - Controls buffering for large files.
  - Options include "none" (no buffering), "auto" (buffers the entire media file), and "metadata" (buffers only the metadata).

📢 **The <audio> element**

The `<audio>` element functions similarly to the `<video>` element, with a few distinctions. Here's an example:

```html
<audio controls>
  <source src="audio/viper.mp3" type="audio/mp3" />
  <source src="audio/viper.ogg" type="audio/ogg" />
  <p>Your browser doesn't support this audio file. Here is a <a href="viper.mp3">link to the audio</a> instead.</p>
</audio>
```

This produces something like the following in a browser:

![Alt Audio element](https://github.com/adityahongal/html/blob/main/images/audio%20element.png)


The `<audio>` element is more compact than a video player as it lacks a visual component. Here are the differences and similarities compared to the HTML video element:

**Differences:**
- `<audio>` doesn't support the `width/height` attributes, as there is no visual component.
- It also doesn't support the `poster` attribute, given the absence of a visual component.

**Similarities:**
- Otherwise, `<audio>` supports all the same features as `<video>`.
- It can use the `controls` attribute for playback controls.
- Multiple `<source>` elements can be used for different audio formats.
- Fallback content can be included for unsupported browsers using additional HTML content within the `<audio>` element.

🦯 **Displaying video text tracks**

In HTML video, you can provide accessibility features such as transcripts for people who may not be able to hear or understand the audio content. This is especially helpful for those with auditory impairments or in situations where playing audio is impractical. The WebVTT (Web Video Text Tracks) file format and the `<track>` element are used for this purpose.

**WebVTT Overview:**
- WebVTT is a format for text files containing strings of text along with metadata like the time in the video when each text string should be displayed.
- Cues are the text strings, and they come in different types, including subtitles for translations, captions for transcriptions of dialog, and timed descriptions for visually impaired users.

**Common Cues:**
1. **Subtitles:**
   - Provide translations of foreign material for those who don't understand the spoken words in the audio.

2. **Captions:**
   - Synchronized transcriptions of dialog or descriptions of significant sounds, aiding those who can't hear the audio.

3. **Timed Descriptions:**
   - Text spoken by the media player to describe important visuals for blind or visually impaired users.

By incorporating WebVTT and the `<track>` element, you can enhance the accessibility of your video content, making it more inclusive for a diverse audience.

A standard WebVTT file appears like this:

```plaintext
WEBVTT

1
00:00:22.230 --> 00:00:24.606
This is the first subtitle.

2
00:00:30.739 --> 00:00:34.074
This is the second.

...
```

To display this alongside HTML media playback, follow these steps:

1. Save it as a .vtt file in an appropriate location.
2. Link to the .vtt file using the `<track>` element. Place `<track>` within `<audio>` or `<video>`, after all `<source>` elements. Use the `kind` attribute to specify whether the cues are subtitles, captions, or descriptions. Additionally, use `srclang` to inform the browser of the language and add `label` to help users identify the language they are seeking.

Here's an example:

```html
<video controls>
  <source src="example.mp4" type="video/mp4" />
  <source src="example.webm" type="video/webm" />
  <track kind="subtitles" src="subtitles_es.vtt" srclang="es" label="Spanish" />
</video>
```

In this example, the WebVTT file "subtitles_es.vtt" contains Spanish subtitles for the video. The `<track>` element specifies the kind of content, the source file, language, and label for better identification.


## From object to iframe — other embedding technologies

At this stage, you've likely mastered the art of embedding content like images, videos, and audio in your web pages. Now, let's take a slight detour to explore elements that enable you to embed a diverse range of content types: the `<iframe>`, `<embed>`, and `<object>` elements. `<iframe>` is ideal for embedding entire web pages, while `<embed>` and `<object>` facilitate the embedding of external resources, such as PDF files.

These elements provide versatile options for enhancing the richness of your web content.

**Example of embedding a youtube video and google maps using <iframe>**

![Alt maps](https://github.com/adityahongal/html/blob/main/images/embedding%20maps.png)


**The <embed> and <object> elements**

The `<embed>` and `<object>` elements have a distinct purpose compared to `<iframe>`. They function as general-purpose embedding tools for external content, like PDFs. However, it's worth noting that their usage is less common. When dealing with PDFs, it's often more practical to provide a link to the document rather than embedding it directly into the page.

Historically, these elements were also employed for embedding content handled by browser plugins like Adobe Flash. However, due to the obsolescence of such technology, modern browsers no longer support it.

When dealing with the need to embed plugin content, you'll require essential information, summarized as follows:

| Element | URL of the Embedded Content | Accurate Media Type | Height and Width (in CSS pixels) | Parameters for the Plugin | Fallback HTML Content for Unavailable Resource |
| ------- | --------------------------- | -------------------- | -------------------------------- | ------------------------- | ----------------------------------------------- |
| `<embed>` | `src` attribute | `type` attribute | `height` and `width` attributes | Ad hoc attributes with names and values | Not supported ( `<noembed>` is obsolete) |
| `<object>` | `data` attribute | `type` attribute | `height` and `width` attributes | Single-tag `<param>` elements, contained within `<object>` | Contained within `<object>`, after `<param>` elements |

These elements, namely `<embed>` and `<object>`, offer a range of attributes and structures to embed and control plugin content while providing fallback options for scenarios where the resource is unavailable.

Let's look at an `<object>` example that embeds a PDF into a page

```html
<object data="mypdf.pdf" type="application/pdf" width="800" height="1200">
  <p>
    You don't have a PDF plugin, but you can
    <a href="mypdf.pdf">download the PDF file. </a>
  </p>
</object>
```


## Adding vector graphics to the web

Vector graphics are very useful in many circumstances — they have small file sizes and are highly scalable, so they don't pixelate when zoomed in or blown up to a large size.

On the web, you'll work with two types of images — raster images, and vector images:

**Raster images** are defined using a grid of pixels — a raster image file contains information showing exactly where each pixel is to be placed, and exactly what color it should be. Popular web raster formats include Bitmap (.bmp), PNG (.png), JPEG (.jpg), and GIF (.gif.)

**Vector images** are defined using algorithms — a vector image file contains shape and path definitions that the computer can use to work out what the image should look like when rendered on the screen. The `SVG` format allows us to create powerful vector graphics for use on the Web.

**what is SVG ?**

SVG (Scalable Vector Graphics) is an XML-based language used for describing vector images. Unlike HTML, SVG focuses on marking up graphics rather than content. It provides various elements to define shapes and apply effects to them. Basic shapes like <circle> and <rect>, along with advanced features such as <feColorMatrix>, <animate>, and <mask>, enable the creation of dynamic and scalable vector graphics.

Here's a basic example of SVG code creating a circle and a rectangle:

```html
<svg
  version="1.1"
  baseProfile="full"
  width="300"
  height="200"
  xmlns="http://www.w3.org/2000/svg">
  <rect width="100%" height="100%" fill="black" />
  <circle cx="150" cy="100" r="90" fill="blue" />
</svg>
```

While simple SVG can be hand-coded, complex images are best created using vector graphics editors like Inkscape or Illustrator. SVG offers advantages such as accessibility for text, styling/scripting flexibility with CSS and JavaScript, and SEO benefits.

However, SVG has its challenges:
- Complex SVGs may lead to larger file sizes and increased browser processing time.
- Creating intricate SVGs can be more challenging than raster images.
- Raster graphics may be preferred for complex precision images like photos.

Despite its complexities, SVG is a powerful tool for creating scalable and interactive vector graphics on the web.

**Adding SVG to your pages**

**The quick way: img element**

To embed an SVG using an <img> element, simply reference the SVG file in the src attribute. Include height and/or width attributes as needed, ensuring proper sizing. Here's an example:

```html
<img
  src="equilateral.svg"
  alt="triangle with all three sides equal"
  height="87"
  width="100" />
```

**Pros:**
- Familiar image syntax with a text equivalent provided in the alt attribute.
- Easy conversion into a hyperlink by nesting the <img> inside an <a> element.
- Browser caching can enhance loading times for pages using the same SVG image.

**Cons:**
- Limited manipulation with JavaScript.
- Inline CSS styles are required for CSS control; external stylesheets have no effect.
- CSS pseudoclasses (e.g., :focus) cannot be used for restyling.

**How to include SVG code inside your HTML**

To inline an SVG, open the SVG file in a text editor, copy the SVG code, and paste it directly into your HTML document. Ensure that the code snippet begins with an <svg> start tag and ends with an </svg> end tag. Here's a simple example:

```html
<svg width="300" height="200">
  <rect width="100%" height="100%" fill="green" />
</svg>
```

**Pros:**
- Inlining SVG saves an HTTP request, potentially reducing loading time.
- You can assign classes and ids to SVG elements and style them with CSS within the SVG or in the HTML document.
- Allows the use of CSS interactions (like :focus) and CSS animations on the SVG image.
- You can create hyperlinks by wrapping the SVG markup in an <a> element.

**Cons:**
- Suitable only if the SVG is used in a single place; duplication can lead to resource-intensive maintenance.
- Increases the size of your HTML file due to extra SVG code.
- Browser caching is not applicable to inline SVG, impacting loading times for subsequent pages.
- Fallbacks in a <foreignObject> element may be included, but browsers supporting SVG will still download any fallback images. Consider the extra overhead for supporting obsolescent browsers.

**How to embed an SVG with an iframe**

To embed an SVG document using an `<iframe`, you can use the following example:

```html
<iframe src="triangle.svg" width="500" height="500" sandbox>
  <img src="triangle.png" alt="Triangle with three unequal sides" />
</iframe>
```

**Cons:**
- iFrames have a fallback mechanism, but browsers only display the fallback if they lack support for iframes altogether.
- If the SVG and your current webpage have different origins, you cannot use JavaScript on your main webpage to manipulate the SVG.


## Responsive images

🌅 **Why responsive images ?**

The "art direction problem" and "resolution switching problem" are challenges associated with responsive web design, specifically concerning the handling of images. Let's break down each problem:

1. **Art Direction Problem:**
   
   - **Issue:** The art direction problem arises when you want to display different portions or variations of an image based on different screen sizes or orientations. For example, you might want to show a close-up of a product on larger screens and a full view on smaller screens.
   
   - **Challenge:** Traditional responsive images (using only the `srcset` attribute) might resize the entire image based on the viewport, but they don't allow you to select different regions or versions of the image for different contexts.

2. **Resolution Switching Problem:**
   
   - **Issue:** The resolution switching problem occurs when you want to provide images with different resolutions (pixel densities) for devices with varying screen capabilities (like Retina displays).
   
   - **Challenge:** Without proper handling, high-resolution images might be unnecessarily downloaded by devices with standard displays, leading to increased page load times and data usage.

🌅 **How do you create responsive images ?**

**Resolution switching: Different sizes**

Displaying identical image content at different sizes based on the device.

**Traditional Approach:**
```html
<img src="elva-fairy-800w.jpg" alt="Elva dressed as a fairy" />
```

**Improved Approach:**
```html
<img
  srcset="elva-fairy-480w.jpg 480w, elva-fairy-800w.jpg 800w"
  sizes="(max-width: 600px) 480px, 800px"
  src="elva-fairy-800w.jpg"
  alt="Elva dressed as a fairy"
/>
```

**Explanation:**
- `srcset`: Defines a set of images with sizes for the browser to choose from.
  - Each set includes an image filename and its intrinsic width.
  - Example: `elva-fairy-480w.jpg 480w, elva-fairy-800w.jpg 800w`

- `sizes`: Specifies media conditions and the corresponding slot size for optimal image selection.
  - Each condition is in the format `(media-condition) slot-size`.
  - Example: `(max-width: 600px) 480px, 800px`

**How it Works:**
1. Browser evaluates media conditions.
2. Chooses the first true condition.
3. Loads the image from `srcset` that matches or is larger than the chosen slot.
4. Optimizes bandwidth usage by selecting an image closest in size to the slot.

**Benefits:**
- Bandwidth savings, especially for pages with multiple images.
- Improved loading times for devices with varying screen sizes.

**Compatibility:**
- Supported by modern browsers; older browsers ignore these attributes and load the default image specified in `src`.

This technique provides responsive images that adapt to different screen sizes, optimizing user experience and bandwidth usage.

**Resolution switching: Same size, different resolutions**

Supporting multiple display resolutions while maintaining the same real-world size on the screen.

**Simplified Approach:**
```html
<img
  srcset="elva-fairy-320w.jpg, elva-fairy-480w.jpg 1.5x, elva-fairy-640w.jpg 2x"
  src="elva-fairy-640w.jpg"
  alt="Elva dressed as a fairy"
/>
```

**CSS Style:**
```css
img {
  width: 320px;
}
```

**Explanation:**
- `srcset`: Specifies a set of images with x-descriptors for different resolutions.
  - Example: `elva-fairy-320w.jpg, elva-fairy-480w.jpg 1.5x, elva-fairy-640w.jpg 2x`

**How it Works:**
1. Browser determines the display resolution.
2. Selects the most appropriate image from `srcset` based on x-descriptors.
3. Applies CSS styling to maintain a consistent width of 320 pixels on the screen.

**Benefits:**
- Simplified syntax without the need for `sizes`.
- Browser automatically selects the appropriate resolution image based on the device's display characteristics.

**Optimization:**
- Improved bandwidth usage by loading images closest in resolution to the display.

This approach allows for responsive images with varying resolutions, adapting to different devices while maintaining a consistent real-world size on the screen.

🌅 **Art Direction**

**Art Direction Problem:**
Adjusting displayed images to suit different display sizes, addressing issues like cropping or loss of detail on smaller screens.

**Solution: `<picture>` Element**
```html
<picture>
  <source media="(max-width: 799px)" srcset="elva-480w-close-portrait.jpg" />
  <source media="(min-width: 800px)" srcset="elva-800w.jpg" />
  <img src="elva-800w.jpg" alt="Chris holding his daughter Elva" />
</picture>
```

**Explanation:**
- `<picture>`: Wrapper for multiple `<source>` elements and a default `<img>`.
- `<source>`: Contains media condition and srcset for different scenarios.
  - Example: `(max-width: 799px)` — If viewport width is 799px or less.
  - Example: `(min-width: 800px)` — If viewport width is 800px or more.
  - `srcset`: Path to the image to display for the given condition.

**How it Works:**
1. Browser evaluates media conditions and selects the first true condition.
2. Chooses the corresponding image specified in the selected `<source>` element.
3. Renders the selected image.

**Benefits:**
- Allows tailored image selection based on viewport conditions.
- Addresses art direction problems by providing different images for different scenarios.
- Provides a default `<img>` for unsupported conditions or browsers.

**Usage Tips:**
- Use when you need specific images for different display scenarios.
- Always include a default `<img>` for unsupported conditions.

This approach enhances image presentation, offering flexibility to display images optimized for different screen sizes and addressing art direction concerns.


## Mozilla Splash Page example 

![Alt mozillasplashpage](https://github.com/adityahongal/html/blob/main/images/mozilla%20splash%20page.png)


## HTML tables

🪑 **What is a table ?**

HTML provides a way to structure and present tabular data on the web. Tables are a structured set of data with rows and columns, allowing easy lookup of values indicating connections between different types of data. They have been used in human society for a long time and are commonly employed to represent information such as a person's age, days of the week, or a timetable for a local swimming pool.

🪑 **When should you NOT use HTML tables**

HTML tables should be used for tabular data, not for page layout. In the past, tables were often misused to structure web page layouts due to poor CSS support across browsers. However, using tables for layout is discouraged for several reasons:

1. **Reduced Accessibility:** Layout tables can decrease accessibility for visually impaired users. Screen readers, which are used by blind individuals, interpret HTML tags and provide information to users. Tables used for layout can create confusing output for screen readers.

2. **Tag Soup:** Table layouts involve more complex markup compared to proper CSS layout techniques. This complexity can lead to code that is harder to write, maintain, and debug.

3. **Non-Responsive:** Tables are not inherently responsive. Unlike proper layout containers (e.g., <header>, <section>, <article>, or <div>), which default to 100% width, tables are sized based on their content. Additional measures are required to make table layouts work effectively across various devices.

In summary, using tables for layout instead of CSS layout techniques is not recommended due to issues related to accessibility, code complexity, and responsiveness.

🪑 **Creating a table**

Let's create a basic table structure with multiple rows.

```html
<!DOCTYPE html>
<html lang="en-us">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>Simple Table Example</title>
    <link href="minimal-table.css" rel="stylesheet" type="text/css">
</head>
<body>
    <h1>Simple Table Example</h1>

    <table>
        <tr>
            <td>Hi, I'm your first cell.</td>
            <td>I'm your second cell.</td>
            <td>I'm your third cell.</td>
            <td>I'm your fourth cell.</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
            <td>Row 2, Cell 3</td>
            <td>Row 2, Cell 4</td>
        </tr>
        <!-- Add more rows as needed -->
    </table>

</body>
</html>
```

In this example, I've added a second row with different cell contents. You can continue to add more rows following the same structure with `<tr>` for each row and `<td>` for each cell. Each `<tr>` element represents a new row, and the `<td>` elements inside it represent the cells in that row.

![Alt simpletable](https://github.com/adityahongal/html/blob/main/images/simple%20table.png)


🪑 **Adding headers with <th> element**

Certainly! Let's delve into the theory of adding headers to a table for better clarity:

1. **Introduction to Table Headers (`<th>`):**
   - In HTML tables, headers are used to label and describe the content of rows and columns.
   - The `<th>` (table header) element is employed to create header cells in a table.

2. **Placement of Header Cells:**
   - Header cells can be placed at the beginning of a row or at the start of a column.
   - They are often used in the first row (`<tr>`) to label columns, and in the first column to label rows.

3. **Benefits of Table Headers:**
   - Headers make it clear what type of data is present in each column or row, improving readability.
   - They provide context and help users understand the meaning of the data.

4. **Example Usage:**
   - The `<th>` element is used similarly to `<td>`, but it signifies a header cell.

     ```html
     <table>
       <tr>
         <th>&nbsp;</th>
         <th>Knocky</th>
         <th>Flor</th>
         <th>Ella</th>
         <th>Juan</th>
       </tr>
       <!-- ... More rows ... -->
     </table>
     ```

In summary, the inclusion of `<th>` elements in a table enhances the structure and usability of the table by providing clear labels for columns and rows. It's a best practice for creating well-organized and easily understandable tabular data.

🪑 **Row span and Column span**

Certainly! Let's break down the theory of allowing cells to span multiple rows and columns using the `colspan` and `rowspan` attributes in HTML tables:

1. **Introduction to `colspan` and `rowspan`:**
   - In HTML tables, the `colspan` attribute is used to make a table cell span multiple columns.
   - The `rowspan` attribute is used to make a table cell span multiple rows.

2. **Use Cases for Spanning Cells:**
   - Spanning cells is useful when you want to merge cells either horizontally or vertically to create a more visually organized and structured table.

3. **Applying `colspan` Example:**
   - To make a cell span multiple columns, add the `colspan` attribute with the desired number of columns to the `<th>` or `<td>` element.

     ```html
     <th colspan="2">Animals</th>
     ```

4. **Applying `rowspan` Example:**
   - To make a cell span multiple rows, add the `rowspan` attribute with the desired number of rows to the `<th>` or `<td>` element.

     ```html
     <th rowspan="2">Horse</th>
     ```

In summary, `colspan` and `rowspan` are valuable attributes for creating more complex and visually appealing tables by allowing cells to extend across multiple columns or rows. They enhance the layout and organization of tabular data in HTML.

Example of simple Animal table

![Alt animal table](https://github.com/adityahongal/html/blob/main/images/simple%20animal%20table.png)



### 🪑Styling Columns Without `<col>`

In HTML tables, you can apply styling information to an entire column using `<col>` and `<colgroup>` elements. This is beneficial when you want to avoid repeating styling for every `<td>` or `<th>` in the column.

#### Example Without `<col>`

```html
<table>
  <tr>
    <th>Data 1</th>
    <th style="background-color: yellow">Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td style="background-color: yellow">Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td style="background-color: yellow">Jazz</td>
  </tr>
</table>
```

#### Styling with `<col>`

Instead of repeating styling information, use `<col>` inside a `<colgroup>` container just below the opening `<table>` tag.

```html
<table>
  <colgroup>
    <col />
    <col style="background-color: yellow" />
  </colgroup>
  <tr>
    <th>Data 1</th>
    <th>Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td>Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td>Jazz</td>
  </tr>
</table>
```

For styling both columns, use a single `<col>` element with a `span` attribute:

```html
<colgroup>
  <col style="background-color: yellow" span="2" />
</colgroup>
```

The `span` attribute specifies the number of columns to which the styling applies.

### Simple example for a time table using rowspan and colspan

![Alt timetable](https://github.com/adityahongal/html/blob/main/images/simple%20timetable.png)

##  HTML tables advanced features

🪑 **Adding a caption to your table with <caption>**

You can give your table a caption by putting it inside a `<caption>` element and nesting that inside the `<table>` element. You should put it just below the opening `<table>` tag.

```html
<table>
  <caption>
    Dinosaurs in the Jurassic period
  </caption>

  …
</table>
```

🪑 **Adding structure with <thead>, <tfoot>, and <tbody>**

When dealing with more complex table structures, it's beneficial to provide structural definition using `<thead>`, `<tfoot>`, and `<tbody>`. While these elements don't directly enhance accessibility, they serve as valuable hooks for styling and layout in CSS. They can be particularly useful for scenarios like repeating the header and footer on printed pages or controlling the display of the table body.

Here's how to use them:

- **`<thead>` (Table Header):**
  - Wrap the part of the table that serves as the header.
  - Usually includes the first row with column headings.
  - If you're using `<col>/<colgroup>` elements, place the `<thead>` just below those.

- **`<tfoot>` (Table Footer):**
  - Wrap the part of the table that represents the footer.
  - This might include a final row with items summed from previous rows.
  - Can be placed at the bottom of the table or just below the table header.

- **`<tbody>` (Table Body):**
  - Wrap the other parts of the table content that aren't in the header or footer.
  - Appears below the table header or footer, depending on your chosen structure.

**Example:**

```html
<table>
  <colgroup>
    <!-- Define column styling if needed -->
    <col style="width: 30%;" />
    <col style="width: 40%;" />
    <col style="width: 30%;" />
  </colgroup>
  
  <thead>
    <tr>
      <th>Name</th>
      <th>Occupation</th>
      <th>Location</th>
    </tr>
  </thead>
  
  <tfoot>
    <tr>
      <td>Total</td>
      <td></td>
      <td></td>
    </tr>
  </tfoot>
  
  <tbody>
    <tr>
      <td>John Doe</td>
      <td>Developer</td>
      <td>New York</td>
    </tr>
    <!-- More rows... -->
  </tbody>
</table>
```

By structuring your table with these elements, you provide clear hooks for styling and layout adjustments.

🪑 **Nesting tables**

While it's possible to nest a table inside another one, it's generally not advised due to potential confusion and reduced accessibility. In most cases, adding extra cells, rows, or columns to the existing table is a more straightforward approach. However, there are scenarios, like content importation from other sources, where nesting might be necessary.

Here's a simple example of a nested table:

```html
<table id="table1">
  <tr>
    <th>title1</th>
    <th>title2</th>
    <th>title3</th>
  </tr>
  <tr>
    <td id="nested">
      <table id="table2">
        <tr>
          <td>cell1</td>
          <td>cell2</td>
          <td>cell3</td>
        </tr>
      </table>
    </td>
    <td>cell2</td>
    <td>cell3</td>
  </tr>
  <tr>
    <td>cell4</td>
    <td>cell5</td>
    <td>cell6</td>
  </tr>
</table>
```

In this example, `table2` is nested inside a cell (`<td>` with `id="nested"`) of `table1`. While this structure is valid, use it judiciously, and favor simplicity for better markup clarity and accessibility.

