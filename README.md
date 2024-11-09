# MUHJAR545_FTO2407_GroupA_Muhammad_Jareer_Obaray_CDV05

# HTML Breakdown:
# Document Type & Language:
<!DOCTYPE html> defines the document as HTML5, and lang="en" specifies English as the language.

# Meta Tags:
meta charset="UTF-8" sets the character encoding, ensuring the document can handle a wide variety of characters.
meta name="viewport" makes the site responsive on different screen sizes, essential for mobile compatibility.
meta name="description" and meta name="keywords" enhance SEO by providing search engines with information about the portfolio.

# CSS Link: 
<link rel="stylesheet" href="style.css"> links an external CSS file, style.css, where all styling is defined.

# Navigation Bar (<nav>):
Contains links (<a> tags) to different sections of the page: Home, Projects, and Contact.
Each link uses an href with a # followed by the ID of the target section (#home, #projects, #contact), allowing users to jump to different sections on the same page.

# Introduction Section (<header>):
This section introduces you, the developer, to visitors. The id="home" makes it targetable by the navigation link (href="#home").
<h1> is the main heading for the page, followed by a <p> paragraph that provides a brief bio/introduction.

# Projects Section (<main>):
The id="projects" attribute allows it to be linked to by href="#projects".
Project Card (<section class="project-card">):
Each project is represented in a section.project-card, making each one visually distinct.
<h2> displays the project name.
<img> shows a screenshot of the project, with alt text for accessibility.
<p> describes the project and the technologies used.
A <ul> list with <li> items outlines specific features.
A link to GitHub provides access to the project’s source code.

# Footer (<footer>):
Contains contact information with an email link (<a href="mailto:...">).
Displays a copyright notice.

# CSS Breakdown

# Reset Styles: 
This resets all elements to have no margin or padding and uses box-sizing: border-box, which makes layouts easier to manage.

# Navbar Styling (.nav-bar):
Dark background (#333) with white text.
Flexbox is used to align links (display: flex and justify-content: space-evenly).
position: fixed keeps it at the top even when scrolling.

# Body Styling:
Sets a background image for the page, filling the viewport with background-size: cover.
Uses display: flex and flex-direction: column to stack elements vertically.

# Header Styling:
Centers text and adds padding.
White text ensures readability on the background image.

# Project Card Styling:
Creates a card-like effect with a white background, padding, and rounded corners (border-radius).
Adds a shadow for depth and a hover effect to lift the card slightly.

# Footer Styling:
Centers content, gives it a distinct blue background, and fills the page width.
