### **Phase 5 Capstone Project Guidelines: What’s Expected (In No Uncertain Terms)**

You’ve made it to **Phase 5**. Now, it’s time to prove that you can apply what you’ve learned in a **full-stack software engineering project**. This is your Capstone Project, which means that your work will be a reflection of your ability as a developer. There's no **half-hearted effort** or **"I'll finish later"** attitude allowed. Here, you’re building something that could sit in your portfolio, show to potential employers, and demonstrate that you’re **job-ready**.

If your project fails to meet the **minimum expectations** laid out below, **you will not pass**—period. This is not just about putting things together; it’s about building something **robust, functional, and well-structured**.

#### **Minimum Sufficient Scope for Your Capstone Project (What We Expect)**

1. **A Real, Functional Web Application**  
   You’re building a **real, working web application**—not a toy project, not a simple to-do app, but something that **feels like a production-level product**. Whether you’re building an e-commerce platform, a social app, or a project management tool, it must provide clear functionality that users can interact with.  
   
   **Ask yourself:**
   - Does this project serve a real purpose?
   - Can users achieve specific goals using your app (create accounts, manage items, etc.)?
   - Does your app solve a problem, even in a simplified form?

2. **Flask + SQLAlchemy Backend**  
   Your backend will be built using Flask and SQLAlchemy. If your project lacks proper structure here, your app is fundamentally broken. Flask will handle routing, while SQLAlchemy is responsible for your database models and relationships. This means:
   - **RESTful API design**: You need to implement clean, concise routes that follow REST conventions.
   - **Database interactions**: CRUD operations must be handled via SQLAlchemy models, not raw SQL queries.
   - **Complex relationships**: Include **one-to-many**, **many-to-many**, and **one-to-one** relationships where necessary.
   - **Controllers and Services**: Organize your business logic well. If your Flask app is a monolith of poorly structured code, it will not be considered sufficient.

   **Sufficient example:**
   - An e-commerce app with models for **Products**, **Categories**, **Users**, and **Orders**.
   - Orders can have many products (many-to-many), and products can belong to multiple categories (many-to-many).
   - The app allows users to **register**, **log in**, and **place orders**, with CRUD operations available for products.

3. **Four Models Minimum**  
   **Four fully-implemented models** are required at a minimum. Each model should have fields, relationships, and be tied to clear functionality in your app. The models can’t just exist on paper—you must demonstrate their **real-world use**. Models should represent the core entities in your application. 
   
   **Sufficient models:**
   - **User Model**: To handle user authentication, profiles, etc.
   - **Post Model**: For a blog or social media app.
   - **Comment Model**: To handle comments on posts.
   - **Like Model**: To handle user likes on posts.

4. **Many-to-Many Relationship**  
   This is a fundamental part of your database schema and should be **implemented correctly**. If you can’t demonstrate an understanding of complex relationships, you haven’t learned enough to pass.
   
   **Sufficient example:**
   - A user can belong to many groups, and a group can have many users (many-to-many via a join table).
   - Products can belong to multiple categories, and categories can contain multiple products.

5. **Five Frontend Routes (Using React Router)**  
   Implement at least five **distinct routes** on the client-side using **React Router**. This means your application must have a frontend that behaves like a single-page application (SPA). It’s not just about clicking buttons—you need to manage state and navigation effectively.
   
   **Sufficient routes:**
   - `/login`: User authentication page.
   - `/dashboard`: User's home screen.
   - `/profile`: User profile details and edit page.
   - `/posts`: List of all posts.
   - `/post/:id`: View a single post in detail.

6. **Full CRUD on at Least 1 Model (RESTful)**  
   At least one of your models should have full **Create**, **Read**, **Update**, and **Delete** functionality that is fully REST-compliant. This means that users can interact with the data stored in that model through clear API endpoints, and the frontend should allow users to do this interactively.

   **Sufficient example:**
   - A user can **create**, **view**, **edit**, and **delete** a blog post.
   - The UI should reflect these actions: a form to create/edit a post, buttons to delete, and lists to view the content.

7. **Validations and Error Handling**  
   Don’t expect to pass if you’re letting users submit garbage data. Your application should validate all incoming requests and handle errors gracefully. This includes client-side validations to give immediate feedback to users and backend validations to ensure the data entering the database is clean.
   
   **Sufficient example:**
   - Form validation in React with meaningful error messages.
   - Backend validations for email uniqueness, password length, etc.
   - Custom error messages for failed API calls.

8. **Implement Something New (Beyond the Curriculum)**  
   To pass, you must show that you can learn and integrate **something new** that wasn’t covered in the course. This could be a **third-party library**, a more complex authentication system, or even a new frontend feature. It should challenge you but still be within reason.
   
   **Sufficient examples:**
   - Implementing **social login** (e.g., Google or Facebook OAuth).
   - Building a **custom hook** for API data fetching with error handling.
   - Integrating **Stripe** for payment processing.

9. **State Management with useContext or Redux**  
   You must manage state across your app using either **useContext** or **Redux**. This requirement is non-negotiable. If your state management is basic or relies entirely on local component state, you’re not demonstrating that you can handle a real-world app’s complexity.
   
   **Sufficient example:**
   - useContext for managing user authentication status and roles.
   - Redux for managing global state for cart items in an e-commerce app.

---

### **What Defines Success? (Beyond the Minimum)**

1. **Well-Organized Code**  
   Your code should be **readable, well-structured, and modular**. If you’re shoving all your logic into one file or creating confusing naming conventions, your project is not up to standard. Follow best practices for organizing both your backend (Flask) and frontend (React).

   **Sufficient example:**
   - Separate routes, controllers, and services on the backend.
   - Component-based design for React with clear folder structures.

2. **Comprehensive Testing**  
   Your project must include tests for key functionality. If you’re ignoring tests, it shows you haven’t embraced a critical part of the development process. **Backend unit tests and frontend integration tests** are expected.

   **Sufficient example:**
   - Write unit tests for Flask routes.
   - Test React components to ensure proper rendering and functionality.

3. **Efficient UI/UX**  
   Your project doesn’t need to look like it was built by a professional designer, but it does need to be **usable**. The user should be able to navigate your application intuitively, with **clear instructions and feedback**.

   **Sufficient example:**
   - Forms are properly aligned, with error messages displayed.
   - Loading spinners for asynchronous actions.
   - Buttons and links are clear and visible.

4. **Performance and Optimization**  
   This isn’t a beginner project anymore. Your app should be optimized for performance, with **paginated data fetching** and **clean API calls**. If your app slows down or breaks under minimal stress, it’s not ready for real-world use.

   **Sufficient example:**
   - Paginate data for large lists (e.g., posts, products).
   - Optimize image loading by serving properly sized images.
---

### **Final Thoughts**

Your Capstone Project isn’t just about **doing enough** to pass. It’s about demonstrating that you can **build something real**. You’re a developer. This project is your opportunity to show that you’re ready to enter the workforce and deliver **production-level code**. **Sloppy work, unfinished features, or untested code will not be accepted.**

This is your chance to **prove** that you can take an idea from conception to completion, following best practices and using all the tools you’ve learned.
