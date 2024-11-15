# 🪟 HTML Table Example

This project contains a basic HTML webpage that demonstrates the use of tables to display data. It showcases a list of Conor McGregor's fights, including event details, opponents, venues, cities, and Pay-Per-View (PPV) sales. This example is designed to help learners understand how to create and structure tables in HTML.

## 📜 Code Overview
The HTML file includes the following sections:

- **DOCTYPE Declaration**: `<!DOCTYPE html>` specifies that this is an HTML5 document.
- **HTML Element**: `<html lang="en">` wraps all the content and sets the language to English.

### 😸 Head Section
The `<head>` section contains metadata, viewport settings, and the title of the page:

- **Charset**: `<meta charset="UTF-8">` sets the character encoding to UTF-8 for proper text display.
- **Viewport**: `<meta name="viewport" content="width=device-width, initial-scale=1.0">` ensures the webpage is responsive by setting the viewport width to the device width and initial scale to 1.
- **Title**: `<title>HTML Table</title>` sets the browser tab title.

### 💪 Body Section
The `<body>` section displays the visible content of the webpage:

- **Heading**: `<h1>Conor McGregor Fights</h1>`: A level 1 heading for the section showcasing Conor McGregor's fights.
- **Table**:
  - `<table>`: The table element that contains all the tabular data.
    - **Table Head**:
      - `<thead>`: The header section of the table.
        - `<tr>`: A table row.
          - `<th>Event</th>`: A table header cell for the event.
          - `<th>Fight</th>`: A table header cell for the fight.
          - `<th>Venue</th>`: A table header cell for the venue.
          - `<th>City</th>`: A table header cell for the city.
          - `<th>PPV</th>`: A table header cell for the Pay-Per-View sales.
    - **Table Body**:
      - `<tbody>`: The body section of the table containing the actual data.
        - `<tr>`: A table row.
          - `<td>UFC 189</td>`: A table data cell for the event.
          - `<td>Mendes vs McGregor</td>`: A table data cell for the fight.
          - `<td rowspan="3">MGM Grand</td>`: A table data cell for the venue, spanning three rows.
          - `<td rowspan="4">Las Vegas</td>`: A table data cell for the city, spanning four rows.
          - `<td>825,000</td>`: A table data cell for the PPV sales.
        - (Additional rows follow the same structure.)
    - **Table Foot**:
      - `<tfoot>`: The footer section of the table.
        - `<tr>`: A table row.
          - `<td colspan="4">Total Sales</td>`: A table data cell for the total sales, spanning four columns.
          - `<td>4,992,000</td>`: A table data cell for the total PPV sales.

### 👨🏽‍🏫 Explanation of Tags and Elements
1. **`<!DOCTYPE html>`**: Declares the document type and version of HTML (HTML5).
2. **`<html lang="en">`**: The root element of an HTML document, specifying the language as English.
3. **`<head>`**: Contains meta-information about the HTML document, such as the character set, viewport settings, and title.
4. **`<meta charset="UTF-8">`**: Sets the character encoding for the document to UTF-8, ensuring proper display of text.
5. **`<meta name="viewport" content="width=device-width, initial-scale=1.0">`**: Ensures the webpage is responsive by setting the viewport width to the device width and initial scale to 1.
6. **`<title>HTML Table</title>`**: Sets the title of the webpage, which appears in the browser tab.
7. **`<body>`**: Contains the content of the webpage that is visible to users.
8. **`<h1>`**: A level 1 heading, used for the main title of the section.
9. **`<table>`**: Defines a table for displaying data in rows and columns.
10. **`<thead>`**: Defines the header section of the table.
11. **`<tbody>`**: Defines the body section of the table.
12. **`<tfoot>`**: Defines the footer section of the table.
13. **`<tr>`**: Defines a row in the table.
14. **`<th>`**: Defines a header cell in the table.
15. **`<td>`**: Defines a data cell in the table.
16. **`rowspan`**: An attribute that allows a cell to span multiple rows.
17. **`colspan`**: An attribute that allows a cell to span multiple columns.

## 💻 How to View the Webpage
1. Clone or download this HTML file to your local machine.
2. Open the HTML file in any web browser (e.g., Chrome, Firefox, Edge) to view the webpage.

## 🔮 Purpose
This project is intended as an introductory exercise to help learners understand how to create and structure tables in HTML.
