# PART-2-WEDE5020-ST10531213-

CRUST & CRUMB ARTISAN BAKERY
WEBSITE REDESIGN README
WEDO5020 - Siyabonga Mhlongo
============================================================

PURPOSE
-------
This README explains how to replace the old Crust & Crumb website with
its redesigned version. The new website uses HTML and CSS only, has a
responsive layout, and is organised for use in Visual Studio Code.

The redesign changes the website from a basic bakery page into a clean,
professional artisan bakery website with:

- A redesigned home page with a strong hero section.
- A clear navigation menu across all pages.
- A separate About and Products page.
- A separate Enquiries and Contact page.
- A product catalogue grouped into categories.
- A responsive mobile navigation menu made with CSS only.
- Responsive layouts for desktop, tablet and mobile devices.
- A warm rustic bakery colour palette.
- Playfair Display headings and Lato body text.
- Accessibility features such as skip links, labels and semantic HTML.
- A contact form and Google Map section.
- Consistent footer content on every page.


NEW PROJECT STRUCTURE
---------------------
Create or replace your VS Code project so it has this structure:

PART 2 CRUST AND CRUMB/
|
|-- index.html
|-- about.html
|-- contact.html
|-- style.css
|
|-- styles/
|   |-- index.css
|   |-- about.css
|   |-- contact.css
|
|-- images/
|   |-- Add your bakery and product photos here
|
|-- README.txt

IMPORTANT:
The HTML files must remain in the main project folder.
The three page-specific CSS files must remain inside the styles folder.
Do not rename the files unless you also update the links inside the HTML.


WHAT EACH FILE DOES
-------------------
index.html
The home page. It contains:
- Bakery introduction and hero section.
- Main calls to action.
- Bakery values: Naturally Leavened, Locally Sourced and Made to Order.
- Short bakery story section.
- Catering call to action.

about.html
The About and Products page. It contains:
- Bakery overview.
- Sourdough products.
- Pastries.
- Custom cakes.
- Catering products and menus.
- Product descriptions and visual placeholders.

contact.html
The Enquiries and Contact page. It contains:
- Customer enquiry form.
- Full name, email, phone, enquiry type, date and message fields.
- Bakery hours, phone, email and address.
- Google Map embed.

style.css
The shared stylesheet used by all pages. It contains:
- Reset styles.
- Colours and typography variables.
- Header and navigation styles.
- Buttons.
- Page headers.
- Section backgrounds.
- Footer.
- Shared responsive styles.

styles/index.css
Styles only used by the home page, including the hero, values grid and story section.

styles/about.css
Styles only used by the About and Products page, including product cards and product categories.

styles/contact.css
Styles only used by the Contact page, including the form, bakery details and map.


HOW TO UPDATE THE WEBSITE IN VS CODE
------------------------------------
1. Open Visual Studio Code.
2. Select File > Open Folder.
3. Open the folder named PART 2 CRUST AND CRUMB.
4. Replace the old index.html with the redesigned index.html.
5. Replace the old about.html with the redesigned about.html.
6. Replace the old contact.html with the redesigned contact.html.
7. Replace the old style.css with the redesigned style.css.
8. Create a folder named styles if it does not already exist.
9. Add index.css, about.css and contact.css inside the styles folder.
10. Save all files.

Every HTML page should contain these stylesheet links:

<link rel="stylesheet" href="style.css">
<link rel="stylesheet" href="styles/index.css">

The second CSS link changes according to the page:

index.html:
<link rel="stylesheet" href="styles/index.css">

about.html:
<link rel="stylesheet" href="styles/about.css">

contact.html:
<link rel="stylesheet" href="styles/contact.css">


HOW TO RUN THE WEBSITE
----------------------
Recommended method:

1. Install the Live Server extension in VS Code.
2. Open index.html.
3. Right-click inside index.html.
4. Select Open with Live Server.
5. The website will open in your browser.
6. Use the navigation links to test Home, About and Enquiries.

If you see "localhost refused to connect", Live Server is not running.
Do not manually use localhost:8080 unless your own server is configured
for port 8080. Live Server normally uses a URL similar to:

http://127.0.0.1:5500/index.html


ADDING REAL IMAGES
------------------
The product illustrations are placeholders. To add real bakery photos:

1. Create an images folder in the main project folder.
2. Add your images inside it.
3. Replace a placeholder SVG with an image, for example:

<img src="images/classic-country-loaf.jpg"
     alt="Freshly baked classic country sourdough loaf">

Use a clear, accurate alt description for every image. This improves
accessibility and supports the W3C accessibility requirements in the
proposal.

Recommended image names:
- bakery-interior.jpg
- classic-country-loaf.jpg
- rye-seed-boule.jpg
- sourdough-baguette.jpg
- butter-croissant.jpg
- seasonal-fruit-danish.jpg
- celebration-cake.jpg
- wedding-cake.jpg
- catering-platter.jpg


IMPORTANT INFORMATION TO REPLACE
--------------------------------
Before submitting or publishing the website, replace the example details
with the real bakery information:

- Phone number: 021 555 1234
- Email address: hello@crustandcrumb.co.za
- Address: 45 Main Road, Cape Town, 8001
- Google Map location.

The current details are example content for the student project and must
be confirmed before launch.


DESIGN CHANGES FROM THE OLD WEBSITE
------------------------------------
The new version includes:

- A stronger visual hierarchy using large Playfair Display headings.
- A consistent warm brown, cream and gold bakery colour scheme.
- Better spacing and alignment throughout all pages.
- A professional hero section on the home page.
- Clearer calls to action for products, orders and catering enquiries.
- Product cards with category labels and descriptions.
- A two-column enquiry layout on desktop.
- A single-column mobile layout for easier reading.
- A CSS-only mobile hamburger menu.
- Better keyboard focus states and skip navigation.
- Semantic elements including header, nav, main, section, article and footer.
- Responsive breakpoints for tablets and mobile devices.
- No JavaScript dependency.


TESTING CHECKLIST
-----------------
Before submission, test the following:

[ ] index.html opens correctly.
[ ] about.html opens correctly.
[ ] contact.html opens correctly.
[ ] All navigation links work.
[ ] The Home link returns to index.html.
[ ] CSS loads on every page.
[ ] The mobile menu opens when the screen is narrow.
[ ] The website works at desktop width.
[ ] The website works at tablet width.
[ ] The website works at mobile width.
[ ] Form labels match their inputs.
[ ] Required form fields work.
[ ] The Google Map loads.
[ ] There are no broken image links.
[ ] The browser console has no errors.
[ ] Text is readable and has good contrast.
[ ] All real images have alt text.


ACADEMIC NOTE
-------------
This website is built according to the Crust & Crumb proposal:

- HTML is used for structure and content.
- CSS is used for styling, layout and responsive presentation.
- The design is warm, rustic and minimalist.
- The product catalogue uses a grid layout.
- The enquiry page supports custom cake and catering leads.
- The website is designed for mobile and desktop users.
- Accessibility principles from W3C are considered.

This README documents the redesign and the implementation process for
submission with the WEDO5020 student project.
