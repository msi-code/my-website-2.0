# EcoTech Solutions Website

## 🌍 Project Description
EcoTech Solutions is a responsive, eco‑friendly themed website designed to showcase services, staff, and contact information.  
The site emphasizes sustainability with a green color palette, clean layouts, and user‑friendly navigation.  
It was built as part of a practical learning project, aligning with the POE checklist requirements.

---

## 🖼️ Layout Overview
- **Header**  
  - Logo placement on the left.  
  - Navigation bar with links to Home, About Us, Services, Contact, and Enquiry.  

- **Main Content**  
  - Centralized sections with eco‑green backgrounds.  
  - Headings styled with text shadows and uppercase formatting.  

- **Staff Section**  
  - Grid layout using flexbox.  
  - Staff cards with images, names, and hover effects.  

- **Contact Form**  
  - Centered form with fields for name, email, and enquiry.  
  - Styled with rounded corners, shadows, and responsive alignment.  

- **Footer**  
  - Eco‑green background with white text.  
  - Contains copyright.

---

## 📱 Responsiveness
- **Desktop**: Full layout with wide spacing and multiple staff cards per row.  
- **Tablet (≤1024px)**: Reduced padding, staff cards display two per row, headings scale down.  
- **Mobile (≤768px)**:  
  - Header stacks vertically.  
  - Navigation links become a centered column.  
  - Staff cards display one per row.  
  - Contact form shrinks with reduced padding for readability.

---

## 📝 Changelog
### Part 1
- Created basic HTML structure (index, about, services, contact, enquiry).  
- Added navigation bar and footer.  
- Implemented staff section and contact form.  
- Applied initial eco‑green color scheme.

### Part 2
- Enhanced design with multiple shades of green.  
- Added hover effects for navigation and staff cards.  
- Improved contact form styling with focus states.  
- Introduced responsive design via media queries for tablet and mobile.  
- Fixed alignment issues and centralized content.  
- Applied POE checklist requirements (forms, enquiry page, footer details).

---
### Part 3

Functionality: JavaScript enhancements (Interactive Elements)

Image lightbox on the About Us page (about.html, Style.css).
Added a lightbox so that the photos on the About Us page open in a larger view when clicked. The approach was adapted from the lightbox example provided by the lecturer, and changed to suit this website.
HTML (about.html): Added the class gallery-img to both About Us photos so that JavaScript can identify them. Added a hidden overlay element, <div id="lightbox"><img id="lightboxImage" src="" alt="Enlarged photo"></div>, just before the closing </main> tag.

HTML (about.html): Added the class gallery-img to both About Us photos so that JavaScript can identify them. Added a hidden overlay element, <div id="lightbox"><img id="lightboxImage" src="" alt="Enlarged photo"></div>, just before the closing </main> tag.

JavaScript (about.html): Added a script before the closing </body> tag. It selects every .gallery-img element and adds a click listener. When a photo is clicked, its src is copied into the overlay image and the overlay is displayed with display: flex. A second click listener on the overlay hides it again when the user clicks anywhere on it.
CSS (Style.css): Added a new "Image Lightbox" section. #lightbox is a fixed, full-screen overlay (position: fixed; inset: 0) that is hidden by default, uses a semi-transparent dark green background taken from the site's colour palette, centres the enlarged photo with flexbox, and sits above all other content with z-index: 1000. The enlarged image is limited to 90% of the screen width and height so it never overflows. .gallery-img was given a pointer cursor and a small hover zoom with a shadow, so users can tell the photos are clickable.

## 📊 Assessment Feedback (Formative 1 Part 1)
- **Module**: Web Development (Introduction) WEDE5020  
- **Score**: 57.5 / 100 (57.5%)  
- **Submission**: `my-website-2.0.zip` (906 KB) + GitHub repo link  
- **Submission Date**: 14 August 2026, 9:57 PM  
- **Feedback Date**: 06 September 2026, 7:31 PM  
- **Notes**:  
  - Review feedback carefully for improvements.  
  - Ensure submissions match required format.  
  - Some rubric criteria not scored — focus on formatting and checklist compliance for Part 2.

---
## 📚 References
- GitHub Repository: [msi-code/my-website-2.0](https://github.com/msi-code/my-website-2.0)
- POE Checklist (Part 2): Independent Institute of Education, 2026 (local PDF resource)
- Feedback for Formative 1 Part 1: Web Development (Introduction) WEDE5020, The Independent Institute of Education, 2026
- CSS and HTML documentation: [MDN Web Docs](https://developer.mozilla.org/)
