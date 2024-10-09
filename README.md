# Eye Animation Program

## Overview

The Eye Animation program creates a playful visual effect where two eyes follow the mouse cursor around the screen. As the user moves their mouse, the pupils of the eyes track the cursor position, providing an engaging and interactive experience.

## Features

- **Interactive Eyes**: The pupils of the eyes move in response to mouse movements, creating a lifelike effect.
- **Simple Structure**: The program consists of HTML for layout, CSS for styling, and JavaScript for interactivity.

## Technologies Used

- HTML
- CSS
- JavaScript

## How to Use

1. **Set Up Your Environment**: Save the provided code into an `.html` file (e.g., `eye_animation.html`) and create a CSS file named `eye-style.css` for the styles.
2. **Open the HTML File**: Open the `.html` file in a web browser.
3. **Interact with the Eyes**: Move your mouse around the window to see the eyes follow your cursor.

## Code Explanation

- **HTML Structure**:
  - The eyes are represented using nested `<div>` elements, with a main container for the body.
  - Each eye contains a ball representing the pupil.
  
- **CSS Styling**: The `eye-style.css` file (not included in the provided code) should contain styles to position the eyes and define their appearance, ensuring the pupils are centered within the eye containers.

- **JavaScript Functionality**:
  - The `mousemove` event is captured to determine the current mouse position.
  - The pupils' positions are updated based on the mouse's X and Y coordinates, scaled appropriately for the eye containers.
  - The pupils use CSS `transform` to move smoothly within their respective eye containers.

## Customization

You can customize the following aspects of the program:

- **Eye Design**: Modify the CSS in `eye-style.css` to change the appearance of the eyes and pupils (e.g., size, color, shape).
- **Follow Sensitivity**: Adjust the calculations in the JavaScript to change how closely the pupils follow the cursor.

## Conclusion

This Eye Animation program is a fun and simple project that showcases basic web development concepts, including DOM manipulation and event handling. Feel free to experiment with the design and functionality to enhance the experience!
