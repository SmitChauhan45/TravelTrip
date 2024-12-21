TravelTrip Website This is a simple travel agency webpage built using HTML, CSS, and Bootstrap. The website presents various travel packages, services offered by the agency, and a contact form to get in touch. It leverages modern web technologies to provide a clean and responsive layout.

How to Run the Webpage Locally To run this webpage on your local machine, follow these steps:

Clone the repository (optional): If you are downloading the files from a repository, you can clone the repository using Git:

bash Copy code git clone https://github.com/SmitChauhan45/TravelTrip.git

File Structure: Ensure the following file structure:

/TravelTrip /assets logo2.png hero.png /main.css /index.html

Open the index.html file: Open the index.html file in any modern web browser (such as Chrome, Firefox, Edge, or Safari).

Ensure Internet Connectivity: The page uses Bootstrap and Font Awesome from external CDN servers, so make sure you're connected to the internet while accessing the page locally.

The webpage should display the travel agency homepage with various sections like the hero, about, services, travel packages, contact form, and footer.

Bootstrap Components Used This website leverages several Bootstrap components to enhance its functionality and layout. Below is a list of components used in the design:

Navbar:

The website header features a responsive navigation bar, which collapses into a hamburger menu on smaller screens. This is implemented using Bootstrap’s navbar, navbar-toggler, and collapse components.

Hero Section:

The hero section contains a prominent call-to-action (CTA) button styled using the .btn, .btn-primary, and .btn-lg classes, along with centered text in a container.

Cards:

The services and travel packages are displayed using Bootstrap's card component. Each service or package is showcased within a card containing an image, a title, and some description. html

Forms:

The contact form is created using Bootstrap’s form classes, including form-control for text inputs and a button styled with btn and btn-primary.

Grid System:

The grid system is used to structure the content and make it responsive. For instance, in the services and packages section, we used col-sm-12, col-md-4, and col-md-3 classes to make the columns adjust based on screen size.

Typography and Icons:

Typography uses custom font families (Poppins in this case) via Google Fonts. The Font Awesome icons are used for visual representation of services like flight booking, hotel booking, and so on:

Responsive Images:

Bootstrap’s card-img-top class is used to make images responsive within the card elements.

Conclusion This website serves as a basic travel agency homepage, presenting information about services, packages, and company details. Bootstrap components provide a responsive and attractive user interface, while Font Awesome icons enhance visual appeal. You can customize the layout by modifying the existing HTML structure and CSS.
