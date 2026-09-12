# project url : https://abdullahabodayya-jpg.github.io/-CSS-basics-practice/
# CSS Practice - Position & Layout Lab

A practical HTML and CSS learning project focused on CSS positioning,
layout, spacing, borders, shadows, z-index, image positioning, and basic
webpage structure.

The project contains multiple CSS exercises, each organized into a
separate page, followed by a final **Online FoodShop** webpage that
combines the concepts learned throughout the project.

------------------------------------------------------------------------

## Table of Contents

-   [About The Project](#about-the-project)
-   [Project Goals](#project-goals)
-   [What I Practiced](#what-i-practiced)
-   [Project Pages](#project-pages)
-   [Final Project](#final-project)
-   [Technologies Used](#technologies-used)
-   [CSS Concepts](#css-concepts)
-   [Project Structure](#project-structure)
-   [How To Run The Project](#how-to-run-the-project)
-   [Navigation](#navigation)
-   [What I Learned](#what-i-learned)
-   [Future Improvements](#future-improvements)
-   [Author](#author)
-   [License](#license)

------------------------------------------------------------------------

# About The Project

This project was created as a practical CSS exercise to understand how
different CSS properties and positioning techniques work in real
webpages.

Instead of putting all exercises into one HTML file, the project is
divided into multiple pages.

Each page focuses on a specific CSS concept.

The project starts with basic positioning concepts and gradually moves
into more advanced examples involving overlapping elements, z-index,
image positioning, scrolling, and sticky elements.

After completing the CSS exercises, the project ends with a simple food
shop website called **Online FoodShop**.

The final website combines HTML and CSS concepts that were practiced
throughout the project.

------------------------------------------------------------------------

# Project Goals

The main goals of this project are:

-   Understand how CSS positioning works.
-   Understand the difference between static, relative, absolute, fixed,
    and sticky positioning.
-   Practice using `z-index`.
-   Understand how elements overlap.
-   Practice margin and padding.
-   Practice different border styles.
-   Create multiple box shadows.
-   Position and layer images.
-   Practice different display properties.
-   Build a multi-page HTML and CSS project.
-   Apply CSS concepts in a complete webpage.

------------------------------------------------------------------------

# What I Practiced

Throughout the project, I practiced:

-   HTML5
-   CSS3
-   CSS Positioning
-   Static Positioning
-   Relative Positioning
-   Absolute Positioning
-   Fixed Positioning
-   Sticky Positioning
-   Z-index
-   Margin
-   Padding
-   Borders
-   Border Styles
-   Box Shadow
-   Multiple Box Shadows
-   Image Positioning
-   Image Overlapping
-   Background Images
-   Flexbox
-   Inline-block
-   Basic Page Layout
-   Navigation
-   Multi-page Website Structure

------------------------------------------------------------------------

# Project Pages

## Page 1 - Position

The first page introduces the main CSS positioning techniques.

The exercise contains multiple elements using different position values.

### Concepts Practiced

-   `position: relative`
-   `position: absolute`
-   `position: fixed`
-   `z-index`

The purpose of this page is to understand how different positioning
methods change the behavior of elements on the page.

------------------------------------------------------------------------

## Page 2 - Z-index

The second page focuses on the `z-index` property.

Several boxes are positioned so they overlap each other.

Different `z-index` values are used to control which element appears
above the others.

### Concepts Practiced

-   `position`
-   `z-index`
-   Stacking order
-   Overlapping elements

This exercise demonstrates that `z-index` controls the stacking order of
positioned elements.

------------------------------------------------------------------------

## Page 3 - Absolute Position

The third page focuses on absolute positioning.

The exercise demonstrates how an absolutely positioned element can be
placed relative to a positioned parent.

### Concepts Practiced

-   `position: absolute`
-   `position: relative`
-   `top`
-   `left`
-   Parent-child positioning

A common CSS pattern is used:

``` css
.parent {
    position: relative;
}

.child {
    position: absolute;
}
```

The parent becomes the reference point for the absolutely positioned
child.

------------------------------------------------------------------------

## Page 4 - Relative vs Static

The fourth page demonstrates the difference between:

``` css
position: static;
```

and:

``` css
position: relative;
```

Multiple boxes are arranged using `inline-block`.

This exercise intentionally uses `inline-block` instead of CSS Grid to
practice another method of arranging elements horizontally.

### Concepts Practiced

-   Static positioning
-   Relative positioning
-   `top`
-   `left`
-   `inline-block`
-   Margin
-   Horizontal layout

The main idea is to understand that an element with `position: relative`
remains in the normal document flow while allowing its visual position
to be adjusted.

------------------------------------------------------------------------

## Page 5 - Multi Box Shadow

The fifth page focuses on the CSS `box-shadow` property.

The exercise demonstrates how multiple shadows can be applied to the
same element.

### Concepts Practiced

-   `box-shadow`
-   Multiple shadows
-   Element styling
-   Visual depth

Multiple shadow values can be combined to create different visual
effects around an element.

Example:

``` css
box-shadow:
    5px 5px 10px gray,
    -5px -5px 10px lightgray;
```

------------------------------------------------------------------------

## Page 6 - Borders

The sixth page focuses on CSS borders.

The exercise contains six different border styles to demonstrate how the
appearance of an element changes depending on the border style.

### Border Styles

``` text
solid
dashed
dotted
double
groove
ridge
```

### Concepts Practiced

-   Border width
-   Border color
-   Border style
-   Different border appearances

Example:

``` css
border: 2px solid black;
```

------------------------------------------------------------------------

## Page 7 - Image Positioning

The seventh page focuses on positioning multiple images.

Four images are placed so that they overlap each other.

Positioning and `z-index` are used to control the order of the images.

### Concepts Practiced

-   `position: relative`
-   `position: absolute`
-   Image sizing
-   Image overlapping
-   `z-index`
-   `object-fit`

The first image is given a higher stacking level so it appears above the
other images.

------------------------------------------------------------------------

## Page 8 - Advanced

The eighth page is the advanced positioning exercise.

Multiple boxes are placed on the page and one of the elements uses
sticky positioning.

The page contains additional content so the user can scroll and observe
how the sticky element behaves.

### Concepts Practiced

-   `position: sticky`
-   Scrolling behavior
-   Positioning
-   `z-index`
-   Normal document flow
-   Long page layout

The sticky element starts in its normal position.

When the user scrolls past a certain point, the element remains visible
according to its `top` value.

Example:

``` css
position: sticky;
top: 20px;
```

------------------------------------------------------------------------

# Final Project

## Online FoodShop

The final part of the project is a simple food ordering webpage called:

**Online FoodShop**

This webpage combines HTML and CSS concepts practiced in the previous
exercises.

The goal is not to build a fully functional food ordering system, but to
practice creating a complete webpage using HTML and CSS.

------------------------------------------------------------------------

# Online FoodShop Sections

## Header

The website header contains:

-   Food Shop logo
-   Navigation menu
-   Home
-   About
-   Menu
-   Contact Us

The navigation links include CSS styling and hover effects.

------------------------------------------------------------------------

## Hero Section

The hero section introduces the website with:

**Welcome To the Online FoodShop**

It contains:

-   Food background image
-   Order Now button
-   Food-related images
-   Positioned elements

The section uses CSS background images and positioning techniques.

------------------------------------------------------------------------

## Food Categories

The website contains different food categories.

The current categories include:

-   Main Food
-   Drinks
-   Sweet Food

Each category contains an image that can be used as a link.

------------------------------------------------------------------------

## Footer

The website also includes a footer section.

The footer can contain:

-   Website information
-   Navigation links
-   Additional links
-   Copyright information

------------------------------------------------------------------------

# Technologies Used

The project currently uses:

### HTML5

Used to create the structure and content of the webpages.

### CSS3

Used to control:

-   Layout
-   Positioning
-   Colors
-   Spacing
-   Borders
-   Shadows
-   Images
-   Hover effects
-   Page styling

No JavaScript or frontend frameworks are required for the current
version.

------------------------------------------------------------------------

# CSS Concepts

The project uses many CSS properties throughout the different exercises.

## Positioning

``` text
position
top
left
right
bottom
```

The project demonstrates:

``` text
static
relative
absolute
fixed
sticky
```

------------------------------------------------------------------------

## Stacking

``` text
z-index
```

Used to control which positioned elements appear above or below other
elements.

------------------------------------------------------------------------

## Spacing

``` text
margin
padding
```

Used to control the space around and inside elements.

------------------------------------------------------------------------

## Borders

``` text
border
border-radius
border-style
border-width
border-color
```

Used throughout the border exercise and other pages.

------------------------------------------------------------------------

## Shadows

``` text
box-shadow
```

Used to create visual depth and multiple shadow effects.

------------------------------------------------------------------------

## Images

``` text
width
height
object-fit
background-image
background-size
background-position
```

Used to control image size, position, and appearance.

------------------------------------------------------------------------

## Display

Different display techniques are used throughout the project:

``` text
block
inline-block
flex
```

Different layout techniques are intentionally used across the exercises
to understand how they behave.

------------------------------------------------------------------------

# Project Structure

``` text
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
```

------------------------------------------------------------------------

# How To Run The Project

There are no special dependencies required.

To run the project locally:

### 1. Clone the repository

``` bash
git clone <repository-url>
```

### 2. Open the project folder

``` bash
cd CSS-basics-practice
```

### 3. Open the project

Open `index.html` in your web browser.

You can also use a code editor such as Visual Studio Code with the Live
Server extension.

------------------------------------------------------------------------

# Navigation

The project is designed as a small CSS learning website.

The main page provides access to the different exercises.

The Pages section contains links to each CSS exercise.

Each exercise page also contains navigation controls that allow the user
to move between the pages.

The final website can be opened separately from the project navigation.

This structure makes it easier to explore the exercises in order.

------------------------------------------------------------------------

# Learning Progression

The exercises are organized to gradually introduce CSS concepts.

### Basic Positioning

The first exercises focus on:

-   Static
-   Relative
-   Absolute
-   Fixed

### Stacking

The project then introduces:

-   Z-index
-   Overlapping elements

### Layout

The project continues with:

-   Inline-block
-   Margin
-   Positioning
-   Horizontal layouts

### Styling

The project then covers:

-   Borders
-   Box shadows
-   Multiple shadows

### Images

The project demonstrates:

-   Image positioning
-   Image overlapping
-   Z-index

### Advanced Positioning

The final exercise introduces:

-   Sticky positioning
-   Scrolling behavior
-   Normal document flow

### Final Website

The concepts are then combined in the:

**Online FoodShop**

webpage.

------------------------------------------------------------------------

# What I Learned

This project helped me understand how CSS positioning works in practice.

Some of the main things I learned include:

1.  How `static` positioning works.
2.  How `relative` positioning keeps an element in the normal flow.
3.  How `absolute` positioning removes an element from the normal flow.
4.  How an absolute element can use a positioned parent as its
    reference.
5.  How `fixed` positioning works relative to the viewport.
6.  How `sticky` positioning behaves during scrolling.
7.  How `z-index` controls stacking order.
8.  How margin and padding affect spacing.
9.  How different border styles change the appearance of elements.
10. How multiple box shadows can be combined.
11. How images can be positioned and layered.
12. How different CSS display values affect layout.
13. How to organize multiple HTML pages.
14. How to connect multiple webpages using navigation links.
15. How to combine CSS concepts into a complete webpage.

------------------------------------------------------------------------

# Purpose

This project is part of my frontend development learning journey.

The purpose is to build a strong foundation in HTML and CSS before
moving to more advanced frontend technologies.

The exercises are intentionally practical so that CSS concepts can be
understood through actual webpages rather than only theoretical
examples.

------------------------------------------------------------------------

# Future Improvements

There are several improvements that could be added in future versions.

## JavaScript

Add JavaScript to make the website interactive.

Possible features:

-   Working order buttons
-   Interactive navigation
-   Shopping cart
-   Product filtering
-   Form validation

## Responsive Design

Improve the website for:

-   Mobile phones
-   Tablets
-   Laptops
-   Large screens

## Online FoodShop

The final website could be expanded with:

-   More food products
-   Product prices
-   Product descriptions
-   Shopping cart
-   Checkout page
-   Contact form
-   Search functionality

## CSS Improvements

Additional CSS concepts could also be added:

-   CSS Grid
-   CSS Animations
-   CSS Transitions
-   Media Queries
-   Advanced Flexbox
-   Responsive layouts

## Frameworks

In the future, the project could be rebuilt using a frontend framework
such as React.

------------------------------------------------------------------------

# Project Status

This project is currently a learning and practice project.

The main HTML and CSS exercises are completed, along with the initial
Online FoodShop webpage.

Future versions may include JavaScript, responsive design, and
additional frontend functionality.

------------------------------------------------------------------------

# Author

## Abdullah Abu Dayeh

Frontend development learner focused on building a strong foundation in
HTML, CSS, JavaScript, and modern web development technologies.

------------------------------------------------------------------------

# License

This project was created for learning and practice purposes.

You are welcome to explore the code and use it as a reference for
learning HTML and CSS.

