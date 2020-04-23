---
marp: true
---

# Basics of website development

## **by : Mohammadali Azani**

---

# HTML5(Hyper Text Markup Language)

* \<DOCTYPE html> ==> (For html5) All HTML documents must start with a <!DOCTYPE> declaration. The declaration is not an HTML tag. It is an "information" to the browser about what document type to expect.

In HTML 5, the declaration is simple

* \<html> ==> This is for open a tag in html

* \</html> ==> We can close a tag by using </TAG-NAME>

* \<p> ==> This is a tag

* \<p> Paragraph </p> ==> This is an element

---

# Tags and elements names

* \<h1> - \<h6> ==> we have 6 header tag size and h1 is the biggest one and it will go on to h6 that is the smallest header size

* \<p> ==> paragraph tag

* \<b> ==> bold tag (expired)

* \<strong> ==> instead of bold (b tag) for semantic html

* \<i> ==> italic tag (expired)

* \<em> ==> emphasis instead of italic (i tag) for semantic html

* \<mark> ==> highlight a text

* \<!-- Comment text --> ==> comment tag and it's not showing in the browser

---

* \<ul> ==> unordered list tah

* \<ol> ==> ordered list tag

* \<li> ==> list item tag

* This is how to make list:
  * [\<ol> | \<ul>]
            \<li>apple</li>
            \<li>orange</li>
            \<li>banana</li>
            \<li>pear</li>
        [\</ol> | \</ul>]

---

# Self closing tags

* \<br> ==> break line tag

* \<hr> ==> horizontal line tag

* \<img src="Source file path or url" alt="alternative text if image doesn't appear" height="hight number(32)" width="width number(32)"> ==> to insert image to our webpage

---

# Anchor tag

* The \<a> tag defines a hyperlink, which is used to link from one page to another

* Example:  \<a href="https://www.w3schools.com">Visit W3Schools.com!</a>

* By default index.html is the main file(first html file or homepage)

---

* \<form> ==> form tag to create form

* \<input type="TYPE"> ==> to get input in our form and it's self closing tag

* input types: text, password, submit, reset, checkbox, color, date, email, file, hidden, image, radio, url, search , ...

---

# Form method

* we have two methods for giving the user information in forms
  * GET ==> in url
  * POST ==> To backend webserver
  
* \<div> ==> division tag to divide content and wrap the content
  
* \<span> ==> span tag to divide content and wrap the content but it's an inline element

* \<pre> ==> preserve spaces and blank lines

* \<p style="color:blue;">This is a paragraph with css style </p> ==> use css(color) in html

* \<p style="font-family:courier;">This is a paragraph with css style </p> ==> use css(font) in html

* \<p style="text-align:center;">This is a paragraph with css style </p> ==> use css(align) in html

* \<p style="font-size:50px;">This is a paragraph with css style </p> ==> use css(font-size) in html

* \<p style="background-color:blue;">This is a paragraph with css style </p> ==> use css(bg-color) in html

* \<sub> ==> subscript

* \<del> ==> delete tag

* \<q> ==> quotation tag

* \<blockquote> ==> section that is quoted from another source(Browsers usually indent)

* \<bdo dir="rtl">This is test.</bdo> ==> Bi-Directional Override

* \<abbr title="Mr rtb">Who</abbr> ==> abbreviation tag