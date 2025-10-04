# SCT_WD_1

This is a responsive single-page website featuring a navigation bar (navbar) that dynamically changes its background color when the user scrolls down. The webpage is designed using HTML, CSS, and JavaScript, ensuring it works on all screen sizes (desktop, tablet, mobile). The navbar helps users easily navigate through different sections of the page, while the color change effect improves visual feedback and user experience.

**How It Works / Steps**

**HTML Structure**
1. The page has a <nav> element containing navigation links.
2. Multiple <section> elements or content blocks make up the page content.
3. Each section can be identified using ids for linking from the navbar.

**CSS Styling**
1. Navbar is fixed at the top so it stays visible while scrolling.
2. Default background color is set (e.g., transparent or light).
3. Scroll effect uses a new background color when the page is scrolled past a threshold (like 50px).
4. Responsive styles ensure the page layout adjusts for different screen sizes.

**JavaScript Functionality**

1. Detects scroll position of the page.
2. When the scroll position passes a certain point, a CSS class is added to the navbar to change its color.
3. Removes the class when scrolling back to the top.

**User Interaction**

1. Users can click the navbar links to jump to different sections.
2. Visual feedback is provided as the navbar changes color, indicating scrolling activity.
3. Responsive Behavior
On smaller screens, the navbar and page sections adjust automatically.

Optionally, a hamburger menu can be added for mobile devices.
