# Semantic HTML: Best Practices for

# Accessibility and SEO

## About the Project

This project focuses on building a solid foundation in Semantic HTML while
emphasizing accessibility , SEO optimization , and the implementation of ARIA roles for enhanced
usability. Through incremental tasks, learners will structure and enhance a web page to make it not only
visually structured but also optimized for screen readers and search engines. By the end of the project,
learners will understand the importance of semantic elements and accessibility features in modern web
development.

## Learning Objectives
Master Semantic HTML : Learn to structure web pages using semantic elements such as header, main, article, section, and <footer> for better content organization and accessibility. Optimize for SEO : Understand how to improve the visibility of your webpage through appropriate usage of meta tags and proper document structure. Enhance Accessibility : Implement ARIA roles and attributes to make web forms and content more accessible to users with disabilities. Understand Form Design Best Practices : Learn to create accessible and user-friendly forms using modern HTML techniques. Adopt Incremental Development : Practice progressive enhancement by building upon the foundation of each previous task.

## Requirements
1. A working understanding of **HTML**.
2. Familiarity with semantic HTML elements and their purpose.
3. Basic knowledge of **SEO** and its importance in web development.
4. Awareness of **web accessibility standards** , including ARIA roles and attributes.

## Tasks
### 0. Creating a Structured HTML Document Using Semantic Elements mandatory

Objective : Practice structuring a simple HTML document using semantic elements.
Create your first HTML file 0-index.html with:
inside the html tag, create the head and body tags (empty) in this order
Inside the body tag:
Add a header that contains a nav with at least three links.
Create a main section that contains an article, and inside the article, add a h1 tag for the title
and a section for the content.
Add a footer with some copyright information “@copyright ”
Remember the structure of a html files starts with a doctype
Check submission

### 1. Enhancing HTML Document with Meta Tags and Title for SEO and Accessibility mandatory

Objective : To enhance the structure of the HTML document by adding meta tags for improved SEO,
accessibility, and responsiveness, while properly defining the document’s character set and title.
Copy the content of 0-index. html into1-index. Html Inside theheadtag:
Add a meta tag inside the head
Add the charset attribute with the value utf-
Add 4 more meta tags with the following:
Tag 1: name=description content=A blog post about semantic HTML and accessibility
practises`
Tag 2: name=keywords content=`HTML, Semantic, Accessibility, Blog,SEO
Tag 3:- name=author content=
Tag 4:- name=viewport content=width=device-width, initial-scale=1.
Add a title tag with the following message: Semantic Html Blog Post
Check submission
Repo:
GitHub repository: alx-intermediate-frontend
Directory: 0x00-semantic_html
File: 0-index.html
Repo:
GitHub repository: alx-intermediate-frontend
Directory: 0x00-semantic_html
File: 1-index.html

### 2. Creating a Blog Post Layout Using Semantic HTML Elements mandatory

**Objective** : Apply semantic elements to create a blog post layout

Copy the content of file 1-index.html into 2-index.html
Inside the header tag
Add h1 tag with the content My Blog
Add a nav tag
Inside the nav tag, create a ul tag with 3 li tag referencing the following respectively:
Home
About
Contact
Inside the article tag in the main tag:
Add a header tag with the a h2 tag text: understanding Semantic Html
Add a p tag with the text: Published on <time datetime=”2024-09-10”> September 10
Inside the section tag, add a:
H3 tag with the text: introduction
P tag with the text: Semantic HTML helps improve the accessibility and SEO of your website.
In this post, we’ll explore its benefits and how to implement it. Ensure you close the tags
Below the previous section tag, Add another section tag:(this is after closing
the section tag in the previous tag)
In the newly created section tag, add:
h3a tg with the text: Main Content
P tag with the text:
### Using elements like
<code>&lt;article&gt;</code>
<code>&lt;section&gt;</code>
<code>&lt;header&gt;</code>
ensures that both users and search engines can better understand the structure and content of a
webpage.`
figure with:
img tag with an src=””, alt attribute with text: example
Figcaption with the text: An illustration of semantic HTML elements
Add a third section tag. Inside it add:
H3 tag with the text: Conclusion
p tag with the text: By adopting semantic HTML, you enhance your site's accessibility,
improve SEO, and make the content easier to navigate.
Add a footer tag. Inside it, add: *]
*p tag with the text: written by <name>

p tag with the text: Published on 2024-09-
ps : All the above changes have been made in the article tag inside the main tag


Remember to close each tag you create

Check submission
### 3. Enhancing Form Accessibility with ARIA Roles and Attributes mandatory

**Objective** : Implement ARIA roles to improve accessibility in a form

Copy the content of 2-index.html into 3-index.html
Inside the main element, add a new section tag
In the section tag add:

Form tag with the following attributes:
action=”#”
method=”POST”
aria-labelledby=”form-title”
role=”form”
Inside the form tag, add:
**A div. Inside it add:**

label tag with a for attribute:name
input tag with the following attributes:
type:- “text”
id : “name”
name: “name”
aria-required: “true”
**A `div tag inside it add:**

label tag with a or attribute:name
Input tag with the same attributes as the previous. Just replace “name” text with “email”
**A div tag inside it add:**

button tag with the following attributes:
type: “submit”
*aria-label: “Submit the form”

**A div tag with the following attributes:**

aria-live: “polite”
role: “alert”
Ps as always remember to close tags

**Repo:**

GitHub repository: alx-intermediate-frontend
Directory: 0x00-semantic_html
File: 2-index.html
**Repo:**


Check submission
### 4. Manual Review mandatory

GitHub repository: alx-intermediate-frontend
Directory: 0x00-semantic_html
File: 3-index.html
**Repo:**

GitHub repository: alx-intermediate-frontend
Directory: 0x00-semantic_html

