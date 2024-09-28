Chemical Supplies Data Table Task
Project Overview
This project demonstrates a JavaScript task developed using HTML, CSS, and JavaScript. The task involves creating a dynamic data table for Chemical Supplies using a demo JSON array of chemical data. The table provides several interactive functionalities such as sorting, adding, editing, deleting, and moving rows, as well as saving the updated data.

Features
Dynamic Data Table:

The table is generated dynamically from a predefined JSON array of chemical data.
The JSON array includes properties like chemical name, vendor, density, viscosity, packaging, pack size, unit, and quantity.
Sort Functionality:

You can sort the data by Chemical Name, Vendor, Density, Viscosity, Packaging, Pack Size, Unit, and Quantity.
Sorting can be done in ascending or descending order by clicking the table headers.
Add New Chemical:

Users can add new chemicals to the table by entering details in the modal form, which includes all the fields mentioned above.
Edit Existing Chemical:

Users can select a chemical row from the table and edit its details via the modal form.
Delete Chemical:

Users can delete any selected chemical from the table.
Move Row Up/Down:

The rows in the table can be moved up or down, allowing you to reorder the chemicals as necessary.
Save Data:

The table provides a save functionality to retain the updated data.
Files Included
index.html: Contains the structure of the page, including the table and modal form.
assets/css/style.css: Contains the styling for the page layout, table, buttons, and modal.
assets/js/script.js: Contains the JavaScript code that handles the table functionalities like sorting, adding, editing, deleting, moving rows, and saving the data.
How to Use
Clone or download the repository.
Open index.html in any modern browser.
The Chemical Supplies Data Table will be loaded with demo data.
Use the buttons in the action section to add, edit, delete, or reorder the chemicals.
The "Save" button will save your changes.
Project Structure
bash
Copy code
├── assets
│   ├── css
│   │   └── style.css        # CSS for styling the page
│   ├── img
│   │   └── icons            # Icons used for buttons
│   └── js
│       └── script.js        # Main JS file with all functionalities
├── index.html                # Main HTML file
└── README.md                 # This readme file
Technologies Used
HTML5 for structuring the page.
CSS3 for styling the table, modal, and buttons.
JavaScript (ES6) for implementing the functionalities (sorting, adding, editing, deleting, reordering, and saving the table data).
