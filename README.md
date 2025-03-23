# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨

SOLUTIONS

1.<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="A basic HTML5 document demonstrating structure and best practices.">
  <meta name="keywords" content="HTML5, structure, example, best practices">
  <meta name="author" content="Your Name (or Website Name)">

  <title>Basic HTML5 Document</title>

  <link rel="stylesheet" href="style.css"> <!-- Link to external stylesheet (recommended) -->
  <link rel="icon" href="favicon.ico" type="image/x-icon"> <!-- Favicon - replace with your icon file -->

  <!-- Optional:  Google Fonts or other CDN links -->
  <!-- <link rel="preconnect" href="https://fonts.googleapis.com">
       <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
       <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"> -->

  <!--  Optional:  For accessibility improvements -->
  <!-- <link rel="stylesheet" href="path/to/accessibility-styles.css"> -->

</head>
<body>

  <header>
    <nav>
      <h1><a href="#">My Website</a></h1>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Services</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="hero">
      <h2>Welcome to My Website!</h2>
      <p>This is a basic HTML5 document demonstrating the structure of a typical webpage.</p>
      <a href="#" class="button">Learn More</a>
    </section>

    <section id="about">
      <h3>About Us</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.  Nullam euismod, lorem vitae tincidunt eleifend, turpis enim vestibulum lectus, eu facilisis quam purus quis quam. Sed finibus urna sed neque blandit, at interdum nisi pretium.</p>
      <img src="placeholder.jpg" alt="Placeholder Image" width="300" height="200">  <!-- Replace with your image and dimensions -->
    </section>

    <section id="services">
      <h3>Our Services</h3>
      <ul>
        <li>Service 1: Description of service 1.</li>
        <li>Service 2: Description of service 2.</li>
        <li>Service 3: Description of service 3.</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Your Website. All rights reserved.</p>
    <p>
        <a href="#">Privacy Policy</a> | <a href="#">Terms of Service</a>
    </p>
  </footer>

  <!-- Optional: Link to external JavaScript file (place at the end of the body for performance) -->
  <script src="script.js"></script>

</body>
</html>
