# Coffee-Shop-website-using-HTML-CSS-JavaScript
This project is a website for coffee house business. It uses HTML for the structure, CSS to style the pages, and JavaScript for making the site interactive.
The site includes several sections like a landing page with a banner and an image slider, areas to show services, a menu, and animated counters that display important business stats. If you are having a coffee shop you can take the advantage of this website and customize this according to your requirement to showcase coffee shop services and items

The design is responsive, which means it works well on any device such as phones, tablets, or desktops. 

Structure :
HTML :
Head Section :
Links to external resources, including stylesheets from Google Fonts, Font Awesome for icons, and Swiper.js for the image slider.

Body Section :
Contains the core components of the webpage:

Navbar: A fixed navigation bar that provides links to different sections of the site.
Landing Section: Features a welcome message and a call-to-action button, alongside a Swiper image slider.
About Section: Highlights key business features like ease of ordering, fast delivery, and quality coffee.
Menu Section: Displays a brief description of the coffee house’s menu with associated images.
Business Data Section: Displays business statistics, like the number of branches and awards.
CSS :
Global Styles :
Font settings, margins, padding, and box-sizing are reset for consistency across browsers. html is set to font-size: 62.5% for easier scaling and responsiveness.

Container and Navbar :
The container spans the full width and height, providing a base layout. The navbar is styled with a fixed position, making it always visible, and it transitions smoothly into a sticky mode when scrolling, shrinking its height.

Landing Section :
The banner text is centered with the use of absolute positioning and is styled to stand out with fonts from Google. Call-to-action buttons have hover effects that change colors and borders for interactivity.

Swiper Slider :
Custom pagination styles are applied to the Swiper bullets, and images are set to cover the entire viewport for an immersive experience

Responsive Design :
The website is built to be responsive, ensuring that the layout and images adjust properly on different screen sizes. The use of percentages and flexible units like rem helps achieve this.

JavaScript Logic :
Swiper Functionality :
The Swiper.js library is used to create an image slider that transitions between images with a fade effect.

Autoplay :
The images change automatically every 4 seconds (delay: 4000) without disabling the autoplay when the user interacts with the slider (disableOnInteraction: false).

Looping :
The slider loops indefinitely (loop: true), ensuring continuous movement without breaks.

Pagination
Bullet-style pagination allows users to navigate between slides manually, with the pagination bullets being clickable (clickable: true).

Purpose of Functions
Swiper Slider Initialization :
Initializes the image slider and controls its behavior, ensuring smooth transitions between images, autoplay, and user interaction via pagination.

Scroll Event Listener :
This function checks the user’s scroll position in real-time and applies two important changes:

Sticky Navbar: Adds/removes the sticky class when the user scrolls down to keep the navigation visible while compact.
Trigger Counters: When the user scrolls past the menu section, the counters for business data start incrementing.
startCount Function :
This function controls the increment of each business data counter. It starts counting from 0 to the target value and stops when the target is reached.The counting process is paced by setting the interval dynamically based on the target value, ensuring the numbers increment at a consistent speed.
