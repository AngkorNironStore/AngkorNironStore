<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Website Title</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to CSS file -->
</head>
<body>
    
    <!-- Website Content -->
    <header>
        <h1>Welcome to Your Top-Up Store</h1>
        <p>Purchase game diamonds instantly!</p>
    </header>

    <main>
        <!-- Product Information -->
        <div class="product">
            <h2>Diamond Top-Up</h2>
            <form action="process_order.php" method="POST">
                <label for="diamonds">Select Diamonds:</label>
                <select id="diamonds" name="diamonds">
                    <option value="50">50 Diamonds - $0.99</option>
                    <option value="100">100 Diamonds - $1.99</option>
                    <option value="500">500 Diamonds - $9.99</option>
                </select>

                <label for="playerID">Player ID:</label>
                <input type="text" id="playerID" name="playerID" required>

                <label for="serverID">Server ID:</label>
                <input type="text" id="serverID" name="serverID" required>

                <button type="submit">Buy Now</button>
            </form>
        </div>
    </main>

    <!-- Message Area -->
    <footer>
        <p>&copy; 2024 Your Store Name</p>
    </footer>

    <!-- Link to JavaScript file -->
    <script src="script.js"></script>
</body>
</html>

<!--
**AngkorNironStore/AngkorNironStore** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
