# Delivery Status Page

A front-end user interface that represents a multi-step food delivery flow, built using HTML and CSS.

This project demonstrates how to design a clean, modern delivery status experience using card-based layouts, visual progress indicators, and responsive behavior without the need of JavaScript.

# Purpose

This project was built to:
* Practice creating multi-step UI layouts.
* Improve confidence with card-based design patterns.
* Reinforce positioning and layout techniques in CSS.
* Work with visual hierarchy and user flow.
* Build a realistic UI similar to food delivery applications.

# Features

* Three-step delivery flow represented by panels:
    * Dish selection
    * Order confirmation
    * Delivery in progress
* Card-based layout with elevation and shadows.
* Visual step indicators using progress dots.
* Primary and inactive button states.
* Clean typography using Google Fonts.
* Responsive layout that adapts for desktop screens.

# Tech Stack

* HTML5
* CSS3
* Google Fonts

# How It Works

The UI is structured as three separate panels, each representing a step in the delivery process.
* Each panel is styled as a card with shadows and rounded corners.
* The center panel represents the active step in the flow.
* Progress dots visually indicate the current step.
* Buttons change style based on active or inactive states.
* On smaller screens, only the main panel is shown.
* A media query reveals the left and right panels on larger screens to show the full flow.



# Styling Notes

* Flexbox is used to center and align panels.
* Absolute positioning handles icons, buttons, and progress indicators.
* Shadows and elevation create depth between UI layers.
* Button states are visually differentiated using color and opacity.
* Media queries control which panels are visible based on screen size.

# Demo

Open the index.html file in your browser (or use Live Server) to view the delivery status interface.
No setup or build steps required.