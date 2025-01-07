# visayas-vaccine-info
Aggregation of COVID vaccine info for Visayas Island

# dhrubsingh/visayas-vaccine-info

## 📖 Project Overview
The Visayas Vaccine Info project is a web-based tool designed to aggregate and provide easy access to COVID-19 vaccine registration information for cities in the Visayas region of the Philippines. Its primary purpose is to help residents quickly find vaccine registration links and contact details for their local government units (LGUs). The project targets Filipinos in the Visayas region who are seeking vaccination opportunities and aims to amplify the reach of local government vaccine initiatives.

## 🏗️ Technical Architecture
The project is built as a static website using HTML, CSS, and JavaScript. The main components include an interactive searchable list of cities, dynamically generated content using JavaScript, and responsive styling with Bootstrap. The `index.html` file serves as the entry point, while `script.js` handles the dynamic generation of city data and search functionality. The `styles.css` file provides custom styling to enhance the user experience.

## 📁 File Documentation

### 📄 index.html
This is the main HTML file that structures the webpage. It includes meta tags for responsiveness, links to Bootstrap and custom CSS, and a container for displaying the vaccine registration information. The file also integrates the JavaScript functionality for dynamic content generation.

### 📄 script.js
This JavaScript file contains the logic for dynamically generating the list of cities and their corresponding vaccine registration links. It also implements the search functionality to filter cities based on user input. The file uses an array of city objects to store and display the data.

### 📄 styles.css
This CSS file provides custom styling for the webpage, including the layout, colors, and responsiveness. It enhances the visual appeal of the search bar, city list, and other elements, ensuring a user-friendly experience.

## 🔧 Installation
To set up the project locally, follow these steps:

```bash
git clone https://github.com/dhrubsingh/visayas-vaccine-info.git
cd visayas-vaccine-info
```

Open the `index.html` file in your preferred web browser to view the project.

## 🚀 Usage
Once the project is running, you can search for your city in the search bar. The list will dynamically filter based on your input. Click on a city name to view its vaccine registration link and contact information.

Example of searching for a city:

```javascript
// Example: Searching for "Bacolod"
document.getElementById('myInput').value = 'Bacolod';
search();
```

## 📋 Requirements
- A modern web browser (e.g., Chrome, Firefox, Edge)
- Internet connection (for loading Bootstrap and Google Fonts)
- No additional dependencies are required.

## 📝 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.