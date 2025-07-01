# Digital-marketing-Agency
## Digital Marketing Agency Website
This is a simple, single-page application (SPA) style website for a digital marketing agency, built with pure HTML, CSS (Tailwind CSS), and JavaScript. It features a responsive design, dynamic page loading, and simulated analytics tracking for various user interactions.

Table of Contents
Features

Pages

Analytics Tracking

How to Run

Project Structure

Customization

Features
Single Page Application (SPA) feel: Content for different pages (Home, Services, Contact Us) loads dynamically without full page reloads.

Responsive Design: Utilizes Tailwind CSS for a mobile-first, responsive layout.

Sticky Navigation: The header remains at the top of the viewport for easy navigation.

Smooth Scroll: "Back to Top" button for quick navigation to the top of the page.

Form Submission Modal: A "Thank You" modal appears upon successful contact form submission.

Simulated Google Analytics: Demonstrates how to track various user interactions (CTA clicks, form submissions, scroll depth, downloads) by logging events to the console.

Sample Brochure: Includes a separate HTML page acting as a sample brochure that can be "downloaded" (opened in a new tab).

Pages
The website consists of the following main sections, dynamically loaded into the main-content area:

Landing Page (Home):

Introduction to the agency.

"Why Choose Us?" section.

A prominent Call-to-Action (CTA) button to learn more about services, which scrolls to the brochure download section on the Services page.

Services Page:

Details about various digital marketing services (SEO, SMM, PPC, etc.).

"Download Our Full Brochure" section with a button to open the sample brochure.

Contact Us Page:

A contact form for inquiries.

Displays a "Thank You" modal upon successful submission.

Analytics Tracking
The website includes simulated Google Analytics (gtag) events that log to the browser's console. This demonstrates how you would implement tracking for:

CTA Clicks: Track clicks on various call-to-action buttons (cta_click event).

Triggers: Click Classes (track-cta), Click Text (e.g., "Learn More About Our Services").

Form Submissions: Track when the contact form is successfully submitted (form_submission event).

Triggers: Form Submit event on the form.

Scroll Depth: Track how far users scroll down a page (25%, 50%, 75%, 100% thresholds) (scroll_depth event).

Downloads: Track clicks on the brochure download button (file_download event).

Triggers: Click Classes (track-download).

Page Views: Track navigation between the simulated pages (page_view event).

Triggers: Page Path changes (simulated by JavaScript).

To view the simulated analytics events, open your browser's developer console (usually F12 or Right-Click -> Inspect -> Console) while interacting with the website.

How to Run
This website is a single HTML file and can be run directly in any modern web browser.

Save the code: Copy the entire HTML code from the marketing-website immersive into a file named index.html.

Save the brochure code: Copy the entire HTML code from the sample-brochure immersive into a file named sample-brochure.html in the same directory as index.html.

Open index.html: Double-click index.html in your file explorer, or open it in your web browser.

Project Structure
.
├── index.html            # Main website file
└── sample-brochure.html  # Sample brochure content

Customization
Content: Modify the pageContent JavaScript object in index.html to update text, images, and links for each section.

Styling: Adjust the Tailwind CSS classes directly in the HTML or add custom CSS within the <style> tags in index.html for more specific design changes.

Analytics: To integrate with actual Google Analytics, replace the gtag simulation function with the official Google Analytics script and your tracking ID.

Brochure: Replace the href="/sample-brochure" in index.html with the actual URL to your PDF brochure if you host one externally.
