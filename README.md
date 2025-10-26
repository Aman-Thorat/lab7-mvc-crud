# Lab 7: MVC Refactor
## Overview
This lab refactors the previous chatbot project into the Model-View-Controller (MVC) pattern.
## Project Goals
By the end of this lab, I will have:
1. A chatbot application refactored into MVC architecture
2. Full CRUD (Create, Read, Update, Delete) functionality for chat messages
3. Data persistence using localStorage and JSON
4. Import and export capabilities for chat history
## Website Details
My website will:
- Have a working chatbot using the Eliza response logic
- Store and load chat history using localStorage
- Allow editing and deleting messages
- Let users export and import chat history as JSON files
- Keep the UI responsive and easy to use
## Development Approach
This project was developed in steps:
1. Refactored Lab 6 chatbot code into separate MVC components
2. Built the View to handle DOM rendering and updates
3. Created the Controller to manage user actions and communication between Model and View
4. Added CRUD features for chat management
5. Tested data persistence, import/export, and message editing/deletion
## Repository Structure (Planned)
```
├── src
├──── js/
│ ├──── model.js - Data management (Model)
│ ├──── view.js - UI rendering (View)
│ ├──── controller.js - Business logic (Controller)
│ ├──── app.js - Application initialization
│ └──── eliza.js - Bot response logic (provided concept from Lab 6)
├──── index.html - Main application page
├──── styles.css - Application styles
├── README.md # A README for desciptions of the Lab
└── LICENSE.md # MIT License
```
## License
This project is licensed under the MIT License - see [LICENSE.md](LICENSE) for
details.
## Website Link:
https://lab7-mvc-crud-196.pages.dev/
## Author
**Aman Thorat**