# ps-info-template

Case Study you can use as a template to create a web-based dialog system that covers the information stage of a public service. This system includes two main elements, a questionnaire and a number of questions (with their answers) that are frequently asked by citizens about this service, known as FAQs. It was created in order to inform citizens whether or not they are eligible for the public service and to provide information on the documents required.

You can visit the web-based dialogue system [here](https://govgr-mobility-card.github.io/info-for-mobility-card-gr/).

## Requirements

To use and modify this project, you need the following:

- A modern web browser (Chrome, Firefox, Safari, etc.)
- Visual Studio Code (VSCode) or another code editor
- Live Server extension for VSCode \*\* (or an equivalent development server like Apache)
- Basic knowledge of HTML, CSS, and JavaScript

\*\* [Live Server Extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer): Go to the Extensions view by clicking on the Extensions icon in the Sidebar or pressing Ctrl+Shift+X. Search for "Live Server" and install the extension by Ritwick Dey (OR search with id = ritwickdey.LiveServer). 

## Setup Instructions

### 1. Clone the Repository

First, clone this repository to your local machine. Open a terminal (CMD) in a folder and run:

```sh
   git clone https://github.com/govgr-mobility-card/ps-info-template.git
```

### 2. Open the project folder in VSCode:

Open the project folder in VSCode and start the Live Server (click 'Go Live' at the bottom-right). You will see a port number, e.g., "Port:XXXX". Open the HTML file you want to preview in the browser using this port (e.g., http://localhost:5500/).

## Navigating the Project

The project structure is as follows:

```sh
project
│
├── index.html # Main HTML file
├── styles.css # Custom CSS styles
├── js/
│ ├── jquery-functions.js # Custom jQuery functions to fetch Questions, Evidences, FAQs and to handle answers in the questionnaire
│ └── change-language-functions.js # Language switch functions
├── questions-utils/
│ ├── all-questions-en.json # has all questions&answers in english
│ ├── all-questions.json # has all questions&answers in greek
│ ├── cpsv-en.json # has all Evidences in english
│ ├── cpsv.json # has all Evidences in greek
│ ├── faq-en.json # has all FAQs questions&answers in english
│ ├── faq.json # has all FAQs questions&answers in greek
└── README.md # Project documentation
```
## Deployment Instructions

To deploy your site to github pages you need to: 
1. Make the repo public (unless you have a pro github account). 
2. Go to settings
3. From the menu at the left side of the page select "Pages"
4. Select this options -> Source: "Deploy from a branch" & Branch: The branch you want to deploy (Prefer to merge all your branches to the main branch and deploy this one)

## Acknowledgments

This project was developed as part of a thesis assignment. Special thanks to our professors and mentors for their guidance and support.
