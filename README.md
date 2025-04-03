# Personal Website

This is a personal website showcasing various sections such as a full-page background, navigation bar, photo gallery, video gallery, QR code, Q&A, and a contact form. The website is styled using CSS to create a visually appealing and responsive design.

## CSS Elements Used

### 1. **Full-Page Background**
   - **CSS Properties**:
     - `background-image`: Used to set a full-page background image.
     - `background-size`: Ensures the image covers the entire viewport.
     - `background-position`: Centers the image.
     - `background-attachment`: Fixes the background image while scrolling.
   - **Class**: `.full-page-image`

### 2. **Global Styles**
   - **CSS Properties**:
     - `color`: Sets the default text color to white.
     - `overflow-x`: Hides horizontal scrolling.
     - `box-shadow`: Adds shadows to sections for a 3D effect.
     - `backdrop-filter`: Adds a blur effect to section backgrounds.
   - **Class**: `html, body`, `section`

### 3. **Navigation Bar**
   - **CSS Properties**:
     - `position: fixed`: Keeps the navigation bar at the top of the page.
     - `display: flex`: Aligns navigation links horizontally.
     - `gap`: Adds spacing between navigation links.
     - `transition`: Smooth hover effects for links.
   - **Class**: `.topnav`, `.topnav a`, `.topnav a:hover`, `.topnav a.active`

### 4. **Photo Gallery**
   - **CSS Properties**:
     - `display: flex`: Creates a responsive grid layout for images.
     - `gap`: Adds spacing between images.
     - `transform`: Scales images on hover for a zoom effect.
   - **Class**: `.gallery`, `.gallery-image`, `.gallery-image:hover`

### 5. **Modal for Images**
   - **CSS Properties**:
     - `position: fixed`: Centers the modal on the screen.
     - `background-color`: Adds a semi-transparent background.
     - `display: none`: Hides the modal by default.
     - `:target`: Displays the modal when triggered.
   - **Class**: `.modal`, `.modal img`, `.modal:target`, `.close`

### 6. **Video Gallery**
   - **CSS Properties**:
     - `display: flex`: Aligns video containers in a responsive layout.
     - `border-radius`: Adds rounded corners to video containers.
     - `box-shadow`: Adds shadows for a polished look.
   - **Class**: `.video-gallery`, `.video-container`, `.video-container iframe`

### 7. **QR Code Section**
   - **CSS Properties**:
     - `text-align`: Centers the QR code and text.
     - `border`: Adds a border around the QR code image.
     - `box-shadow`: Adds depth to the QR code image.
   - **Class**: `.qr-code`, `.qr-image`

### 8. **Contact Form**
   - **CSS Properties**:
     - `display: flex`: Arranges form elements vertically.
     - `flex-direction: column`: Ensures a top-to-bottom layout.
     - `align-items: center`: Centers the form elements horizontally.
     - `padding`: Adds spacing inside the form container.
     - `background-color`: Adds a semi-transparent background to the form.
     - `box-shadow`: Adds a shadow for a modern look.
     - `transition`: Smooth hover effect for the submit button.
   - **Class**: `.contact-form`, `.contact-form label`, `.contact-form input`, `.contact-form textarea`, `.contact-form button`

### 9. **Responsive Design**
   - **CSS Properties**:
     - `max-width`: Limits the width of elements for better readability.
     - `width: 100%`: Ensures elements are responsive and adapt to smaller screens.
     - `flex-wrap`: Allows elements to wrap in flex containers.
   - **Classes Used**: Various classes across the site.

## Features
- **Full-Page Background**: A visually appealing background image that remains fixed while scrolling.
- **Navigation Bar**: A sticky navigation bar with smooth hover effects.
- **Photo Gallery**: A responsive image gallery with zoom effects and modals for larger views.
- **Video Gallery**: Embedded YouTube videos styled with rounded corners and shadows.
- **QR Code Section**: A QR code that links to the GitHub repository.
- **Contact Form**: A user-friendly form for visitors to send messages.