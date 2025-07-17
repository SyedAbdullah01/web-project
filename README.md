## Web Project - Zameen.com Front-End Clone

A pixel-perfect front-end clone of Zameen.com built for academic purposes demonstrating modular design, responsiveness, and client-side data management.

---

### 📋 Contents

* [Demo](#demo)
* [Features](#features)
* [Technologies](#technologies)
* [Project Structure](#project-structure)
* [Installation](#installation)
* [Usage](#usage)

---

### 🔍 Demo

Open the `index.html` in your browser or serve it via a local HTTP server to explore the following pages:

1. **Home**: Hero banner, search bar, featured listings
2. **Listings**: Browse properties with filtering
3. **Property Details**: Detailed view of a selected property
4. **Agents**: List of real estate agents
5. **Add Property**: Form to submit new properties
6. **About Us**: Company information
7. **Contact Us**: Contact form
8. **Login / Sign Up**: Authentication mock-ups
9. **Society Maps**: Location maps
10. **Terms of Use**: Site policies

---

### ✨ Features

* Modular JavaScript using ES6 modules
* Dynamic content management via a single `data.js` file
* Responsive layout with Bootstrap 5 and custom CSS
* Client-side form validation
* Clean, reusable components

---

### 🛠 Technologies

* HTML5
* CSS3
* Bootstrap 5
* TailwindCSS
* JavaScript (ES6+)
* [Git](https://git-scm.com/) for version control

---

### 🗂 Project Structure

```
web-project/
│
├── index.html            # Homepage
├── listings.html         # Property listings
├── property-details.html # Single property detail
├── agents.html           # Agent directory
├── add-property.html     # Property submission form
├── about-us.html         # About page
├── contact-us.html       # Contact form
├── login.html            # Login mock-up
├── sign-up.html          # Sign-up mock-up
├── society-maps.html     # Society maps
├── terms of use.html     # Terms of use page
│
├── homepage.js           # Homepage functionality
├── agents.js             # Agents page logic
├── data.js               # Shared dynamic content data
│
└── assets/               # Images & icons
    ├── icons/
    └── images/

```

---

### 💾 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/SyedAbdullah01/web-project.git
   cd web-project
   ```

2. **Serve files**

   For full ES6 module support, use a local HTTP server. Example:

   ```bash
   # Python 3
   python3 -m http.server 8000

   # Node.js
   npx http-server .
   ```

---

### 🚀 Usage

1. Navigate to `http://localhost:8000` in your browser.
2. Explore pages via the navigation bar.
3. Modify `data.js` to update site-wide content.

---
