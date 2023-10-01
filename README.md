<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pets for Sale</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        h1 {
            margin: 0;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        h2 {
            color: #333;
        }

        .pet {
            border: 1px solid #ccc;
            padding: 10px;
            margin-bottom: 20px;
            border-radius: 5px;
        }

        .pet img {
            max-width: 100%;
            height: auto;
        }

        .price {
            font-weight: bold;
            color: #e74c3c;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pets for Sale</h1>
        <p>Find your perfect furry friend!</p>
    </header>

    <div class="container">
        <h2>Cats</h2>
        <div class="pet">
            <img src="cat1.jpg" alt="Cat 1">
            <p>Beautiful Siamese Cat</p>
            <p class="price">$300</p>
        </div>

        <div class="pet">
            <img src="cat2.jpg" alt="Cat 2">
            <p>Cute Persian Cat</p>
            <p class="price">$250</p>
        </div>

        <h2>Dogs</h2>
        <div class="pet">
            <img src="dog1.jpg" alt="Dog 1">
            <p>Adorable Golden Retriever</p>
            <p class="price">$500</p>
        </div>

        <div class="pet">
            <img src="dog2.jpg" alt="Dog 2">
            <p>Playful Labrador</p>
            <p class="price">$450</p>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 Pets for Sale</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- The previous code for the head section remains the same -->
</head>
<body>
    <header>
        <!-- The previous header content remains the same -->
    </header>

    <div class="container">
        <h2>Cats</h2>
        <div class="pet">
            <img src="cat1.jpg" alt="Cat 1">
            <p>Beautiful Siamese Cat</p>
            <p class="price">$300</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor odio vel ullamcorper.</p>
        </div>

        <div class="pet">
            <img src="cat2.jpg" alt="Cat 2">
            <p>Cute Persian Cat</p>
            <p class="price">$250</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor odio vel ullamcorper.</p>
        </div>

        <h2>Dogs</h2>
        <div class="pet">
            <img src="dog1.jpg" alt="Dog 1">
            <p>Adorable Golden Retriever</p>
            <p class="price">$500</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor odio vel ullamcorper.</p>
        </div>

        <div class="pet">
            <img src="dog2.jpg" alt="Dog 2">
            <p>Playful Labrador</p>
            <p class="price">$450</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed auctor odio vel ullamcorper.</p>
        </div>

        <!-- Contact Information -->
        <h2>Contact Us</h2>
        <p>If you have any questions or would like to inquire about our pets, please feel free to contact us:</p>
        <ul>
            <li>Email: <a href="mailto:contact@petsforsale.com">contact@petsforsale.com</a></li>
            <li>Phone: +1 (123) 456-7890</li>
            <li>Address: 1234 Pet Street, Animalville, USA</li>
        </ul>

        <!-- Contact Form (You can replace this with an actual contact form) -->
        <h2>Contact Form</h2>
        <form action="submit_form.php" method="POST">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>

            <input type="submit" value="Submit">
        </form>
    </div>

    <footer>
        <!-- The previous footer content remains the same -->
    </footer>
</body>
</html>
