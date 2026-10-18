# TasteOfPakistan_Restuarant_Homepage
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) <br>
![Layouts](https://img.shields.io/badge/Layout_Paradigms-Fixed%20|%20Fluid%20|%20Adaptive%20|%20Responsive-orange?style=for-the-badge) <br>
![Dependencies](https://img.shields.io/badge/Dependencies-Zero%20Frameworks%20(Vanilla)-green?style=for-the-badge) <br>
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge) <br>

This project was made to experiment with and better understand four different web layout approaches: 

● **Fixed** <br>
● **Fluid** <br>
● **Adaptive** <br>
● **Responsive** <br>

I have created a HTML file showcasing a fictional restaurant “Taste of Pakistan”. The website contains four main containers using `<div>`, for the header, navigation bar, content page containing a general introduction to the restaurant and the specials menu and lastly the footer.

## **💻Technical Specification**

● **Markup Language:** HTML5 (Semantic Structure) <br>
● **Styling:** Pure Vanilla CSS3 (No external CSS libraries or frameworks) <br>
● **Design Paradigms:** Fixed Layout, Fluid (Liquid) Layout, Adaptive Layout, Responsive Layout <br>
● **CSS Techniques:** CSS Grid, Flexbox, Floats & Clears, Media Queries (`@media`), CSS Box Sizing (`border-box`), Dynamic Math (`calc()`) <br>


## 🏗️ Architectural Layout Comparison 

### 1. Fixed Layout
A fixed layout is created using absolute sizing for each container, this includes both the root containers as well as all the inner content blocks. This layout provided designers with layout predictability, and allowed designers to control placements of elements to the exact pixel.

**.page-container {width: 980px;margin: 0 auto;}** <br>
**.menu-card { width: 290px; height: 150px;.......**

### 2. Fluid Layout
A fluid layout is constructed using relative percentage units for width, margins and padding. For the root container sizing is relative to the browser width and for inner containers sizing is relative to the respective root containers. From a viewpoint perspective elements scale proportionally to the size of the browser window. If the browser is wider elements tend to stretch to take up more space, consequentially if the browser window is narrowed items compress to fit onto the screen.

### 3. Adaptive Layout
The adaptive layout uses CSS Media Queries to load pre-made layouts according to the user's width. The layout remains static until the browser's width crosses a specific predefined width known as a breakpoint.

### 4. Responsive Layout
A responsive Layout combines the percentage scaling of the fluid layout, as well as the media queries adjustments of the adaptive layout resulting in a webpage with elements that scale fluidly and a layout that adjusts at specifics thresholds.This allows for dynamic scaling, pages that scale smoothly between breakpoints. 

● Header content stacks vertically on smaller screens <br>
● Three column menu grids wrap into a single column layout

## ⚡Installation and Layout Test Guide

● **Step 1:** Clone the Respistory

● **Step 2:** Open the TasteOfPakistan.html file

● **Step 3:** Simply change the stylesheet href (mentioned in the head) to the desired layout (default responsive)

<img width="641" height="116" alt="image" src="https://github.com/user-attachments/assets/85fe0a95-ce60-4704-bea9-95451662f8a1" />

--Option 1--
`<link rel="stylesheet" href="restaurant-fixed.css">`

--Option 2--
`<link rel="stylesheet" href="restaurant-fluid.css">`

--Option 3--
`<link rel="stylesheet" href="restaurant-adaptive.css">`

--Option 4--
`<link rel="stylesheet" href="restaurant-responsive.css">`

## Website Preview

<img width="1368" height="886" alt="image" src="https://github.com/user-attachments/assets/9f8468ac-87e5-41aa-94bc-0e48cded207e" />

<img width="1369" height="886" alt="image" src="https://github.com/user-attachments/assets/494c4187-c218-42bd-8954-25ddce37e3ad" />








