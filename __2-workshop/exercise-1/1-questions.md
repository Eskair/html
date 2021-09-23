# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [ false] `<div><span>hello</div></span>`

b) [false ]

```html
<ul>
<li>one</li>
</ol>
```

c) [false ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about the screenreaer?

A screen reader is a piece of software that uses technology to convert text to speech. They allow people who blind or visually impaired, like me, to use computers and mobile phones. Screen readers read everything that is on the device screen out loud in synthesised speech.

Screen reader users tend to navigate websites using the keyboard or touch gestures on mobile.
As a screen reader user, I need websites to be optimised for keyboard-only navigation. Often, I’m unable to navigate using headings and other elements on the page. Simply because the developer has not considered keyboard-only users.
And building websites to accessibility standards is not just the right thing to do. There are many other benefits to designing accessible apps and websites.

https://bighack.org/message-to-web-developers-from-a-screen-reader-user/

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
The <img> tag is used to insert an image into a document.
<picture>

<source>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<a>: The Anchor element. The <a> HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address. Content within each <a> should indicate the link's destination.

c) You want to sell designer hats. You need to receive orders from the user.

<ul> <li>Item A</li> <li>Item B</li> <li>Item C</li> </ul>;
<ol> <li>Step 1</li> <li>Step 2</li> <li>Step 3</li> </ol>
<dl><dt></dt><dd></dd></dl>

Read more: https://html.com/lists/#ixzz77FQ63xTf

Read more: https://html.com/lists/#ixzz77FQ1m7FB

## Q4 - Can a `button`be a child of a `button`? Explain your reasoning

It is not valid to put a <button> inside a <button> element.
In the W3C recomendation for the button element you can read:

Content model:
Phrasing content, but there must be no interactive content descendant.

[source: w3.org (emphasis mine)]

Interactive content includes:

a
audio (if the controls attribute is present)
button
embed
iframe
img (if the usemap attribute is present)
input (if the type attribute is not in the hidden state)
keygen
label
object (if the usemap attribute is present)
select
textarea
video (if the controls attribute is present)

## Q5 - What is the most generic tag you can use?

It wasn't surprising to find that the link tag is the most used tag. In fact it represents almost 25% of all tags on the web.

## Q6 - What do the following achronyms stand for?

a) `a` The <a> tag defines a hyperlink, which is used to link from one page to another.

b) `ol` The <ol> tag defines an ordered list. An ordered list can be numerical or alphabetical.

c) `ul`The <ul> tag defines an unordered (bulleted) list.

Use the <ul> tag together with the <li> tag to create unordered lists.

d) `li` he <li> tag is used inside ordered lists(<ol>), unordered lists (<ul>), and in menu lists (<menu>).

e) `tr` The <tr> tag defines a row in an HTML table.

A <tr> element contains one or more <th> or <td> elements.

f) `th` The <th> tag defines a header cell in an HTML table.

g) `td` The <td> tag defines a standard data cell in an HTML table.

## Q7 - Usually, `td` elements are children of what kind of elements?

<table><tr>

## Q8 - What is the difference between td and th?

The <td> tag defines a standard data cell in an HTML table.
The <th> tag defines a header cell in an HTML table.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

It is true that the `h1` element is very often bigger than the other heading elements. but hi and h3 for title not for text .

## Q10 - In which situation can you use self closing tags?

The br tag inserts a line break (not a paragraph break). This tag has no content, so it is self closing.

## Q11 - What is autofilling and why is it important?

Autofill is a function in some computer applications or programs, typically those containing forms, which prefills a field automatically and can save a user time.
The autocomplete attribute specifies whether or not an input field should have autocomplete enabled. Autocomplete allows the browser to predict the value. When a user starts to type in a field, the browser should display options to fill in the field, based on earlier typed values.
It's understandable why web developers haven't paid much attention to autofill. When you're filling out forms with test data on a regular basis, autofill tends to get in the way. But autofill is an important feature for our users. Google has found that “users complete forms up to 30% faster” when using autofill.

## Q12 - Which attributes are always present in an img element?

The src and alt attributes are required for the document to be valid.

## Q13 - Which attribute is always present for an anchor tag?

The <a> HTML element (or anchor element), with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address. Content within each <a> should indicate the link's destination.
