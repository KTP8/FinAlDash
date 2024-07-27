# Financial Dashboard

![Screenshot 2024-07-27 at 09 43 23](https://github.com/user-attachments/assets/1314ae0a-7678-4047-933d-d50d8d154020)

## Table of Contents
1. [Introduction](#introduction)
2. [Technologies Used](#technologies-used)
3. [Features](#features)
4. [Testing](#Testing)
5. [Code Example](#code-example)
6. [Deployment](#deployment)
7. [Credits](#credits)
8. [Media](#media)

## Introduction: 

This project is a financial dashboard website that provides key financial metrics, market trends, and secuirty information to provide substance for UK based investors to conduct personal risk assesments. The purpose of this page is to serve as a blog/brief introductory to investing by outlining the key market indictaors that investors must monitor as well as the security threats posed by investing/use of online financial services. The finanical dashboard website also includes links to useful resources such as yahoo finance (for investment metrics) and action fraud (for reporting security threats).

*Financial Dashboard is a site which focuses on linking both experienced and novice investors with the information and tools which will help them to remain risk adverse and make informed investment decisions.*

## Technologies Used
- HTML5
- CSS3
- Hosted on GitHub Pages

## Features 

Financial Dashboard has an interactive landing page with a short "about us" description followed by an overview of its two subsequent pages "market" and "security". As well as navigation buttons on the page, Financial Dashboard also has a navigation bar featured on all three pages with the same destinations as the navigation buttons as well as a link back to the Home page (index.html). Although the website is catered for all level of investor, the market page provides information more relevant for the novice investor that wonders which indices are most important to their investment journey whilst the security page has universal applications to all levels of experience and also contains information on cybersecurity relevant to those who have little to no risk appetite for investment. 

### Exisiting Features 
- **Navigation Bar**
  - Featured on all three pages, the navigation bar has links to the Home page, Market page, and Security page and is identical in each for easy navigation.
  - The navigation bar is a fully resposnive design and changes size but remains in the top right corner depending on screen size.
  - The navigation bar icons change colour when hovered over to improve user accessibility.
 
  
  ![Screenshot 2024-07-27 at 10 42 16](https://github.com/user-attachments/assets/1947b64d-234e-4aae-abdb-b80d64c30b22)
  
 
- **Website Logo**
  - The Website Logo is featured on all pages in the top banner and serves the purpose of allowing users to see the site name on all three pages.
    
  ![Logo](https://github.com/user-attachments/assets/292b6a15-0b24-4439-8c7d-8c3400075783)

  
- **Embedded Media**
  - The Financial Dashboard uses an embedded youtube video to help educate users on cybersecurity risks.

   ![Screenshot 2024-07-27 at 09 32 36](https://github.com/user-attachments/assets/4501710d-4650-4c83-a574-cceb09262cbd)
 

 
- **The Landing Page**
 - The landing page (index.html) includes an AI generated image of stock market candlestick flow with the site name 'Financial Dashboard' as an overlay. Thsis overlay is also fully responsive and changes size subject to the device window being used.
  - The landing page introduces the user to the website with an eye-catching design whilst using colours which make it clear that the purpose of the site is informative.
    
![Screenshot 2024-07-27 at 09 33 13](https://github.com/user-attachments/assets/a34380d4-e431-49ba-a46d-f2af117d864d)


 
 
- **Market**
  - The Market page introduces the user to indices and metrics which are important to become familiar with when investing.
  - The Market page also includes an embedded link to Yahoo Finance where users can monitor stock performance further.

    
![Screenshot 2024-07-27 at 09 33 28](https://github.com/user-attachments/assets/7950717c-6d40-4679-8f5b-d1d16377204c)
![Screenshot 2024-07-27 at 09 33 42](https://github.com/user-attachments/assets/3e97c609-8823-4b9e-bea6-e02d481ee8d5)

 
- **Security**
  - The Security page enlightens the user to the security cybersecurity risks that, althugh are a threat to all computer users, are very commonly seen when investing and traversing websites that either request payments or give financial advice.
  - The Security page contains an embedded youtube video outlining an example of a cybersecurity attack, to enlighten the user of their threat and magnitude.
  - The Security page also includes embedded links for the user to both report cybersecurity attacks/suspicious activity and links to software which can help to protect them.

    
![Screenshot 2024-07-27 at 10 48 05](https://github.com/user-attachments/assets/4e24205b-c147-40a2-a79b-d6c3f27dbdb1)
![Screenshot 2024-07-27 at 10 48 19](https://github.com/user-attachments/assets/bec636b7-4970-4841-bac2-124126958d5d)



 
- **Features left to implement**
  - A sign-up for a weekly blog where users can stay up-to-date with geopolitical and economic factors affecting their investments.

## Testing  
- I have tested that this page works on the following browsers: Chrome, Safari, Firefox.
- I can confirm that the project is responsive and functions well whilst maintaining aesthetics on all standard screen sizes using lighthouse on the devtools device toolbar.
- I have confirmed that the navigation, about us, graphics, and site function are all easy to understand and readable, and have ensured that it is easy to watch the embedded video.
- I have confrimed that all interactive links and embedded media (youtube video) works.
- Financial Dashboard has been tested on every page using lighthouse for both desktop and mobile size and recieved the following rankings:


### Validator Testing 
- HTML
  - No errors were returned when passing through the official W3C validator.
- CSS
  - No errors were returned when passing through the official (Jigsaw) validator.

 
### Responsiveness
- The site was tested using lighthouse to assess its responsivness and useability, earning 100 for useability on desktop and 88 on mobile display:

![Screenshot 2024-07-27 at 09 36 42](https://github.com/user-attachments/assets/02880530-82f4-4b17-b740-e0f147f51c62)

### Bugs
- Initially, when deploying my project to GitHub Pages, I discovered the project was broken and had some issues with it loading due to an error with jekyll.
- There was also an issue with the header not loading and the logo design in the top left corner overhanging on the tool bar.
- I have fixed these bugs by altering the format in GitHub to fix the jekyll error & by styling the header, logo, and top-bar as follows:

      .images-container {
      display: flex;'
    'justify-content: space-between;'  /* Distributes space evenly between the images */
    'align-items: center;'  /* Aligns images vertically in the center */
'}'

'.inline-image {'
    'width: 23%;'  /* Adjusts width to fit 4 images within the container */
    'height: auto;'  /* Maintains aspect ratio */
'}'

/*Top Bar Styles */
'.top-bar {'
    'background-color: #182841;'  /* Blue background */
    'width: 100%;'
    'height: 50px;  /* Adjust height as needed */
    'display: flex;'
   ' align-items: center;  /* Center the logo and navigation vertically */
    'justify-content: space-between; /* Space between logo and navigation */
    'padding: 0 10px;  /* Padding for some spacing from the edges */
'}'


## Code Example 
How to implement a responsive navbar in CSS:
'.navbar ul {'
'list-style: none;'
'display: flex;' /*Aligns navigation items in a row*/
'justify-contnet:' flex-end; /*Aligns navigation items to the right*/
'}'

How to evenly distribute spaces between images: 
'.images-container {'
  'justify content: space between' /*Distributes space evenly between images*/
  'align items: center;' /*Aligns images in center*/ 
'}'

## Deployment 

**This site was deployed to GitHub pages. The steps to deploy are:**
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the Master Branch has been selected, the page will automatically refresh with a detailed ribbon display to indicate deployment was successful

  THE LIVE LINK CAN BE FOUND HERE: https://8000-ktp8-finaldash-2iz1xkckre5.ws.codeinstitute-ide.net/index.html 



## Credits 
- Coursera: html and CSS code course (used for taught methods not from code institute)
- Google Search: used to help find the correct commands to push logo image into top corner
- Youtube: used to find aid when writing navbar code and for embedded video
- ChatGPT: used in consolidating written elements from data collected by Project Owner (to check comprehension) and to alter code for 'head' element with reminder to include meta charset = UTF-8
- Imgur: used to generate image urls
- Yahoo Finance: used for data included on 'market.html'


## Media 
- Pixabay: used for copyright free AI generated images
- Google finance: used for charts
- SciShow: creator of embeded video
