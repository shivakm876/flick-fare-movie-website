# FlickFare - Your Gateway to the Silver Screen

FlickFare is a simple and intuitive static movie booking website designed to provide users with an easy way to explore movies currently showing and coming soon, view detailed information, watch trailers, and simulate ticket bookings.

## Features

* **Comprehensive Movie Listings:** Browse an extensive collection of movies currently in theaters and those anticipated to be released soon.
* **Detailed Movie Information:** Each movie comes with a dedicated page displaying its poster, title, release date, audience rating, duration, genre, certification, and a brief synopsis.
* **Seamless Trailer Integration:** Easily access movie trailers directly from the movie details page with embedded YouTube links.
* **Interactive Seat Selection (Simulation):** A user-friendly interface allows for selecting preferred seats in a cinema hall, calculating the total cost, and confirming the simulated booking.
* **User Authentication (Client-Side Mock):** Includes basic sign-in and sign-up pages with client-side form validation for a mock user experience.
* **Team Showcase:** A dedicated "Our Team" page featuring profiles of the project members with links to their individual resumes.
* **Responsive Design:** Optimized for various screen sizes to provide a consistent viewing experience across desktops, tablets, and mobile devices.
* **Smooth UI/UX:** Utilizes CSS transitions and transformations for engaging visual effects, such as movie card hovers and button interactions.

## Technologies Used

* **HTML5:** For structuring all web pages and their content.
* **CSS3:** For extensive styling, layout, and visual enhancements, including animations and responsive media queries.
* **JavaScript (Vanilla JS):** Powers the dynamic aspects of the website, including:
    * Loading movie data from a JSON array.
    * Storing and retrieving movie information using `localStorage`.
    * Handling seat selection logic and calculating booking totals.
    * Managing modal pop-ups for slot booking and booking confirmation.
    * Client-side form validation for sign-in and sign-up forms.
* **Bootstrap 4 CDN:** Integrated into the sign-in page for enhanced styling and responsive components.
* **Font Awesome CDN:** Used for a wide range of icons, enhancing the visual appeal and usability.
* **Google Fonts:** Custom typography with 'Noto Sans' for general text and 'Unbounded' for headings.

## Project Structure
.
├── css/
│   ├── signin.css          # Styles for the sign-in page
│   ├── signup.css          # Styles for the sign-up page
│   └── style.css           # Main global styles for the website
├── images/
│   ├── blur.jpg            # Background image for signup/signin
│   ├── herobg.png          # Hero section background image
│   ├── logo.jpg            # Website logo
│   └── theatre.jpg         # Image for the home page hero section
├── fonts/                  # Likely contains fonts for material icons used in signup
│   └── material-icon/
│       └── css/
│           └── material-design-iconic-font.min.css
├── resumes/                # Folder containing individual team member resumes
│   ├── neha/
│   │   └── index.html
│   ├── geethika/
│   │   └── index.html
│   ├── shrutika/
│   │   └── index.html
│   ├── sivaganga/
│   │   └── index.html
│   └── sreelakshmy/
│       └── index.html
├── app.js                  # Main JavaScript logic for movie data, local storage, and interactions
├── coming-soon.html        # Page listing upcoming movies
├── currenlty-showing.html  # Page listing movies currently in theaters
├── index.html              # Home page of the website
├── layout.html             # Seat booking layout page
├── movie-desc.html         # Movie details page
├── signin.html             # User sign-in page
└── signup.html             # User sign-up page
## 🚀 Getting Started

To get a local copy up and running, follow these simple steps:

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/your-username/FlickFare.git](https://github.com/your-username/FlickFare.git) # Replace with your actual GitHub repository URL
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd FlickFare
    ```

3.  **Open `index.html`:**
    Simply double-click the `index.html` file or open it with your preferred web browser (e.g., Chrome, Firefox). No server-side setup or additional dependencies are required to run this project.

---

## 🎬 How to Use

* **Home (`index.html`):** Explore a quick overview of trending movies and navigate to other sections.
* **"Currently Showing" & "Coming Soon" (`currenlty-showing.html`, `coming-soon.html`):** Explore movies by their release status.
* **Movie Details (`movie-desc.html`):** Click on any movie poster to view its full information, including a synopsis and a link to its trailer.
* **Book Tickets (`layout.html`):** From a movie's description page, click "Book Ticket" to select your preferred date, time slot, and seats for a simulated booking.
* **Sign In/Sign Up (`signin.html`, `signup.html`):** Access the mock authentication pages. Please note that these are for demonstration purposes only and do not store user data persistently.
* **Team (`team.html`):** Learn more about the project contributors and view their resumes.

---
