# 📻 HTML Radio Buttons Example

This project contains a basic HTML webpage that demonstrates the use of radio buttons within a form. It allows users to select a shirt size and submit their choice. This example is designed to help learners understand how to create and handle radio buttons in HTML forms.

## 📜 Code Overview
The HTML file includes the following sections:

- **DOCTYPE Declaration**: `<!DOCTYPE html>` specifies that this is an HTML5 document.
- **HTML Element**: `<html lang="en">` wraps all the content and sets the language to English.

### 😸 Head Section
The `<head>` section contains metadata, viewport settings, and the title of the page:

- **Charset**: `<meta charset="UTF-8">` sets the character encoding to UTF-8 for proper text display.
- **Viewport**: `<meta name="viewport" content="width=device-width, initial-scale=1.0">` ensures the webpage is responsive by setting the viewport width to the device width and initial scale to 1.
- **Title**: `<title>Radio Button</title>` sets the browser tab title.

### 💪 Body Section
The `<body>` section displays the visible content of the webpage:

- **Heading**: `<h1>Shirt Size</h1>`: A level 1 heading for the shirt size selection section.
- **Form**:
  - `<form action="/clothing/shirts" method="post">`: The form element that specifies the action URL and method (POST) for form submission.
    - **Radio Button Inputs and Labels**:
      - `<input id="small" type="radio" name="size" value="s">`: A radio button input for selecting "Small".
      - `<label for="small">Small</label>`: A label for the small radio button.
      - `<input id="medium" type="radio" name="size" value="m">`: A radio button input for selecting "Medium".
      - `<label for="medium">Medium</label>`: A label for the medium radio button.
      - `<input id="large" type="radio" name="size" value="l">`: A radio button input for selecting "Large".
      - `<label for="large">Large</label>`: A label for the large radio button.
      - `<input id="extra-large" type="radio" name="size" value="xl">`: A radio button input for selecting "XL".
      - `<label for="extra-large">XL</label>`: A label for the XL radio button.
      - `<input id="extra-extra-large" type="radio" name="size" value="xxl">`: A radio button input for selecting "XXL".
      - `<label for="extra-extra-large">XXL</label>`: A label for the XXL radio button.
    - **Submit Button**:
      - `<button type="submit">Submit</button>`: A button to submit the form with the selected size.

### 👨🏽‍🏫 Explanation of Tags and Elements
1. **`<!DOCTYPE html>`**: Declares the document type and version of HTML (HTML5).
2. **`<html lang="en">`**: The root element of an HTML document, specifying the language as English.
3. **`<head>`**: Contains meta-information about the HTML document, such as the character set, viewport settings, and title.
4. **`<meta charset="UTF-8">`**: Sets the character encoding for the document to UTF-8, ensuring proper display of text.
5. **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Ensures the webpage is responsive by setting the viewport width to the device width and initial scale to 1.
6. **`<title>Radio Button</title>`**: Sets the title of the webpage, which appears in the browser tab.
7. **`<body>`**: Contains the content of the webpage that is visible to users.
8. **`<h1>`**: A level 1 heading, used for the main title of the section.
9. **`<form>`**: Defines an HTML form for user input.
10. **`<input type="radio">`**: Defines a radio button input field where users can select one option from a group.
11. **`<label>`**: Defines a label for an `<input>` element, improving accessibility.
12. **`<button type="submit">`**: Defines a button to submit the form.

## 💻 How to View the Webpage
1. Clone or download this HTML file to your local machine.
2. Open the HTML file in any web browser (e.g., Chrome, Firefox, Edge) to view the webpage.

## 🔮 Purpose
This project is intended as an introductory exercise to help learners understand how to create and handle radio buttons within HTML forms.
