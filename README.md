# James Taljaard Portfolio

## About This Project

This project is my first portfolio website for the Front-end Web Development course.

The purpose of the site is to introduce myself, document what I am learning, and create a portfolio that I can continue developing as my front-end development skills improve.

The project originally started with semantic HTML in Module 2. In Module 3, I added CSS to give the portfolio a more professional visual style while keeping the page clear, readable, and easy to navigate.

## Portfolio Theme

I chose a professional front-end web development portfolio as my theme.

I wanted the site to reflect the fact that I am still learning and entering the field, while also looking organised and professional enough to grow into a portfolio that I can use to showcase future projects.

For the styling, I aimed for a clean and modern look rather than something overly complicated. I wanted the design to support the content instead of distracting from it.

## Page Structure

The page is organised using semantic HTML elements so that each part of the page has a clear purpose.

### Header

The header introduces me by name and includes a short description of my journey into front-end web development.

### Navigation

The navigation menu links to the different sections of the page:

- About Me
- What I Am Learning
- My Projects
- Contact Me

These links use anchors to move directly to the relevant section of the same page.

### About Me

The About Me section gives a short introduction about who I am, why I am learning front-end web development, and how I am using the portfolio to track my progress.

### What I Am Learning

This section explains some of the areas I am currently focusing on, including HTML5, semantic HTML, accessibility, Git, GitHub, and code validation.

### My Projects

The projects section currently includes this portfolio website as my first official project. I plan to continue developing this section as I complete more work during the course.

### Contact Me

The contact section includes an email link and a basic practice contact form.

The form uses labels and HTML5 input fields to keep it clear and accessible. It is currently for practice and is not connected to a server.

### Footer

The footer contains my name and the current year.

## Visual Styling

For Module 3, I created a separate `styles.css` file and linked it to my HTML document.

I used an external stylesheet because it keeps the HTML focused on structure and content while the CSS controls the presentation of the page.

### Colour Scheme

I chose a simple professional colour palette using dark navy, blue, white, and light grey.

The main colours include:

- Dark navy: `#0f172a`
- Blue: `#1d4ed8`
- Light background: `#f8fafc`
- Light grey: `#e2e8f0`
- White: `#ffffff`

The dark navy is used for the header and footer, while blue is used as the main accent colour for navigation, headings, links, and buttons.

I chose these colours because they give the site a clean and professional appearance while still providing strong contrast between text and backgrounds.

## Typography

I used two Google Fonts for the portfolio:

- Poppins for headings
- Roboto for body text

Poppins gives the headings a stronger visual presence, while Roboto keeps paragraphs and other content easy to read.

I also included fallback fonts in the CSS in case the Google Fonts cannot be loaded.

The body text uses a line height of `1.6` to create more space between lines and improve readability.

## Layout and Spacing

I used the CSS Box Model to control the spacing and structure of the page.

I used properties such as:

- `margin`
- `padding`
- `border`
- `border-radius`
- `width`
- `max-width`
- `display`
- `box-sizing`

The main content is centred on the page and given a maximum width so that paragraphs do not stretch too far across large screens.

Each section has padding and margin to create enough space between content areas. Borders and light background colours help separate the sections without making the design feel too busy.

The learning and project content also uses a blue left border to create a small visual highlight while keeping the layout consistent.

## Navigation and Interaction

The navigation links are styled as simple buttons using `display: inline-block`.

I also used the `:hover` pseudo-class on navigation links, contact links, and the form button so that users receive visual feedback when they move their mouse over an interactive element.

## Multimedia

I included a personal image in the About Me section.

The image is stored inside the `images` folder and is linked to the page using a relative file path.

I added alternative text to make the image more accessible and used CSS borders and spacing to help the image fit into the overall design.

## Accessibility and HTML Structure

I used semantic HTML elements such as `header`, `nav`, `main`, `section`, `article`, and `footer` to give the page a clear structure.

I also used descriptive headings, alternative text for the image, form labels, and clear navigation links.

When choosing colours, I focused on using clear contrast between text and backgrounds so that the content remains easy to read.

## CSS Validation

I validated my `styles.css` file using the W3C CSS Validation Service.

During validation, I initially received a warning because the hover state of my button used the same colour for both the background and border.

I adjusted the CSS and validated the file again.

The final stylesheet passed the W3C CSS Validator with no errors or warnings.

## File Structure

The project currently contains:

- `index.html` – the main portfolio webpage
- `styles.css` – the external stylesheet used to style the portfolio
- `README.md` – information about the project and my design decisions
- `images/james-taljaard.jpg` – the image used on the webpage

## What I Have Learned

This project has helped me understand the difference between using HTML for structure and CSS for presentation.

I learned how to link an external stylesheet, use different CSS selectors, work with colours and fonts, and use the Box Model to control spacing and layout.

One of the biggest differences I noticed was how much margin and padding can affect the appearance of a page. Small changes to spacing made the site feel much more organised and easier to read.

I also learned how useful validation is. The CSS worked in the browser before validation, but the validator still identified something that could be improved. Fixing the warning helped me understand why checking code is an important part of the development process.

I am still learning, but this module has helped me feel more confident about taking a basic HTML page and giving it a clear and consistent visual style.