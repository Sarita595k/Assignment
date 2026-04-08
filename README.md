# Meera Industries - HDPE Piping Solutions Landing Page

Hey there! This is a high-fidelity landing page I built for Meera Industries. The goal was to take a complex industrial product—HDPE pipes—and present it through a clean, modern, and highly interactive interface.

* **The Scaling Issue:** Since industrial users often view sites on large monitors, I used `rem` units for almost everything. This means the layout scales beautifully on 1600px screens without the text looking tiny or the boxes looking out of place.
* **The Breadcrumb Trick:** I used the `IntersectionObserver` API so the breadcrumb at the top actually "listens" to where you are on the page. As you scroll into the Technical Specs or the FAQ, the breadcrumb updates in real-time.
* **Performance First:** I stuck to Vanilla JavaScript. No heavy libraries or bloated frameworks. The zoom effect on the product images and the FAQ toggles are all lightweight and fast.

## 🛠️ What's Inside?
* **Smart Product Gallery:** Features a hover-zoom and a thumbnail switcher for close-up inspections.
* **Full-Width Branding:** I used a "Wrapper-Container" pattern so the dark blue and gray backgrounds hit the edge of the screen, while the text stays safe inside a centered 1280px grid.
* **Responsive Flow:** I’ve added flex-wrapping to all major cards. If you shrink the screen, the content stacks naturally instead of breaking or overflowing.

## 📂 Project Structure
* `index.html` - The skeleton (Clean and SEO friendly).
* `style.css` - All the styling logic (Variables, Grid, and Media Queries).
* `scripts.js` - The "brain" (Zoom, Carousel, and Accordion logic).

## 🚀 How to Run It
Just clone the repo and open `index.html` in your browser. No build steps or installations needed!

---
**Author:** Sarita
*Building cool things.*
