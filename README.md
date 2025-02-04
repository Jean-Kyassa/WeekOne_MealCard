Smart Meal Card Website Project
Overview
This project is a responsive website for Smart Meal Card, featuring a modern design with a contact page that includes an interactive Google Maps integration. The website is built using HTML5 and CSS3, focusing on clean, maintainable code and user-friendly interface design.
Project Structure
InternshipWeek1/
├── index.html
├── contact.html
├── about.html
├── login.html
├── styles.css
|-- email_icon.jpg
|-- phone_icon.jpg
|-- location-icon.jpg
|-- LG.png
|-- homeIM.png
|-- LoginIM.png
└── README.md
Technologies Used

HTML5
CSS3
Google Maps API (for map integration)
Google Fonts
Modern CSS Grid and Flexbox for layouts

Features

Responsive Navigation

Clean and intuitive navigation menu
Mobile-friendly design
Consistent across all pages


Contact Page Features

Interactive contact form
Google Maps integration
Contact information display
Responsive two-column layout


Styling Features

Modern color scheme
Hover effects
Consistent typography
Responsive design for all screen sizes



Setup and Installation
Prerequisites

A modern web browser (Chrome, Firefox, Safari, or Edge)
A text editor (VS Code, Sublime Text, or similar)
Basic understanding of HTML and CSS

Steps to Run

Clone the repository or download the files
Open the project in your preferred text editor
Ensure all files are in their correct directories as per the project structure
Open index.html in a web browser to view the website

Local Development

No special server requirements - can be run directly from the file system
For live reload functionality, you can use VS Code's Live Server extension

Google Maps Integration
To set up the Google Maps integration:

Go to the Google Cloud Console
Create a new project
Enable the Maps JavaScript API
Get your API key
Replace the iframe src URL in contact.html with your map embed URL
html
<iframe 
    src="YOUR_GOOGLE_MAPS_EMBED_URL"
    width="100%"
    height="300"
    style="border:0;"
    allowfullscreen=""
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade">
</iframe>
Customization
Changing Colors
The main colors can be modified in the CSS:
css:root {
    --primary-color: #ff7f50;
    --secondary-color: #333333;
    --background-color: #f8f9fa;
}
Updating Content

Text content can be modified directly in the HTML files
Images can be replaced in the assets/images directory
Contact information can be updated in contact.html

Best Practices Implemented

Semantic HTML5 elements
Mobile-first responsive design
CSS Grid and Flexbox for layouts
Optimized images
Accessible form elements
Clean and commented code
Consistent naming conventions

Performance Considerations

Minimized HTTP requests
Optimized image sizes
Lazy loading for maps iframe
CSS organized for better maintenance

Browser Support

Chrome (latest)
Firefox (latest)
Safari (latest)
Edge (latest)
Mobile browsers

Known Issues

Map may not load without an internet connection
Form submission requires backend implementation
