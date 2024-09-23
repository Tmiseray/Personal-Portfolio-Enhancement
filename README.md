# Personal-Portfolio-Enhancement
 Coding Temple - Module 8 Mini-Project


This repository contains the code and resources for my enhanced personal portfolio website. This project builds on my previous portfolio by integrating advanced CSS techniques to make the site more visually engaging, interactive, and responsive. The enhanced design showcases my skills, projects, and background more effectively, offering a polished user experience for visitors.

## Overview
The Personal Portfolio is a static website built using HTML and CSS, with additional enhancements applied to improve both aesthetics and functionality. This site showcases various aspects of my work, including my biography, skills, project portfolio, and contact information.

## Key Features
1. **Navigation**
    - Every page includes navigation menus for user-friendly access to sections within my portfolio
    - Each navigation is reactive to hovering, clicking, and visited activity
    - Each navigation is also reactive to screen sizes, which adjusts them to be dropdown menus fixed at the top-left and top-right corners.
    - Main Navigation Bar
        * Fixed position across the top of every page
        * Includes quicklinks to the Home Page, About Me Section, Projects Page, and Contact Me Page
    - Individual Page Navigation Bars
        * This navigation menu is fixed to the left of every page
        * There is a scrollable aspect for different page sizes
        * **Home Page Navigation**
            - Profile Picture Styling: Enhanced presentation of the profile image with rounded corners, borders, and hover effects.
            - Quicklinks to About Me sections
        * **Projects Page Navigation**
            - Quicklinks to the beginning of each project's section
        * **Contact Me Navigation**
            - Embedded Profile Picture
            - Quicklinks for contact methods: LinkedIn, GitHub, Send Email, Send Text, Call Phone

2. **Home Page**
    - The landing page welcomes visitors with a brief introduction about me
    - Provides a concise snapshot of who I am and sets the tone for the rest of the site
    - Visual Appeal: A welcoming and professional color scheme with modern typography sets the tone for the website.
    - Interactive Elements: Smooth transitions and hover effects make the page dynamic and engaging.

    - **About Me Section**
        * Advanced Typography: Improved readability and layout using a combination of custom fonts, line spacing, and CSS text effects.
        * Offers more details about my personal and professional journey.
        * Highlights my transition from customer service to software development, with a focus on my creativity, problem-solving abilities, and attention to detail.
        * Structured Content: Organized and well-styled sections for education, career goals, interests, and background.
    - **Skills Section**
        * Professional Layout: Key information such as skills, certifications, and experience is highlighted with a clear, well-structured layout.
        * Features a visual representation of my technical skills
        * Includes programming languages, frameworks, tools, and software proficiency

3. **Projects Page**
    - Enhanced Visuals: Project descriptions are designed with structured layouts, incorporating both text and images in an eye-catching format.
    - Technologies/tools used in each project are listed for easy reference.

4. **Contact Page**
    - Styled Contact Form: The contact form is user-friendly, with clean layouts and interactive form fields.
    - Provides a engaging contact form, along with contact methods and links to social media profiles (LinkedIn, GitHub, etc.).

5. **Responsive Design**
    - Mobile-Friendly: The entire site is fully responsive, adapting to various screen sizes and devices using media queries.

6. **Technologies Used**
    - *HTML:* Structuring the content and sections across multiple pages.
    - *CSS:* Styling for a modern and visually appealing design.
    - *GitHub:* Used for version control and hosting the code.

7. **Interactive Styling**
    - CSS pseudoclasses like :hover, :active, and :focus are applied across navigation menus, buttons, and form fields, providing users with feedback during interaction.
    - Hover effects on buttons and links enhance user engagement.

8. **Advanced CSS Techniques**
    - Transitions and Animations: Smooth transitions and animations are used on elements like images and buttons to add interactivity.
    - Button Styling: Custom buttons feature rounded corners, hover animations, and shadow effects.

## Getting Started

### Prerequisites
* To run or modify this project, you will need:
    - A basic code editor (e.g., Visual Studio Code)
    - A browser (e.g., Chrome, Firefox) to view the portfolio

## Installation

### Clone the Repository:

*** **Cloning Option** ***
* If you have Git Bash installed, you can clone the repository using the URL
1. Create a 'Clone' Folder
2. Within the folder, right-click for Git Bash
3. From the GitHub Repository, click on the '<> Code' button and copy the link provided
4. Paste the link into your Git Bash and click 'Enter'
* If you have GitHub Desktop, when you click on the '<> Code' button you will have an option to 'Open with GitHub Desktop'
* If you have Visual Studio Code, when you click on the '<> Code' button you will have an option to 'Open with Visual Studio'
* [HTTPS] (https://github.com/Tmiseray/Personal-Portfolio-Enhancement.git)
* [SSH] (git@github.com:Tmiseray/Personal-Portfolio-Enhancement.git)
* [GitHubCLI] (`gh repo clone Tmiseray/Personal-Portfolio-Enhancement`)

*** **Download Option** ***
1. From the GitHub Repository, click on the '<> Code' button
2. Click on 'Download Zip'
3. Extract contents of Zip file

* **Open the Project:** 
    - Navigate to the cloned folder
    - Navigate to the `pages` folder
    - Open `home.html` in your preferred browser

### Project Structure
```bash
personal-portfolio/
│
├── pages/
│   └── home.html           # Home Page w/ About Me & Skills
│   └── projects.html       # Projects Page
│   └── contact.html        # Contact Page
│
├── style-sheets/
│   └── styles.css          # Custom Styles for Website
│   └── main-nav.css        # Custom Styles for Main Navigation
│   └── about-me-nav.css    # Custom Styles for About Me Navigation
│   └── projects-nav.css    # Custom Styles for Projects Page Navigation
│   └── contact-nav.css     # Custom Styles for Contact Page Navigation
│ 
└── images/
│   │
│   ├── game/               # Folder for Specified Project Images
│   │       └── [images] 
│   │ 
│   ├── timebot/
│   │       └── [images]  
│   │
│   ├── to-do-list/
│   │       └── [images] 
│   │
│   ├── contact-management/
│   │       └── [images] 
│   │
│   ├── library-management/
│   │       └── [images] 
│   │
│   ├── library-database/
│   │       └── [images] 
│   │
│   ├── e-commerce/
│   │       └── [images] 
│   │
│   ├── transaction-data-sim/
│   │       └── [images] 
│   │
│   └── [profile-picture] 
```
## Contribution
Contributions, suggestions, or improvements are welcome! Feel free to open an issue or submit a pull request if you'd like to enhance the project.