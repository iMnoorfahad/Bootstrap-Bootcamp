---

### **1-Hour Class Plan for Day 2: Bootstrap Navigation & Forms**

---

### **0:00 - 0:05 (5 min) - Welcome & Recap**
1. **Welcome students back** and quickly review what was covered on Day 1 (Grid system, setting up Bootstrap).
2. **Introduction to today’s lesson**:
   - "Today, we’ll explore Bootstrap’s navigation bar and form components—key elements in most websites."
3. **Engage with a question**:
   - “What do you think is important in a good navigation bar and form design?”

---

### **0:05 - 0:20 (15 min) - Building Responsive Navigation Bars**
1. **Understanding the Navbar Component**:
   - Explain what a **Navbar** is and why it’s essential for website navigation.
   - Show Bootstrap's **Navbar component** and discuss the key classes like `.navbar`, `.navbar-expand-*`, and `.navbar-light`.
   
2. **Live Demo: Basic Navigation Bar**:
   - Create a simple navbar using Bootstrap:
     ```html
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
         <div class="container-fluid">
           <a class="navbar-brand" href="#">Navbar</a>
           <button
             class="navbar-toggler"
             type="button"
             data-bs-toggle="collapse"
             data-bs-target="#navbarNav"
             aria-controls="navbarNav"
             aria-expanded="false"
             aria-label="Toggle navigation"
           >
             <span class="navbar-toggler-icon"></span>
           </button>
           <div class="collapse navbar-collapse" id="navbarNav">
             <ul class="navbar-nav">
               <li class="nav-item">
                 <a class="nav-link active" aria-current="page" href="#">Home</a>
               </li>
               <li class="nav-item">
                 <a class="nav-link" href="#">Features</a>
               </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Dropdown
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li><hr class="dropdown-divider"></li>
                  <li><a class="dropdown-item" href="#">Something else here</a></li>
                </ul>
              </li>
               <li class="nav-item">
                 <a class="nav-link" href="#">Pricing</a>
               </li>
             </ul>
           </div>
         </div>
       </nav>
     ```
   
3. **Adding Dropdowns & Responsive Toggler**:
   - Explain how to add **dropdowns** in a navbar and how the navbar becomes **responsive** using the toggler for mobile devices.
   
4. **Real-life Example**: 
   - Briefly show how a navigation bar might look for a blog or a portfolio website.

---

### **0:20 - 0:35 (15 min) - Styling Forms with Bootstrap**
1. **Introduction to Bootstrap Forms**:
   - Explain why forms are important (e.g., for contact, login, signup, etc.).
   - Highlight the key classes (`.form-group`, `.form-control`, `.form-inline`, `.input-group`).

2. **Creating Basic Form Elements**:
   - Build a simple form with **input**, **select**, and **textarea** elements:
     ```html
     <form>
       <div class="form-group">
         <label for="name">Name</label>
         <input type="text" class="form-control" id="name">
       </div>
       <div class="form-group">
         <label for="email">Email</label>
         <input type="email" class="form-control" id="email">
       </div>
       <div class="form-group">
         <label for="message">Message</label>
         <textarea class="form-control" id="message"></textarea>
       </div>
       <button type="submit" class="btn btn-primary">Submit</button>
     </form>
     ```
   
3. **Adding Form Validation**:
   - Show how to add **validation classes** like `.is-valid` and `.is-invalid` to make forms more interactive.

4. **Real-life Example**:
   - Design a simple **contact form** for a freelance web developer’s site.

---

### **0:35 - 0:45 (10 min) - Customizing Navigation and Forms**
1. **Customizing the Navbar**:
   - Show how to change the **color schemes** of the navbar using classes like `.navbar-dark`, `.bg-dark`, etc.
   - Demonstrate **alignment options** for navigation links (e.g., using `.ml-auto` to align links to the right).
   
2. **Customizing Forms**:
   - Demonstrate how to **customize form styles** (e.g., custom colors, borders, padding).
   - Show how to add extra styling using classes or CSS.

3. **Real-life Example**: 
   - Customize the **contact form** and **navbar** for a school’s website (use a lighter background color and aligned elements to the right for a more professional look).

---

### **0:45 - 0:55 (10 min) - Hands-on Practice**
1. **Challenge the Students**:
   - Guide them to build a complete **navigation bar** with a dropdown, a brand logo, and responsive behavior.
   - Encourage them to create a **styled contact form** with inputs and validation using what they’ve learned.

2. **Live Coding Help**:
   - As students build, walk through some common mistakes and quick fixes they may encounter.

---

### **0:55 - 1:00 (5 min) - Q&A and Closing**
1. **Recap**:
   - Briefly review what you’ve covered today: creating and customizing **navbars** and **forms** in Bootstrap.
   
2. **Q&A**:
   - Open the floor for any questions and clarify doubts.
   
3. **Preview of Next Class**:
   - Tease the next session: "Tomorrow we’ll dive into even more Bootstrap components like buttons, cards, and more. You’ll be building more complex websites in no time!"

---

### **Final Breakdown:**
- **Introduction and Recap (5 min)**
- **Navbar Component (15 min)**: Explain and demonstrate responsive navigation bars.
- **Forms in Bootstrap (15 min)**: Demonstrate creating and styling forms with Bootstrap.
- **Customizing Navigation and Forms (10 min)**: Show customization techniques.
- **Hands-on Practice (10 min)**: Students build their navigation bar and contact form.
- **Q&A and Wrap-up (5 min)**
