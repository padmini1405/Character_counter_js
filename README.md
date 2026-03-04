# Project Overview

This project is a simple web application that includes a text area with a real-time character counter. As the user types a message, 
The application dynamically updates the number of characters typed and displays how many characters remain out of the maximum allowed limit.
The maximum character limit is set to 200 characters.

# Features

- Text area with a maximum character limit (200 characters)
- Real-time character counter
- Displays typed characters and remaining characters (e.g., 150/200 characters)
- Prevents typing beyond the character limit
- Shows a warning message when the limit is exceeded

# Technologies Used

- HTML
- CSS
- JavaScript

# Project Structure

character-counter/
│
├── index.html
├── style.css 

# Requirements Implemented

- HTML textarea with maximum allowed characters display
- input event listener to track user typing
- Real-time character counter update
- Display typed and remaining characters
- Prevent input beyond 200 characters
- Show warning message when limit is exceeded

# How It Works

1) The textarea has a maximum character limit of 200.
2) A JavaScript input event listener tracks changes as the user types.
3) The counter updates dynamically to show:
      - currentCharacters / 200 characters
4) If the user reaches the limit:
      - Further typing is prevented.
      - A warning message is displayed.

# How to view

You can access my website by visiting this [link]. Feel free to explore the content and get in touch.
Created as a practice project to demonstrate DOM manipulation and real-time input handling in JavaScript.

Developed by Padmini K
