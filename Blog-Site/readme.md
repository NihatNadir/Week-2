# Blog Website

This is a simple blog website project that showcases recent blog posts and provides a detailed view for individual posts. The project is built using HTML and CSS and includes responsive design features to ensure compatibility with different screen sizes.

## Features
- **Homepage (`index.html`):**
  - Displays a list of recent blog posts with images, titles, and short summaries.
  - Posts are clickable and redirect to the detailed post page.
- **Post Page (`post.html`):**
  - Displays the content of an individual blog post with an image and detailed text.
- **Responsive Design:**
  - The website is optimized for various screen sizes using media queries.
- **Navigation:**
  - A header with navigation links to the homepage and blog posts.
  - A sticky footer at the bottom of the page.

## Technologies Used
- **HTML5:** Structure and content of the website.
- **CSS3:** Styling and layout, including responsive design.
- **CSS Variables:** For consistent color schemes across the website.

## Media Queries
The project uses media queries to ensure a responsive design:
- **For screens smaller than 768px:**
  - Blog posts are displayed in a vertical column instead of side by side.
  - Images are resized to fit the smaller screen width.
  - Margins and padding are adjusted for better usability on small screens.

Example of the media query used:
```css
@media (max-width: 768px) {
    section {
        flex-direction: column;
        align-items: center;
    }
    .post-summary {
        width: 90%;
        margin: 1rem 0;
    }
    img {
        width: 90%;
        height: auto;
    }
}