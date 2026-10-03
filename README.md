# Cognifyz Level 2 - Task 3
## Advanced CSS Styling and Responsive Design

### Overview

This project is developed as part of the **Cognifyz Technologies Full Stack Development Internship – Level 2, Task 3**.

The objective of this task is to enhance the web application by introducing **advanced CSS styling, responsive design, CSS transitions, animations, Bootstrap components, and a structured multi-section layout**.

The application demonstrates how modern frontend technologies can be used to create an attractive, interactive, and responsive web interface that works across different screen sizes.

---

## Task Objective

The main objectives of this task are:

- Create a more complex webpage layout with multiple sections.
- Apply advanced CSS properties for improved styling.
- Implement CSS transitions and animations.
- Create a responsive user interface.
- Use Bootstrap for a consistent and responsive layout.
- Design attractive cards, navigation, buttons, and sections.
- Ensure the webpage adapts to desktop, tablet, and mobile screen sizes.

---

## Technologies Used

- **HTML5** - Used to create the structure of the webpage.
- **CSS3** - Used for advanced styling, layouts, transitions, and animations.
- **Bootstrap** - Used for responsive layouts and UI components.
- **JavaScript** - Used for basic user interactions.
- **Node.js** - Used as the server-side runtime environment.
- **Express.js** - Used for creating the web server and handling requests.
- **EJS** - Used for server-side rendering and dynamically generating HTML.
- **npm** - Used for dependency management.

---

## Key Features

### 1. Multi-Section Webpage

The application contains multiple sections to create a complete and structured webpage.

The main sections include:

- Home
- Features
- About
- Contact

Each section provides different information and contributes to the overall user experience.

### 2. Advanced CSS Styling

Modern CSS properties are used to improve the visual appearance of the application.

The styling includes:

- Gradient backgrounds
- Responsive layouts
- Cards
- Shadows
- Rounded corners
- Typography
- Spacing
- Hover effects
- Button styling
- Flexible layouts

### 3. Responsive Design

The webpage is designed to automatically adapt to different screen sizes.

The application supports:

- Desktop screens
- Laptop screens
- Tablet screens
- Mobile screens

Responsive design techniques are used to maintain a consistent and user-friendly layout across different devices.

### 4. CSS Transitions

CSS transitions are used to provide smooth visual changes when users interact with different elements.

For example, buttons and cards can provide smooth effects when the user moves the mouse over them.

### 5. CSS Animations

CSS animations are used to make the webpage more dynamic and interactive.

Animations are applied to selected elements to improve the visual presentation of the application.

### 6. Bootstrap Integration

Bootstrap is used to create a consistent and responsive user interface.

Bootstrap helps with:

- Responsive layouts
- Containers
- Grid system
- Buttons
- Cards
- Spacing
- Mobile-friendly design

### 7. Interactive Navigation

The application contains a navigation bar with links to different sections of the webpage.

The navigation includes:

- Home
- Features
- About
- Contact

Users can navigate between the different sections of the webpage.

### 8. Feature Cards

The Features section contains visually appealing cards representing:

- Modern CSS
- Responsive Design
- Animations

Each card provides information about the corresponding feature.

### 9. Contact Section

The Contact section provides a simple call-to-action for users who want to learn more about the project.

A contact button and interactive message are included in this section.



## Application Workflow


        User Opens Application
                 |
                 v
          Home Section
                 |
                 v
        Navigation Menu
                 |
       +---------+---------+
       |         |         |
       v         v         v
    Features   About    Contact
       |         |         |
       v         v         v
 Feature Cards Technologies Contact Button
       |         |         |
       +---------+---------+
                 |
                 v
        Responsive Interface


Responsive Design Workflow

              Web Application
                     |
                     v
             Responsive Layout
                     |
          +----------+----------+
          |          |          |
          v          v          v
       Desktop     Tablet     Mobile
          |          |          |
          v          v          v
      Multi-column  Adjusted   Stacked
        Layout       Layout     Layout

The layout automatically adjusts according to the available screen size to provide a better viewing experience.
Advanced CSS Techniques

The project demonstrates several CSS concepts.

Gradient Backgrounds

Gradient backgrounds are used in sections such as the Home and Contact sections to create a modern visual appearance.

Cards

Feature cards are designed using:

-Border radius
-Box shadows
-Spacing
-Responsive sizing
-Hover effects
-Flexbox

Flexbox is used to arrange elements and create flexible layouts.

CSS Grid

CSS Grid can be used to organize multiple elements into structured rows and columns.

Transitions

CSS transitions provide smooth visual effects when elements change their appearance.

Animations

CSS animations are used to create dynamic visual effects.

Media Queries

Media queries are used to adjust the webpage layout for different screen sizes.

Project Structure

Level2_Task3/
│
├── screenshots/
│   ├── home.png
│   ├── features.png
│   ├── about.png
│   └── contact.png
│
├── public/
├── views/
├── server.js
├── package.json
└── README.md


File Description

| File/Folder            | Description                                   |
| ---------------------- | --------------------------------------------- |
|  server.js             | Main Node.js and Express.js server            |
|  views/index.ejs       | Main webpage template                         |
|  public/css/style.css  | Contains custom CSS styling                   |
|  public/js/script.js   | Contains JavaScript functionality             |
|  public/images/        | Stores images used by the application         |
|  package.json          | Contains project information and dependencies |
|  package-lock.json     | Locks installed dependency versions           |
|  node_modules/         | Contains installed npm packages               |
|  README.md             | Project documentation                         |


How to Run the Project

Step 1: Clone the Repository

git clone <gundavarshini>

Step 2: Navigate to the Project

cd Level2_Task3

Step 3: Install Dependencies

npm install

If required, install Express and EJS:

npm install express ejs

Step 4: Start the Server

node server.js

Step 5: Open the Application

Open the local server URL in your browser.

For example:

http://localhost:3002
Application Sections

Home

The Home section introduces the project and displays the main heading:

Advanced CSS Styling

It also provides information about the responsive design implemented in the application.

Features

The Features section contains three feature cards:

-Modern CSS

-Responsive Design

-Animations

The section demonstrates the use of cards, icons, spacing, shadows, and responsive layouts.

About

The About section explains the purpose of the project and displays the technologies used.

The technologies include:

->HTML5

->CSS3

->Bootstrap

->Node.js

->Express.js

->EJS

->Contact

The Contact section provides a simple interaction area with a Contact Cognifyz button and a response message.

Screenshots

Home Section

<img width="1518" height="724" alt="image" src="https://github.com/user-attachments/assets/16fe0fd0-9918-482a-aa19-d06631742cd6" />

Features Section

<img width="1517" height="732" alt="image" src="https://github.com/user-attachments/assets/614376d2-478f-48f9-827b-337b427c8b12" />


About Section

<img width="1521" height="716" alt="image" src="https://github.com/user-attachments/assets/3927798a-64d1-4e95-84b7-a88cd2651639" />


Contact Section

<img width="1517" height="723" alt="image" src="https://github.com/user-attachments/assets/4c44988c-1569-4936-b1e7-7d6a031ae15b" />


Learning Outcomes

Through this task, I gained practical experience in:

1.Advanced CSS styling.

2.Creating multi-section webpages.

3.Designing responsive user interfaces.

4.Using Flexbox and CSS Grid.

5.Implementing CSS transitions.

6.Implementing CSS animations.

7.Working with Bootstrap.

8.Creating responsive layouts.

9.Designing interactive navigation.

10.Creating reusable UI components.

11.Working with Node.js and Express.js.

12.Using EJS for server-side rendering.

13.Testing web applications across different screen sizes.

Future Enhancements

The application can be further enhanced by adding:

->Dark mode.

->Advanced animations.

->Mobile navigation menu.

->Additional interactive components.

->Contact forms.

->Form validation.

->Database integration.

->User authentication.

->Improved accessibility.

->Additional responsive sections.

Internship Details

Organization: Cognifyz Technologies

Program: Full Stack Development Internship

Level: Level 2 - Intermediate

Task: Task 3 - Advanced CSS Styling and Responsive Design

Author

Varshini Reddy

GitHub: <gundavarshini>

Conclusion

This project demonstrates the implementation of advanced CSS styling and responsive web design using modern web development technologies.

The application combines HTML5, CSS3, Bootstrap, JavaScript, Node.js, Express.js, and EJS to create a structured, interactive, visually appealing, and responsive web interface.

Through this task, practical experience was gained in developing multi-section webpages, implementing advanced CSS techniques, creating responsive layouts, and integrating frontend components with a Node.js server environment.
