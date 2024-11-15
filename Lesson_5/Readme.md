# 📋HTML Forms Example

This project contains a basic HTML webpage that demonstrates the use of forms. The form allows users to search for journals by entering text and selecting a category. It is designed to help learners understand how to create and handle forms in HTML.

## 📜 Code Overview
The HTML file includes the following sections:

- **DOCTYPE Declaration**: `<!DOCTYPE html>` specifies that this is an HTML5 document.
- **HTML Element**: `<html lang="en">` wraps all the content and sets the language to English.

### 😸 Head Section
The `<head>` section contains metadata, viewport settings, and the title of the page:

- **Charset**: `<meta charset="UTF-8">` sets the character encoding to UTF-8 for proper text display.
- **Viewport**: `<meta name="viewport" content="width=device-width, initial-scale=1.0">` ensures the webpage is responsive by setting the viewport width to the device width and initial scale to 1.
- **Title**: `<title>Forms</title>` sets the browser tab title.

### 💪 Body Section
The `<body>` section displays the visible content of the webpage:

- **Form**: 
  - `<form action="/api/v1/journal" method="get">`: The form element that specifies the action URL and method (GET) for form submission.
    - **Label and Text Input**:
      - `<label for="search-bar">Search</label>`: A label for the text input field.
      - `<input id="search-bar" type="text" name="search" placeholder="Search for journals">`: A text input field with a placeholder text.
    - **Label and Select Dropdown**:
      - `<label for="journal-category">Journal Category</label>`: A label for the select dropdown.
      - `<select id="journal-category" name="category">`: A dropdown menu for selecting journal categories.
        - `<option value="idea">Idea</option>`: Option for "Idea".
        - `<option value="task">Task</option>`: Option for "Task".
        - `<option value="memory">Memory</option>`: Option for "Memory".
    - **Button**:
      - `<button type="search">Search</button>`: A button to submit the form and perform the search action.

### 🧑🏽‍🏫 Explanation of Tags and Elements
1. **`<!DOCTYPE html>`**: Declares the document type and version of HTML (HTML5).
2. **`<html lang="en">`**: The root element of an HTML document, specifying the language as English.
3. **`<head>`**: Contains meta-information about the HTML document, such as the character set, viewport settings, and title.
4. **`<meta charset="UTF-8">`**: Sets the character encoding for the document to UTF-8, ensuring proper display of text.
5. **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Ensures the webpage is responsive by setting the viewport width to the device width and initial scale to 1.
6. **`<title>Forms</title>`**: Sets the title of the webpage, which appears in the browser tab.
7. **`<body>`**: Contains the content of the webpage that is visible to users.
8. **`<form>`**: Defines an HTML form for user input.
9. **`<label>`**: Defines a label for an `<input>` element, improving accessibility.
10. **`<input>`**: Defines an input field where the user can enter data.
11. **`<select>`**: Creates a dropdown list.
12. **`<option>`**: Defines an option in a dropdown list.
13. **`<button>`**: Defines a clickable button to submit the form.

## 💻 How to View the Webpage
1. Clone or download this HTML file to your local machine.
2. Open the HTML file in any web browser (e.g., Chrome, Firefox, Edge) to view the webpage.

## 🔮 Purpose
This project is intended as an introductory exercise to help learners understand how to create and handle forms in HTML.
