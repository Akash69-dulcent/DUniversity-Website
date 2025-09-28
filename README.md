# DUniversity Website

A responsive, multi-page university website template built with **HTML** and **CSS**, featuring a clean design and modern layout.

## 🚀 Key Features

* **Responsive Design:** Optimized for various screen sizes using **CSS media queries** for a great experience on desktop, tablet, and mobile (specifically targeting screens up to 700px wide).
* **Navigation Toggle:** A mobile-friendly navigation menu that can be toggled open and closed using a simple **JavaScript** implementation.
* **Hero Section:** Full-width header with a background image, text, and a call-to-action button.
* **Interactive Elements:**
    * **Navigation Links:** Hover effect on navigation links with a sliding underscore animation.
    * **Course Columns:** A simple background color change on hover.
    * **Campus Images:** A red color overlay (`.layer`) and a subtle text slide-up effect on hover.
    * **CTA Button:** Hover effects for both the main hero button and the call-to-action button in the dedicated section.
* **Sections Included:** Courses Offered, Global Campus, Facilities, Testimonials, and a final Call-to-Action.
* **Font Icons:** Uses **Font Awesome** for social media icons and the mobile menu icons (bars and times).

## 🛠️ Technologies Used

* **HTML5** (Structure)
* **CSS3** (Styling and Layout)
* **JavaScript** (For mobile menu toggle functionality)
* **Font Awesome** (Icons)

## 📂 Project Structure

This project consists of the following core files:

/
├── index.html       # The main website structure
├── index.css        # All the custom CSS styles
├── js/
│   └── menu-toggle.js # Placeholder for menu toggle script (currently inline in index.html)
└── eduford_img/     # Directory for all image assets (logo.png, banner.png, library.png, etc.)


**Note:** The menu toggle JavaScript logic is currently placed directly at the bottom of the `index.html` file within `<script>` tags, and the `js/menu-toggle.js` file is referenced but empty.

## ⚙️ Setup and Installation

To view and modify this project locally:

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd DUniversity-Website
    ```
3.  **Open `index.html`:** Simply open the `index.html` file in your web browser. All styles and scripts are linked locally.

## 🎨 Customization

* **Color Palette:** The primary red color is `#f44336`. The navigation text color is `#8f84f0`.
* **Backgrounds:** Change the background image and color overlay for the header in the `.header` rule within `index.css`.
* **Content:** All main text and link changes should be made in `index.html`.
* **Responsiveness:** Adjust the `max-width: 700px` media query in `index.css` to change the breakpoint for the mobile layout.

## 🤝 Contribution

Feel free to fork the repository, make improvements, and submit pull requests.

## 📝 License

[Specify your project's license here, e.g., MIT, ISC, or unlicense.]

## 🧑‍💻 Associated by

Akash Kumar (As noted in the footer)
