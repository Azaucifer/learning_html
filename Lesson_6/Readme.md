# 📝 HTML Checkboxes Example

This project contains a basic HTML webpage that demonstrates the use of checkboxes within a form. It allows users to select various pizza toppings and submit their choices. This example is designed to help learners understand how to create and handle checkboxes in HTML forms.

## 📜 Code Overview
The HTML file includes the following sections:

- **DOCTYPE Declaration**: `<!DOCTYPE html>` specifies that this is an HTML5 document.
- **HTML Element**: `<html lang="en">` wraps all the content and sets the language to English.

### 😸 Head Section
The `<head>` section contains metadata, viewport settings, and the title of the page:

- **Charset**: `<meta charset="UTF-8">` sets the character encoding to UTF-8 for proper text display.
- **Viewport**: `<meta name="viewport" content="width=device-width, initial-scale=1.0">` ensures the webpage is responsive by setting the viewport width to the device width and initial scale to 1.
- **Title**: `<title>Check Boxes</title>` sets the browser tab title.

### 💪 Body Section
The `<body>` section displays the visible content of the webpage:

- **Heading**: `<h1>Pizza Toppings</h1>`: A level 1 heading for the pizza toppings section.
- **Form**:
  - `<form action="/food/pizza" method="post">`: The form element that specifies the action URL and method (POST) for form submission.
    - **Checkbox Inputs and Labels**:
      - `<input id="checkbox-1" type="checkbox" name="pineapple">`: A checkbox input for selecting "Pineapple".
      - `<label for="checkbox-1">Pineapple</label>`: A label for the pineapple checkbox.
      - `<input id="checkbox-2" type="checkbox" name="corn">`: A checkbox input for selecting "Corn".
      - `<label for="checkbox-2">Corn</label>`: A label for the corn checkbox.
      - `<input id="checkbox-3" type="checkbox" name="chilly">`: A checkbox input for selecting "Chilly".
      - `<label for="checkbox-3">Chilly</label>`: A label for the chilly checkbox.
      - `<input id="checkbox-4" type="checkbox" name="olives">`: A checkbox input for selecting "Olives".
      - `<label for="checkbox-4">Olives</label>`: A label for the olives checkbox.
    - **Submit Button**:
      - `<button type="submit">Submit</button>`: A button to submit the form with the selected toppings.

### 👨🏽‍🏫 Explanation of Tags and Elements
1. **`<!DOCTYPE html>`**: Declares the document type and version of HTML (HTML5).
2. **`<html lang="en">`**: The root element of an HTML document, specifying the language as English.
3. **`<head>`**: Contains meta-information about the HTML document, such as the character set, viewport settings, and title.
4. **`<meta charset="UTF-8">`**: Sets the character encoding for the document to UTF-8, ensuring proper display of text.
5. **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Ensures the webpage is responsive by setting the viewport width to the device width and initial scale to 1.
6. **`<title>Check Boxes</title>`**: Sets the title of the webpage, which appears in the browser tab.
7. **`<body>`**: Contains the content of the webpage that is visible to users.
8. **`<h1>`**: A level 1 heading, used for the main title of the section.
9. **`<form>`**: Defines an HTML form for user input.
10. **`<input type="checkbox">`**: Defines a checkbox input field where users can select multiple options.
11. **`<label>`**: Defines a label for an `<input>` element, improving accessibility.
12. **`<button type="submit">`**: Defines a button to submit the form.

## 💻 How to View the Webpage
1. Clone or download this HTML file to your local machine.
2. Open the HTML file in any web browser (e.g., Chrome, Firefox, Edge) to view the webpage.

## 🔮 Purpose
This project is intended as an introductory exercise to help learners understand how to create and handle checkboxes within HTML forms.
