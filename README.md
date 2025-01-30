# Recycle-Clothing-and-Materialsproject
# Recycle your old clothing and help reduce waste. Donate your used clothes or send them to recycling centers where they can be repurposed into new products.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recycle Clothing and Materials</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #2d2d2d;
            color: white;
            padding: 20px;
            text-align: center;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
        }
        .card {
            display: flex;
            flex-direction: column;
            background-color: #e9e9e9;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .card img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .card h3 {
            text-align: center;
            color: #2d2d2d;
        }
        .card p {
            font-size: 1.1em;
            color: #555;
        }
        .card a {
            text-align: center;
            color: white;
            background-color: #4CAF50;
            padding: 10px;
            text-decoration: none;
            border-radius: 5px;
        }
        .card a:hover {
            background-color: #45a049;
        }
        footer {
            background-color: #2d2d2d;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Recycle Clothing and Materials</h1>
        <p>Let's protect the planet by recycling clothing, plastics, papers, and more!</p>
    </header>

    <section id="clothing">
        <div class="card">
            <h3>Clothing Recycling</h3>
            <img src="clothing-image.jpg" alt="Clothing Recycling">
            <p>Recycle your old clothing and help reduce waste. Donate your used clothes or send them to recycling centers where they can be repurposed into new products.</p>
            <a href="#">Learn More</a>
        </div>
    </section>

    <section id="plastic">
        <div class="card">
            <h3>Plastic Recycling</h3>
            <img src="plastic-image.jpg" alt="Plastic Recycling">
            <p>Plastic waste is a major environmental concern. Recycle your plastic bottles, containers, and other items to reduce pollution and conserve resources.</p>
            <a href="#">Learn More</a>
        </div>
    </section>

    <section id="paper">
        <div class="card">
            <h3>Paper Recycling</h3>
            <img src="paper-image.jpg" alt="Paper Recycling">
            <p>Recycling paper helps save trees, reduce landfill waste, and save energy. Collect paper such as newspapers, magazines, and old documents for recycling.</p>
            <a href="#">Learn More</a>
        </div>
    </section>

    <section id="contact">
        <div class="card">
            <h3>Contact Us</h3>
            <form action="submit-form.php" method="post">
                <label for="name">Name:</label><br>
                <input type="text" id="name" name="name" required><br><br>

                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="message">Message:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>

                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Recycle Clothing and Materials. All rights reserved.</p>
    </footer>
</body>
</html>
