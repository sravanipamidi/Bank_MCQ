# Bank MCQ Project Documentation

## Step 1: Project Initialization
 - All files and content cleared to start fresh.


## Step 2: Basic HTML Structure
 - Added a container with a heading and three MCQ questions to index.html.
 - Added a submit button to the form.
 - No CSS or interactivity yet, only HTML structure.


## Step 3: Basic CSS Styling
 - Added style.css with modern, clean styling for the quiz.
 - The quiz is centered, with a white background, rounded corners, and a drop shadow.
 - The button is styled for better appearance and hover effect.

## Step 4: Show Submission Message with :target and Fragment Identifier
 - Used the form's action attribute to set the fragment identifier (e.g., action="#submitted-message").
 - Added a hidden message div with id="submitted-message" and class="hidden-message" after the form.
 - In style.css, used the :target selector to display the message when the fragment is present in the URL.
 - This method works in standard browsers, but may not work in all embedded browsers (like Simple Browser in VS Code).
   
## Step 5: Make the Quiz Responsive
 - Added a CSS media query for screens up to 600px wide.
 - The quiz container, heading, questions, and button now scale for mobile devices.
## Step 4: Show Submission Message (HTML & CSS Only)
 - Added a hidden message div below the form in index.html.
 - Changed the form's action to point to the message div using a fragment identifier.
 - Used the :target CSS selector to display the message after form submission.

## Next Steps
1. Add more questions if needed (repeat the question-block structure).
2. Make the quiz responsive for mobile devices (optional, with CSS).
3. Add a section to display the result (using only HTML/CSS, e.g., a hidden div that can be shown by removing a class).
4. Document each step in docs.md as you go.

---

---

This file will be updated with every step and change made to the project.
This file will be updated with every step and change made to the project.
