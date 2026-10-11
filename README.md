# Portfolio Assignment README 

## Overview

This project is a personal portfolio website created using HTML and CSS. It introduces me, displays some of my previous projects, and provides a way to contact me. The website was created as part of my Web and Scripting Programming assignment.

The website contains four pages:

* Home: Introduces me and my portfolio.
* About Me: Provides information about my background and interests.
* Projects: Displays projects I have worked on.
* Contact Me: Provides a contact form.

## Responsive Design

I used three separate CSS files to style the website for different viewport widths.

* Laptop: `laptop.css` provides the main styling and default layout for the website.
* Tablet: `tablet.css` uses a media query for viewport widths between 481px and 960px.
* Mobile: `mobile.css` uses a media query for viewport widths of 480px and below.

I used separate CSS files so that the layout could adjust to different screen sizes. For example, the project articles can appear next to each other on larger screens, while they are stacked vertically on mobile screens. This makes the content easier to view on smaller devices.

## Color Scheme

I used the Deep Twilight color theme from Adobe Color as a starting point for my website's colour palette. I then adjusted some of the colours using VS Code's colour picker to better match the look I wanted for my portfolio. I chose darker plum and wine tones with dusty pink and ivory to create a consistent colour scheme across all four pages.

The main colours used are:

* Dark background: `#171018`
* Plum: `#211721`
* Wine: `#702D43`
* Dusty pink: `#D6A0B2`
* Ivory: `#F0E6E9`

Adobe Color: https://color.adobe.com/create/color-wheel

## Gradients

I used CSS linear gradients to add colour transitions to the website.

* Main content: The `main` element uses a vertical linear gradient from `#211721` to `#3B1D2C`.
* Footer: The footer uses a horizontal linear gradient from `#171018` to `#3B1D2C`.

## External References

I used W3Schools as a reference for the following CSS techniques:

* `line-height`: Used to adjust the spacing between lines of text to improve readability. Source: [W3Schools CSS Texts](https://www.w3schools.com/css/css_text_spacing.asp).
* `:focus` pseudo-class: Used to highlight a form field when it receives focus, making it easier to identify the currently selected field. Source: [W3Schools CSS Forms](https://www.w3schools.com/css/css_form_focus.asp).
* display: inline-block property: Used to display project articles next to each other while allowing them to have their own width, margins, and padding. Source: [W3Schools CSS Inline Block](https://www.w3schools.com/Css/css_inline-block.asp).

## Testing and Validation

* HTML Validation: W3C Markup Validation Service.
* CSS Validation: W3C CSS Validation Service.
* Link Validation: W3C Link Checker.
* Spelling: VS code street side software code spell checker.
* Accessibility: WAVE Web Accessibility Evaluation Tool.

## Publishing

The website will be hosted using GitHub Pages.

* GitHub Repository: [\[repository URL\]](https://github.com/idzi11/assignment-1-portfolio)
* Live Website: [\[GitHub Pages URL\]](https://idzi11.github.io/assignment-1-portfolio/index.html)
