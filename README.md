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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Page with List, Image, Table, and Form</title>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Ordered List (Roman Numerals)</h2>
        <ol type="I">
            <li>Item One</li>
            <li>Item Two</li>
            <li>Item Three</li>
            <li>Item Four</li>
            <li>Item Five</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>External Image</h2>
        <img src="https://www.pexels.com/photo/example-image.jpg" alt="Beautiful Scenery from Pexels" width="500">
    </section>

    <!-- Contact Table -->
    <section>
        <h2>Contact List</h2>
        <table border="1">
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
            <tr>
                <td>John Doe</td>
                <td>123 Main St</td>
                <td>+1234567890</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak St</td>
                <td>+0987654321</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Mark Brown</td>
                <td>789 Pine St</td>
                <td>+1122334455</td>
                <td>mark@example.com</td>
            </tr>
            <tr>
                <td>Lisa White</td>
                <td>159 Maple St</td>
                <td>+5566778899</td>
                <td>lisa@example.com</td>
            </tr>
            <tr>
                <td>Tom Black</td>
                <td>753 Elm St</td>
                <td>+6677889900</td>
                <td>tom@example.com</td>
            </tr>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required><br><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br><br>

            <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select Country</option>
                <option value="usa">USA</option>
                <option value="uk">UK</option>
                <option value="canada">Canada</option>
                <option value="australia">Australia</option>
            </select><br><br>

            <label>Interests:</label>
            <input type="checkbox" id="coding" name="interests" value="coding">
            <label for="coding">Coding</label>
            <input type="checkbox" id="music" name="interests" value="music">
            <label for="music">Music</label>
            <input type="checkbox" id="sports" name="interests" value="sports">
            <label for="sports">Sports</label><br><br>

            <input type="

