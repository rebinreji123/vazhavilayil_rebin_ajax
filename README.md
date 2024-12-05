# vazhavilayil_rebin_ajax
 
# AJAX App: Earbuds Model Page

Welcome to the **AJAX App: Earbuds Model Page**! This project is a dynamic, interactive webpage designed to showcase the features and materials of the earbuds. As part of the assignment, I've utilized skills in **SASS**, **AJAX**, **HTML template elements**, and the **Fetch API** to create a fully responsive and engaging user experience.

---

## Project Description

This assignment builds upon the **Earbuds Promotional Page** and brings it to life with interactivity and dynamic data loading. The project connects to a JSON API that provides information about the earbuds, including their features and materials. Data is fetched asynchronously and displayed interactively on the page.

---

## Features and Implementation

1. **Dynamic Data Loading**  
   - Data is fetched using the **Fetch API** from a provided API endpoint.  
   - A loading spinner is displayed while the data is being retrieved, ensuring clear feedback to the user.

2. **HTML Template Element**  
   - Materials and other data are dynamically rendered using the `<template>` element, ensuring clean and reusable code.  

3. **Error Handling**  
   - Graceful error responses ensure users are informed if the data fails to load.  
   - Messages provide clear guidance or fallback content in case of API issues.  

4. **Interactive Hotspots**  
   - Hotspots allow users to explore the features of the earbuds interactively.  

5. **SASS Workflow**  
   - All styles are written in **SASS** and compiled to CSS, ensuring maintainability and modularity.  

---

## Technologies Used

- **HTML5**: For structure.  
- **SASS**: For styles, enabling modular and efficient CSS writing.  
- **JavaScript (ES6)**: Powers interactivity and dynamic content loading.  
- **Fetch API**: Handles asynchronous API calls.  
- **HTML Template Element**: Creates reusable, dynamic content sections.  
- **Git/GitHub**: For version control and collaboration.  

---

## Setup and Usage

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/ajax-earbuds-app.git
   cd ajax-earbuds-app
   ```

2. Install dependencies and start a local server:  
   ```bash
   npm install
   npm start
   ```

3. Open the app in your browser and interact with the hotspots to explore the dynamic content.

---

## API Endpoints

- **Earbuds Features**: `https://swiftpixel.com/earbud/api/infoboxes`  
- **Materials Data**: `https://swiftpixel.com/earbud/api/materials`  

---

## Git Workflow

1. **Branching**  
   - Features and fixes are implemented on individual branches (e.g., `feature-dynamic-data`, `fix-loading-spinner`).  
   - No direct commits are made to the master branch.  

2. **Merging**  
   - After thorough testing, branches are merged into the master branch using pull requests.  

3. **Version Control**  
   - Commits are made frequently, with detailed messages reflecting changes.  

---

## Submission

To submit, all code is merged into the **master** branch, and the repository link is uploaded to the FOL dropbox.

---


## License

This project is open-source and available under the [MIT License](LICENSE).  

Feel free to explore and provide feedback!