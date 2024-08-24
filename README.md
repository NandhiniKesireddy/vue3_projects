# Vue 3 Practice Applications

## Overview

This repository contains a collection of practice applications developed using Vue 3. The purpose of these applications is to solidify my understanding of Vue 3 concepts, including the Composition API, reactive state management, component-based architecture, routing, and more. Each application focuses on different aspects of Vue.js and web development to enhance my skills.

## Technologies Used

- **Vue 3**: The progressive JavaScript framework used for building user interfaces.
- **Vue Router**: For managing the navigation between different components and views.
- **Pinia/Vuex**: For state management, depending on the application.
- **Axios**: For making HTTP requests to APIs.
- **HTML5 & CSS3**: For structuring and styling the applications.
- **JavaScript (ES6+)**: The primary scripting language used.
- **Vite**: For project scaffolding and development build tool.
- **Git**: For version control and collaboration.

## Applications

### 1. **Task Manager**
   - **Description**: A simple task management application to add, edit, delete, and mark tasks as completed. This application demonstrates the use of the Composition API and reactive state management.
   - **Features**:
     - Add and remove tasks.
     - Edit existing tasks.
     - Mark tasks as complete.
   - **Key Concepts**:
     - Composition API
     - Reactive state
     - Component communication
   - **Project Setup**:
     ```bash
     cd task-manager
     npm install
     npm run dev
     ```

### 2. **Weather App**
   - **Description**: A weather application that fetches data from a public API and displays current weather information for a given city.
   - **Features**:
     - Search for weather by city.
     - Display current temperature, weather conditions, and more.
     - Error handling for invalid city names.
   - **Key Concepts**:
     - API integration with Axios
     - Handling asynchronous operations
     - User input handling
   - **Project Setup**:
     ```bash
     cd weather-app
     npm install
     npm run dev
     ```

### 3. **E-commerce Product Page**
   - **Description**: A mock e-commerce product page displaying a list of products with features like search, filtering, and sorting.
   - **Features**:
     - Search products by name.
     - Filter products by category.
     - Sort products by price or rating.
   - **Key Concepts**:
     - Dynamic components
     - Props and state management
     - Routing with Vue Router
   - **Project Setup**:
     ```bash
     cd ecommerce-product-page
     npm install
     npm run dev
     ```

### 4. **Blog Platform**
   - **Description**: A simple blog platform allowing users to read, create, edit, and delete posts.
   - **Features**:
     - Create and edit blog posts.
     - View a list of blog posts.
     - Delete posts.
   - **Key Concepts**:
     - CRUD operations
     - Form handling
     - Component lifecycle hooks
   - **Project Setup**:
     ```bash
     cd blog-platform
     npm install
     npm run dev
     ```

### 5. **Portfolio Website**
   - **Description**: A personal portfolio website showcasing projects, skills, and contact information.
   - **Features**:
     - Responsive design.
     - Smooth scrolling navigation.
     - Contact form.
   - **Key Concepts**:
     - Single Page Application (SPA)
     - CSS animations and transitions
     - Custom directives
   - **Project Setup**:
     ```bash
     cd portfolio-website
     npm install
     npm run dev
     ```

## How to Run the Applications

1. Clone this repository to your local machine:
   ```bash
   git@github.com:NandhiniKesireddy/vue3_projects.git
   ```
Navigate to the directory of the application you want to run.

## Install the necessary dependencies:

```bash
npm install
```
## Start the development server:

```bash
npm run dev
```
Open your browser and navigate to 
```bash 
http://localhost:5173 (default port for Vite).
```

## Future Enhancements
Implement unit and integration tests using Jest.
Add TypeScript support for type safety.
Improve the UI/UX using a component library like Vuetify or BootstrapVue.
Deploy applications to Netlify or Vercel for public access.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
Thanks to the Vue.js community for the extensive documentation and support.
API providers for free access to data used in these applications.
Contact
For any questions, suggestions, or feedback, feel free to reach out via email.
