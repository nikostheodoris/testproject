# Angular Project Setup

This document collects the basic steps for setting up an Angular project and some ideas for structuring and improving it.

## Getting Started

1. **Install Node.js and npm**
   - Download and install Node.js from [nodejs.org](https://nodejs.org/). This also installs npm (Node Package Manager).

2. **Install Angular CLI**
   - Run:
     ```
     npm install -g @angular/cli
     ```
   - This installs the Angular command-line interface globally.

3. **Create a New Angular Project**
   - Navigate to the directory where you want the project.
   - Run:
     ```
     ng new my-angular-app
     ```
   - Choose your preferred routing and stylesheet options when prompted.

4. **Serve the Application**
   - Move into the project folder:
     ```
     cd my-angular-app
     ```
   - Start the development server:
     ```
     ng serve
     ```
   - Open `http://localhost:4200/` in your browser to see the app running.

5. **Project Structure Overview**
   - `src/app`: Modules, components, and services.
   - `src/index.html`: Main HTML file.
   - `src/styles.css` (or `.scss`): Global styles.
   - Use the CLI to generate additional components or services (`ng generate component my-component`).


