# For You, Dear 🌸🌻
![Project Screenshot](screenshot.png)

A heartfelt project that combines creativity, interactive design, and sentimental elements. This repository is a gift website, designed with love, featuring draggable notes and personalized messages paired with images.

Table of Contents
-- Overview
-- Features
-- File Structure
-- How It Works
-- Usage
-- Technologies Used
-- Future Enhancements

## Overview

"For You, Dear" is a fun, interactive project showcasing draggable paper cards that reveal heartfelt messages and images. It's designed to offer a personalized and interactive experience for someone special. This project leverages HTML, CSS, and JavaScript to create a smooth, visually appealing interface.

## Features
-- Draggable Notes: Users can drag and rearrange the notes freely.
-- Custom Fonts: Unique fonts for a handwritten, personalized look.
-- Hover Effects: Subtle hover animations for a polished touch.
-- Responsive Design: Optimized for desktop and mobile devices.
-- Interactive Messages: Each note contains meaningful text and paired images to convey emotions.

## File Structure
Root Directory:
-- index.html: The main HTML file containing the structure of the webpage.
-- styles.css: The CSS file responsible for styling the webpage, including fonts, colors, and layout.
-- script.js: The JavaScript file adding interactivity, such as drag-and-drop functionality and animations.
-- Rest are just images used in the project.

## Detailed Explanation of Files

### 1. index.html
This is the primary file that defines the structure of the webpage. Key elements include:
<u>Head Section:</u>
Imports Google Fonts (Caveat, Oswald, and Playfair Display). Links the styles.css file for styling. Includes a title, "For you dear 🌸🌻".
<u>Body Section:<u>
Contains multiple <div class="paper image"> elements, each representing a draggable paper card. Each card has a <p> tag for the text message. An <img> tag to display an associated image.

### 2. styles.css
This file defines the visual appearance of the website. Key sections include:
General Styling:
body styled with a black background and a centered layout. Background images and hover effects are implemented for a polished look.

Paper Cards:

.paper class styles each note with a shadow, padding, and rotation for an organic, handwritten feel.

.paper:hover enhances the shadow for an interactive hover effect.

Fonts and Colors:

Custom fonts (Caveat for a handwritten look, Playfair Display for elegance).

Text colors and shadows for a vivid and readable design.

3. script.js

This file handles the functionality of draggable notes. It:

Implements mouse and touch event listeners.

Tracks drag-and-drop movement for each paper card.

Updates the z-index dynamically to ensure the dragged note appears on top.

Key logic includes:

handleMove: Calculates the position and rotation of each card during a drag.

init: Adds event listeners to make each card draggable and rotatable.

4. Images Folder

Contains:

front.png: Background image for the notes.

Multiple images (image1.jpeg, image2.jpeg, etc.) paired with each message.

How It Works

The webpage loads with several draggable cards.

Each card has a unique message and image.

Users can click and drag cards around the screen, rearranging them as desired.

Subtle hover effects enhance the user experience.

Usage

Steps to Run Locally

Clone the repository:

git clone https://github.com/Tamanna013/for-you-dear.git

Navigate to the project directory:

cd for-you-dear

Open index.html in your browser to view the project.

Deployment

The website can be deployed using GitHub Pages or any static hosting platform.

Technologies Used

HTML5: For structure.

CSS3: For styling and animations.

JavaScript (Vanilla): For interactivity.

Future Enhancements

Add responsive touch gestures for better mobile experience.

Implement a save feature to retain card positions.

Add sound effects when cards are dragged.

Enhance accessibility with ARIA roles and labels.

Create a personalization option for users to add their own text and images.

Credits

Created with love by Tamanna (Tamanna013) 🌸💜

