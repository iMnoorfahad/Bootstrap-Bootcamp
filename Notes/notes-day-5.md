# Day 5: Project Day - Building a Complete Website with Custom Bootstrap

---

## 0:00 - 0:05 (5 min) - Welcome & Recap
1. **Welcome the students** and briefly recap what has been covered so far: **Bootstrap components**, **grid system**, **utilities**, and **advanced layouts**.
   
2. **Introduce today's project**:
   - “Today, we will build a **complete web page** using everything we've learned, focusing on customizing Bootstrap to fit our design. We’ll build a page with a **navbar**, **hero section**, **about us**, **contact form**, and **footer**."

---

## 0:05 - 0:15 (10 min) - Setting Up the Project
1. **Explain the project structure**:
   - The project will include sections such as:
     - **Navbar**
     - **Hero Section**
     - **About Us**
     - **Contact Form**
     - **Footer**

2. **Provide the project starter files**:
   - You can share basic HTML and CSS starter files for the project or let students set it up from scratch with Bootstrap via **CDN** or a **local installation**.

3. **Create a simple HTML template**:
   ```html
   <!DOCTYPE html>
   <html lang="en">
   <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Bootstrap Project</title>
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css">
   </head>
   <body>
     <!-- Content goes here -->
   </body>
   </html>
   ```

---

## 0:15 - 0:25 (10 min) - Building the Navbar
1. **Create a responsive navigation bar**:
   - Use Bootstrap's **navbar component**.
   - Include links such as **Home**, **About Us**, **Contact**, etc.
   - Add a **dropdown** and a **navbar-toggler** for responsiveness.

2. **Real-life Example**: 
   - Show how to design a clean, minimalistic navbar for a **portfolio site**.

   ```html
   <nav class="navbar navbar-expand-lg navbar-light bg-light">
     <div class="container-fluid">
       <a class="navbar-brand" href="#">MySite</a>
       <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
         <span class="navbar-toggler-icon"></span>
       </button>
       <div class="collapse navbar-collapse" id="navbarNav">
         <ul class="navbar-nav ms-auto">
           <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
           <li class="nav-item"><a class="nav-link" href="#">About Us</a></li>
           <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
         </ul>
       </div>
     </div>
   </nav>
   ```

---

## 0:25 - 0:35 (10 min) - Building the Hero Section
1. **Create the hero section**:
   - Design a **full-width section** using a background image or solid color.
   - Add a **heading**, **subheading**, and a **call-to-action button**.

2. **Customization**:
   - Modify Bootstrap classes to change the **font**, **spacing**, and **background** using custom CSS.
   - Example:
   ```html
   <section class="hero bg-dark text-white text-center py-5">
     <div class="container">
       <h1>Welcome to My Website</h1>
       <p>Your success starts here.</p>
       <a href="#" class="btn btn-primary mt-3">Get Started</a>
     </div>
   </section>
   ```

---

## 0:35 - 0:45 (10 min) - About Us Section & Customizing Bootstrap
1. **Create the About Us section**:
   - Design a simple **two-column layout** using Bootstrap’s grid system.
   - Add a **heading**, some **text**, and **images** or **icons**.

2. **Customizing Bootstrap styles**:
   - Show how to **override Bootstrap’s default styles** with custom CSS.
   - Example:
   ```css
   .hero h1 {
     font-size: 3rem;
     color: #f8f9fa;
   }

   .about-us h2 {
     color: #007bff;
     font-weight: bold;
   }
   ```

   - Example for the About Us section:
   ```html
   <section class="about-us py-5">
     <div class="container">
       <div class="row">
         <div class="col-md-6">
           <h2>About Us</h2>
           <p>We are a team of passionate developers dedicated to making the web a better place.</p>
         </div>
         <div class="col-md-6">
           <img src="team.jpg" class="img-fluid" alt="Our Team">
         </div>
       </div>
     </div>
   </section>
   ```

---

## 0:45 - 0:50 (5 min) - Building the Contact Form
1. **Create a contact form using Bootstrap**:
   - Use the **form component** to build a **responsive contact form** with **input fields**, **textarea**, and a **submit button**.
   - Include **form validation** classes for better UX.

   ```html
   <section class="contact py-5">
     <div class="container">
       <h2 class="text-center mb-4">Contact Us</h2>
       <form>
         <div class="mb-3">
           <label for="name" class="form-label">Name</label>
           <input type="text" class="form-control" id="name" required>
         </div>
         <div class="mb-3">
           <label for="email" class="form-label">Email</label>
           <input type="email" class="form-control" id="email" required>
         </div>
         <div class="mb-3">
           <label for="message" class="form-label">Message</label>
           <textarea class="form-control" id="message" rows="4" required></textarea>
         </div>
         <button type="submit" class="btn btn-primary">Send Message</button>
       </form>
     </div>
   </section>
   ```

---

## 0:50 - 0:55 (5 min) - Footer Section
1. **Create a simple footer**:
   - Include links and basic contact info in the footer.
   - Style the footer using **Bootstrap classes** for spacing and alignment.

   ```html
   <footer class="bg-dark text-white text-center py-4">
     <p>&copy; 2024 MyWebsite. All Rights Reserved.</p>
     <p>
       <a href="#" class="text-white">Privacy Policy</a> |
       <a href="#" class="text-white">Terms of Service</a>
     </p>
   </footer>
   ```

---

## 0:55 - 1:00 (5 min) - Wrap-up & Q&A
1. **Summarize the project**:
   - “Today we created a complete webpage using **Bootstrap components**, and we customized Bootstrap styles to fit our design needs.”
   
2. **Q&A**:
   - Allow students to ask any questions or clarifications.

3. **Tease future projects**:
   - Encourage students to practice by building more sections or tweaking the design.

---

## Final Breakdown:
- **Welcome & Recap (5 min)**: Quick recap of past classes.
- **Setting Up Project (10 min)**: Overview of the project and starter files.
- **Navbar (10 min)**: Create a responsive navigation bar.
- **Hero Section (10 min)**: Design a hero section with customization.
- **About Us & Customization (10 min)**: Build About Us section and apply custom styles.
- **Contact Form (5 min)**: Create and style a contact form.
- **Footer (5 min)**: Build a simple footer.
- **Wrap-up & Q&A (5 min)**: Conclude the project, take questions.

---
