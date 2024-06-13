# Portfolio

HTML Structure:
The provided code snippet represents an HTML document.
It begins with the <!DOCTYPE html> declaration, specifying that this is an HTML5 document.
The <html> tag encloses the entire content.
The <head> section contains metadata and links to external resources (stylesheets and fonts).
The <body> section contains the visible content of the webpage.
Header Section:
Inside the <header> element:
A logo with the text “Muhsina” and a nested <span> containing “Nuhu.”
An icon (with the class bx bx-menu) for a menu (likely a navigation menu).
A navigation menu (<nav>) with links to different sections of the page (Home, Education, Services, Testimonials, and Contact).
Home Section:
The <section> with the class home represents the home section.
It includes:
A headline: “Hi, It’s Muhsina.”
An animated text (class text-animation) with an empty <span> (possibly for dynamic content).
Social icons (LinkedIn, GitHub, Instagram, and Twitter).
Buttons for hiring and contacting.
An image (with the src attribute pointing to “img.png”).
Education Section:
The <section> with the class education represents the education section.
It includes:
A heading: “Education.”
A timeline with a single item for the year 2021 (High School).
Placeholder text (“Lorem ipsum dolor sit amet consectetur…”) within the timeline content.

Global Styles:
*: This universal selector applies the following styles to all elements:
margin: 0; padding: 0; box-sizing: border-box; text-decoration: none; border: none; outline: none;: Resets margins, padding, and box-sizing behavior.
scroll-behavior: smooth;: Enables smooth scrolling behavior.
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;: Sets the default font family.
Custom Variables (CSS Variables):
:root: Defines custom properties (variables) for use throughout the stylesheet.
--bg-color, --second-bg-color, --text-color, and --main-color are defined with specific color values.
HTML and Body Styles:
html: Sets the base font size to 60% (for responsive typography).
body: Sets the background color and text color.
Header Styles:
.header: Styles for the header section (likely the navigation bar).
Fixed position at the top of the viewport.
Background with a slight blur effect.
Contains a logo, menu icon, and navigation links.
Logo and Navigation Links:
.logo: Styles for the logo (Muhsina Nuhu).
Font size, color, and cursor behavior.
Hover effect with a scale transformation.
Text shadow with the main color.
.navbar a: Styles for navigation links.
Font size, color, margin, and border-bottom.
Hover effect and active link styling.
Home Section Styles:
.home: Styles for the home section.
Centered alignment and spacing.
.home-content: Styles for the content within the home section.
Flex layout, column direction, and alignment.
Headline styles with dynamic content (Muhsina).
Social icons and buttons for hiring/contacting.
An image (with a placeholder source).
Education Section Styles:
.education: Styles for the education section.
Min-height and padding.
Timeline item styles (year, content, etc.).
