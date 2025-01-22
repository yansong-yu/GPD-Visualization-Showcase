This project visualizes probability density functions (PDFs) for various datasets (JAM20/CJ15nlo) and variables(du/dv/uv). The heatmap dynamically represents the relationship between a normalized parameter and the corresponding pdf.

# Features
- Dynamic Heatmap visualization:
The heatmap visualizes the PDF of the selected dataset and variable.
Automatically updates when a dataset or variable is changed.

# Usage
- Prerequisites: A web browser that supports JavaScript and D3.js.

# Setup: 
Clone or download the project to your local machine.

# Running the Project:
- Open a terminal in the project directory.
- Start a local HTTP server:
`python3 -m http.server`
- Access the project in your browser at:
`http://localhost:8000/Ihapdf.html`

# Interactivity:

- Use the dropdown menus at the top to select a dataset (JAM20 or CJ15nlo).
- Select a variable from the variable dropdown (du, dv, or uv).
- The heatmap will automatically render the PDF corresponding to the selected parameter.
