# HTML_Advanced

### Concepts
*For this project, we expect you to look at these concepts:*
- [Some pointers about HTML](https://intranet.hbtn.io/concepts/834)
- [HTML - elements of a web page](https://intranet.hbtn.io/concepts/835)
- [HTML Foundations](https://intranet.hbtn.io/concepts/836)
- [HTML - Semantic sectioning elements](https://intranet.hbtn.io/concepts/837)
- [HTML Semantic Elements](https://intranet.hbtn.io/concepts/838)
- [HTML Validation](https://intranet.hbtn.io/concepts/839)

---

![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/e8a269aa-8a1c-4881-9272-bac570024e81)
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/e8476ba3-a943-4fb5-ba81-3b4417973d5e)

## Resources:books:
Read or watch:
* [Learn to Code HTML & CSS](https://learn.shayhowe.com/html-css/)
* [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
* [MDN](https://developer.mozilla.org/en-US/)

---
## Learning Objectives:bulb:
At the end of this project, you are expected to be able to [explain to anyone](https://fs.blog/feynman-learning-technique/), **without the help of Google**:

### General
- What is HTML
- How to create an HTML page from a wireframe
- What is a markup language
- What is the DOM
- What is an element / tag
- What is an attribute
- What the purpose of each HTML tag

---

## Requirements
### General
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project is mandatory
- You are **not allowed** to install, import or use external libraries. This website must be build with only HTML/CSS/JavaScript. No NodeJS, React, VueJS, Bootstrap, etc.
- Your code should be W3C compliant and validate with [W3C-Validator](https://github.com/hs-hq/W3C-Validator)

---
## Tasks

### [0. README and objectives!](./README.md)
In this and coming projects, you will implement from scratch a webpage from a designer file.

For this first project, you will focus on the HTML structure only - no CSS, no style - just pure HTML semantic.

This designer file will be available on [Figma](https://www.figma.com/files/recent?fuid=1111140545816856971) - feel free to create an account to access the final result here:

  - [Page in Figma](https://www.figma.com/file/XrEAsu1vQj5fhVaNG38d2W/Homepage?type=design&t=uXdOp7qwKRsai8CZ-0)
  - fig file
And “Duplicate to your Drafts” to have access to all design details.
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/b1f0fe12-c48d-44f8-ba66-32af3414e670)
Important notes with Figma:

  - if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://www.fontsquirrel.com/fonts/source-sans-pro) and [Spin-Cycle-OT](https://www.fontsquirrel.com/fonts/Spin-Cycle-OT)
  - some values are in float - feel free to round them
For this task, please write an amazing `README.md`


### [1. Header](./index.html)
Let’s start by the top: **the header**

Here the wireframe of it:
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/964adea6-b870-454f-85a8-3dff89d0e696)
  - Create the HTML skeleton (`html`, `head`, `body`, etc.)
  - In the body, add an `header` tag
  - Inside this `header`:
    - Add a link element with an image inside
    - Add a block of 3 link elements



### [2. Banner](./index.html)
Now, the banner under the `header`:
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/b2cd56e8-f5fc-4ea6-a769-d99e3bbfc7d7)
Under the `header`, add a `main` element with inside a `section` element.

In this `section` element, add:

  - A block with inside:
    - A heading tag (don’t forget to use the correct heading value)
    - A text element
    - A button tag
  - Another block with inside:
    - Another heading tag (same, be careful about which one you are using)
    - A block containing 4 blocks - each block with inside:
      - An image
      - A heading tag
      - A text


### [3. Quote](./index.html)
Under the banner, we will add the quote block:
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/397ce962-0e92-41ce-ab86-2ffc9d2a251a)
The quote section is inside the `main`:

  - Create a new `section` for the quote
  - Inside, add a block containing:
    - An image
    - Another block with inside:
      - A quote tag
      - An author quote
      - A text


### [4. Videos](./index.html)
Let’s now add the videos list:
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/4a977b53-0e45-466e-9853-7aadabcce1b3)
New `section` with inside:

  - A heading tag
  - A block containing the 4 video block - each of them are composed with:
    - An image
    - A heading
    - A text
    - A block for the author:
      - A image
      - A heading
    - A block for the rating:
      - A block of images (one star = one image)
      - A text


### [5. Membership](./index.html)
Membership section is similar as the videos list:
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/27bf093d-32cf-4b81-af0b-ae1cb0396cf1)
After the videos list section, add a new `section` containing:

  - A heading
  - A block with inside 4 block item - each block defined with:
    - An image
    - A heading
    - A text
  - A button


### [6. FAQ](./index.html)
The FAQ section is ending the page before the footer:
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/51e2160b-4426-45be-9d09-04719b1c8107)
Add a `section` for the FAQ with inside:

  - A block that contains 2 “row block”
  - Each “row block” contains 2 “item block”
  - Each “item block” is composed of:
    - A heading
    - A text


### [7. Footer](./index.html)
And… the footer!
![image](https://github.com/FosterClark48/holbertonschool-web-development/assets/105602291/3f576a09-5d37-485e-a807-44b4d320f558)
After the last `section`, outside of the `main`, add a `footer`:

  - A global block (used later for centering the footer content), inside this block:
    - A “row block” with:
      - An image
      - A block with inside:
        - Images with link
    - A text
And… that’s it for the moment - the result should not be shiny, don’t worry, CSS is coming…


---

## Author
- **Foster Clark** - [fozc](https://github.com/FosterClark48) :octocat:
