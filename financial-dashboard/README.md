# Financial Dashboard

## Table of Contents
1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Assets](#assets)
4. [Pages](#pages)
5. [Setup Instructions](#setup-instructions)
6. [Features](#features)
7. [Testing](#testing)
8. [Code Examples](#code-examples)
9. [Contributing](#contributing)
10. [Credits](#credits)
11. [License](#license)

## Introduction
This project has been written by Kiran Taylor-Patel as a submission for Portfolio 1 (Code Institute: Diploma in Full Stack Development). 
This project is a financial dashboard website that provides key financial metrics, market trends, and secuirty information relevant to UK based investors. The purpose of this page is to serve as a blog/brief introductory to investing by outlining the key market indictaors that investors must monitor as well as the security threats posed by investing/use of online financial services. The finanical dashboard website also includes links to useful resources such as yahoo finance (for investment metrics) and action fraud (for reporting security threats).

## Technologies Used
- HTML5
- CSS3
- Hosted on GitHub Pages

## Assets 
- styles.css

## Pages 
- index.html (Home: Introduction and Overview)
- market.html (Outline of Market Indices to Examine & Become Familiar with)
- security.html (Information regarding Cybersecurity Risks Users are Vulnerable to when Investing)

## Setup Instructions 
Clone the repository to local machine:
'''bash
git clone https://github.com/ktp8/FinAlDash/financial-dashboard.git

Navigate to project directory:
cd financil-dashboard 

Open the 'index.html' file in browser to view the project.

## Features 
- Market Insights: Detailed analytics and trends useful to investing in the UK market.
- Security Risk Assesments: Up-to-date information on potential security threats and vulnerabilities.
- Responsive Design: Fully responsive web design that adjusts to various devices and screen sizes.

## Testing  
- I have tested that this page works on the following browsers: Chrome, Safari, Firefox.
- I can confirm that the project is responsive and functions well whilst maintaining aesthetics on all standard screen sizes using lighthouse on the devtools device toolbar.
- I have confirmed that the navigation, about us, graphics, and site function are all easy to understand and readable, and have ensured that it is easy to watch the embedded video.
- I have confrimed that all interactive links and embedded media (youtube video) works.

## Bugs
- Initially, when deploying my project to GitHub Pages, I discovered the project was broken and had some issues with it loading due to an error with jekyll.
- There was also an issue with the header not loading and the logo design in the top left corner overhanging on the tool bar.
- I have fixed these bugs by altering the format in GitHub to fix the jekyll error & by styling the header, logo, and top-bar as follows:
  ###
  .images-container {
    display: flex;
    justify-content: space-between;  /* Distributes space evenly between the images */
    align-items: center;  /* Aligns images vertically in the center */
}

.inline-image {
    width: 23%;  /* Adjusts width to fit 4 images within the container */
    height: auto;  /* Maintains aspect ratio */
}

/* Top Bar Styles */
.top-bar {
    background-color: #182841;  /* Blue background */
    width: 100%;
    height: 50px;  /* Adjust height as needed */
    display: flex;
    align-items: center;  /* Center the logo and navigation vertically */
    justify-content: space-between; /* Space between logo and navigation */
    padding: 0 10px;  /* Padding for some spacing from the edges */
}


## Code Examples 
How to implement a responsive navbar in CSS:
.navbar ul {
list-style: none;
display: flex; /*Aligns navigation items in a row*/
justify-contnet: flex-end; /*Aligns navigation items to the right*/
}

How to evenly distribute spaces between images: 
.images-container {
  justify content: space between /*Distributes space evenly between images*/
  align items: center; /*Aligns images in center*/ 
}


## Contributing 
Contributions welcome - for major changes please first open an issue to discuss changes 

## Credits 
- Kiran Taylor-Patel: Sole Developer/Project Owner
- Coursera: html and CSS code course (used for taught methods not from code institute)
- Google Search: used to help find the correct commands to push logo image into top corner
- Youtube: used to find aid when writing navbar code and for embedded video
- ChatGPT: used in consolidating written elements from data collected by Project Owner (to check comprehension) and to alter code for 'head' element with reminder to include meta charset = UTF-8
- Imgur: used to generate image urls
- Pixabay: used for copyright free AI generated images
- Yahoo Finance: used for data included on 'market.html'
- SciShow: creator of embeded video

##License

This project is licensed under the Code Academy license.

##Images of Finished Project:
