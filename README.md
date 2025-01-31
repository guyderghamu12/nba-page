<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NBA Themed Page</title>
    <style>
        /* General body styling */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #1e1e2f; /* Dark background */
            color: #ffffff; /* White text */
        }

        /* Header styling */
        header {
            background-color: #0a74da; /* NBA blue */
            padding: 20px;
            text-align: center;
            color: #ffffff;
            font-size: 2em;
        }

        /* Navigation bar */
        nav {
            display: flex;
            justify-content: center;
            background-color: #292940; /* Dark navigation background */
            padding: 10px;
        }

        nav a {
            color: #fcb813; /* NBA gold */
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #ff0000; /* NBA red */
            color: #ffffff;
            border-radius: 5px;
        }

        /* Main content styling */
        main {
            padding: 20px;
        }

        .article {
            background-color: #292940; /* Article card background */
            padding: 20px;
            margin: 20px 0;
            border-radius: 8px;
        }

        .article h2 {
            color: #0a74da; /* Title in NBA blue */
        }

        .article p {
            line-height: 1.6;
        }

        /* Footer styling */
        footer {
            background-color: #292940;
            color: #e0e0e0;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }

        /* Button styling */
        .btn {
            display: inline-block;
            background-color: #0a74da; /* NBA blue */
            color: #ffffff;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 10px;
            cursor: pointer;
            border: none;
        }

        .btn:hover {
            background-color: #ff0000; /* NBA red */
            color: #ffffff;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        Welcome to the NBA Fan Page
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#home">Home</a>
        <a href="#news">News</a>
        <a href="#teams">Teams</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content -->
    <main>
        <div class="article">
            <h2>NBA News</h2>
            <p>The latest updates on your favorite teams and players.</p>
            <button class="btn" onclick="showNews()">Read More</button>
        </div>

        <div class="article">
            <h2>Top Players</h2>
            <p>Discover the stars making history in the league this season.</p>
            <button class="btn" onclick="learnMore()">Learn More</button>
        </div>
    </main>

    <!-- Footer -->
    <footer>
        &copy; 2025 NBA Fan Page. All Rights Reserved.
        <button class="btn" onclick="contactUs()">Contact Us</button>
    </footer>

    <script>
        // Functionality for the "Read More" button
        function showNews() {
            alert("Redirecting to NBA news...");
            window.location.href = "https://www.nba.com/news"; // Example link
        }

        // Functionality for the "Learn More" button
        function learnMore() {
            alert("Loading information about top players...");
            window.location.href = "https://www.nba.com/players"; // Example link
        }

        // Functionality for the "Contact Us" button
        function contactUs() {
            alert("You can contact us at support@nba.com");
        }
    </script>

</body>
</html>
