Osariemen Arughu - Portfolio Website
About My Portfolio
This is my personal portfolio website - Web and Scripting Programming. I built the site using HTML5 and CSS3 and it has 4 pages home, about me, projects and contact me. 

Code Sources
The main HTML and CSS techniques used in this project came from the INFR3120 lecture material. I used the lecture examples as a guide and changed the content, colors, sizes, class names, and layout to fit my own portfolio.
Week 1 - Basics of HTML and CSS
I used this lecture for the basic HTML5 page structure, headings, paragraphs, links, div elements, external CSS, classes, IDs, floats, margins, padding, and the wrapper layout.


Week 2 - Structuring Pages with HTML5 Semantic Markup
I used this lecture for semantic HTML elements such as header, nav, article, section, aside, footer, and address.


Week 2 - Embedding Native Video / Forms
I used this lecture for the HTML5 video element, video controls, poster image, form fields, labels, required fields, email validation, textarea, submit button, and reset button.     

Week 3 - Responsive Design
I used this lecture for fluid design, percentage widths, media queries, responsive images, and the separate desktop, tablet, and phone stylesheets.

Week 4 - Interactive Transforms with CSS
I used this lecture for hover effects, transitions, and button interaction.     

Responsive Design and Viewports
I used three separate CSS files so the layout changes depending on the screen size.
Desktop / Laptop
File: style.css
Viewport: 960px and above
I used this size for laptops and desktop computers because they have more horizontal space. This lets sections such as the contact information, contact form, and project cards use wider layouts.
Tablet
File: tablet.css
Viewport: 481px to 960px
I used this range for tablets because they have less horizontal space than a laptop, but still have enough room for some two-column content. Some sections become wider or stack vertically to make them easier to read.
Phone
File: phone.css
Viewport: 480px and below
I used this size for phones. The navigation links become larger blocks, project cards stack into one column, and images, videos, and form fields use percentage widths so they fit smaller screens.
I also used percentage widths in the CSS to create a fluid layout so the content can adjust as the browser size changes.
Gradients
I used both a normal linear gradient and an angled linear gradient in the website.
Angled Linear Gradient
I used a 45deg angled gradient in:
- #hero on the Home page
- .page-heading on the About Me, Projects, and Contact pages
The main angled gradient changes from #161d24 to #1b2b35.
Linear Gradient
I used a left-to-right linear gradient in:
- .simple-section
- .content-section
- .contact-section
- .project-section
I used these gradients to separate the different sections while keeping the same dark theme across the website.
Color Scheme
I chose a dark blue and charcoal color scheme because I wanted the portfolio to have a simple technology/networking look while still being easy to read.
The main colors I used are:
- #11161c - main background
- #161d24 - main content background
- #1b232b - cards and smaller sections
- #2785b8 - main blue accent and buttons
- #6db6dd - lighter blue headings and links
- #d9e0e5 - main text
- #0b1015 - header and footer   

Website Structure
I used semantic HTML5 tags to keep the pages organized:
- header contains my name and the top section of the page.
- nav contains the navigation links.
- article contains the main page content.
- section separates the main content areas.
- aside is used for the profile information on the About Me page.
- footer contains my email and copyright information.
Contact Form
The Contact Me page includes:
- Name
- Email
- Cell Number
- Comments
- Submit button
- Reset button