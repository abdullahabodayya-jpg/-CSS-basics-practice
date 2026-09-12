# CSS Practice - Position & Layout Lab

A practical CSS project created to practice positioning, layout, spacing, borders, shadows, z-index, and image positioning through multiple interactive pages.

The project ends with a complete **Online FoodShop** webpage built using HTML and CSS.

---

## Project Overview

This project is a collection of CSS exercises designed to turn CSS concepts into practical examples.

Instead of practicing every concept in a single file, each exercise is organized into its own page. The pages are connected together through navigation, making it easy to move between the different exercises.

The main focus of the project is understanding how elements behave when different CSS positioning and layout techniques are applied.

The project also includes an advanced exercise and a final website project to apply the concepts in a more realistic webpage.

---

## What This Project Covers

The project focuses mainly on:

- CSS Position
- Static Positioning
- Relative Positioning
- Absolute Positioning
- Fixed Positioning
- Sticky Positioning
- Z-index
- Margin
- Padding
- Borders
- Border Styles
- Box Shadow
- Multiple Box Shadows
- Image Positioning
- Overlapping Elements
- Basic Layout
- HTML Navigation
- Multi-page Website Structure

---

# Project Pages

## Page 1 - Position

This page introduces the main CSS positioning types used in the project.

It demonstrates:

- `position: relative`
- `position: absolute`
- `position: fixed`
- `z-index`

The page shows how different positioning methods affect the location of elements and how elements can overlap each other.

### Main Concept

The goal of this page is to understand the difference between elements that remain in the normal document flow and elements that are removed from it.

---

## Page 2 - Z-index

This page focuses on the `z-index` property.

Several elements are placed on top of each other to demonstrate how CSS controls which element appears in front of another.

### Concepts Practiced

- `position`
- `z-index`
- Element stacking
- Overlapping elements

Higher `z-index` values are used to place elements above elements with lower stacking levels.

---

## Page 3 - Absolute Position

This page focuses specifically on absolute positioning.

The exercise demonstrates how an absolutely positioned element can be placed inside a positioned parent element.

### Concepts Practiced

- `position: absolute`
- `position: relative`
- `top`
- `left`
- Parent-child positioning relationship

A positioned parent can be used as the reference point for an absolutely positioned child.

---

## Page 4 - Relative vs Static

This page demonstrates the difference between:

```css
position: static;
and:

position: relative;

Multiple boxes are arranged using inline-block to practice layout without relying on CSS Grid.

Concepts Practiced
Static positioning
Relative positioning
top
left
inline-block
Margin
Basic horizontal layout

The exercise helps demonstrate that relative keeps an element in its original space while allowing it to be visually moved.

## Page 5 - Multi Box Shadow

This page focuses on CSS shadows.

The goal is to practice creating multiple shadows around an element using the box-shadow property.

Concepts Practiced
box-shadow
Multiple shadows
Element styling
Visual depth

This demonstrates how multiple shadow declarations can be combined to create different visual effects.

## Page 6 - Borders

This page demonstrates six different CSS border styles.

The purpose is to understand how changing the border-style property changes the appearance of an element.

Border Styles

Examples include:

solid
dashed
dotted
double
groove
ridge
Concepts Practiced
Border width
Border color
Border style
Different border appearances
## Page 7 - Image Positioning

This page focuses on positioning multiple images.

Four images are placed so that they overlap each other.

The exercise uses positioning and z-index to control the order of the images.

Concepts Practiced
Absolute positioning
Relative positioning
Image sizing
Image overlapping
z-index
object-fit

The first image is placed above the other images using a higher stacking level.

## Page 8 - Advanced

The final CSS exercise is an advanced positioning example.

Multiple boxes are placed on the page and one of the elements demonstrates sticky positioning while the user scrolls through the page.

Concepts Practiced
position: sticky
Scrolling behavior
Positioning
z-index
Normal document flow
Long page layout

The sticky element starts in its normal position and then remains visible at a specific position while scrolling.

Additional sections are included to create enough page height to demonstrate the scrolling behavior.

Final Project - Online FoodShop

After completing the CSS exercises, the project includes a complete webpage called:

Online FoodShop

This page is designed as a simple food ordering website and combines several HTML and CSS concepts into one project.

Website Sections
Header

The header contains:

Food Shop logo
Navigation menu
Home
About
Menu
Contact Us

The navigation links are styled using CSS and include hover effects.

Hero Section

The hero section introduces the website with:

Welcome To the Online FoodShop

It also contains:

Food background image
Order Now button
Food-related images
Positioned elements

The hero section uses CSS background images and positioning techniques.

Food Categories

The website includes different food categories such as:

Main Food
Drinks
Sweet Food

Each category contains an image that can be used as a link.

Footer

The website also contains a footer section for additional information and navigation.

Technologies Used

This project currently uses:

HTML5
CSS3

No JavaScript or external frameworks are required for the current version.

CSS Techniques Used

Some of the main CSS properties used throughout the project include:

display
position
top
left
right
bottom
z-index
margin
padding
border
border-radius
box-shadow
width
height
background
background-image
background-size
background-position
object-fit

Different display techniques are also used, including:

block
inline-block
flex

The project intentionally uses different layout techniques to understand how each one works rather than relying on a single layout system.

Project Structure
CSS-basics-practice/
│
├── index.html
├── pages.html
│
├── position.html
├── z-index.html
├── absolute.html
├── relative.html
├── shadow.html
├── border.html
├── image.html
├── advanced.html
│
├── webpage.html
│
└── assets/
    │
    ├── style.css
    │
    └── images/
        ├── css-3.png
        ├── foodShop.jpg
        ├── foodBackground.jpg
        ├── chef.jpg
        ├── eat.jpg
        ├── mainFood.jpg
        ├── drinks.jpg
        ├── sweetFood.jpg
        └── ...
Navigation

The project uses navigation links to move between the different exercises.

The main page acts as the starting point, while the Pages section provides access to the individual exercises.

Each exercise also includes navigation controls that allow the user to move between pages.

This makes the project work more like a small CSS learning website instead of a collection of unrelated HTML files.

Learning Goals

The main goal of this project is to build a practical understanding of CSS positioning and layout.

By completing the exercises, I practiced:

How elements behave in normal document flow.
How relative positioning works.
How absolute positioning depends on a positioned parent.
How fixed elements behave relative to the viewport.
How sticky elements behave while scrolling.
How z-index controls stacking order.
How margins and padding affect spacing.
How different border styles work.
How multiple shadows can be created.
How images can be positioned and layered.
How different display properties affect layout.
How to organize a multi-page HTML/CSS project.
Purpose

This project was created as a practical CSS learning project.

Instead of only studying CSS properties individually, each concept is demonstrated through a working webpage.

The project is also part of building a stronger foundation in frontend development before moving into more advanced technologies.

Future Improvements

Possible future improvements include:

Adding JavaScript interactions
Making the website fully responsive
Adding a functional shopping cart
Adding real food products
Adding form validation
Improving accessibility
Adding more advanced CSS animations
Building the project with a frontend framework

## Author

Abdullah Abu Dayeh
