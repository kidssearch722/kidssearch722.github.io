<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KidSafe Search</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>KidSafe Search</h1>
        <p>Search the web in a safe way!</p>
    </header>

    <div class="search-container">
        <input type="text" id="search-bar" placeholder="Search for kid-friendly stuff...">
        <button onclick="search()">Search</button>
    </div>

    <div class="safe-search">
        <p>We only show kid-safe results!</p>
    </div>

    <footer>
        <p>Powered by KidSafe Search | 2025</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and font styles */
body {
    font-family: 'Poppins', sans-serif;
    background-color: #e4f9ff;
    color: #333;
    text-align: center;
    padding: 20px;
}

/* Header styling */
header {
    background-color: #64b5f6;
    color: white;
    padding: 20px;
    border-radius: 10px;
    margin-bottom: 20px;
}

h1 {
    font-size: 3rem;
}

p {
    font-size: 1.2rem;
}

/* Search bar styling */
.search-container {
    margin: 20px auto;
}

#search-bar {
    padding: 10px;
    font-size: 1.2rem;
    border: 2px solid #64b5f6;
    border-radius: 10px;
    width: 80%;
    max-width: 400px;
    margin-bottom: 10px;
}

button {
    padding: 12px 20px;
    font-size: 1.2rem;
    background-color: #64b5f6;
    color: white;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #42a5f5;
}

/* Safe search info */
.safe-search {
    margin-top: 20px;
    font-size: 1.2rem;
    color: #2d6a4f;
}

/* Footer styling */
footer {
    background-color: #64b5f6;
    color: white;
    padding: 10px;
    margin-top: 30px;
}
// Function to handle the search logic
function search() {
    // Get the value from the search input
    const query = document.getElementById("search-bar").value.toLowerCase().trim();

    // Kid-friendly websites for common safe search terms
    const kidFriendlySites = {
        "dinosaurs": "https://www.nationalgeographic.com/science/article/dinosaurs",
        "space": "https://kids.nationalgeographic.com/space/",
        "animals": "https://www.awesomeanimalfacts.com/",
        "science": "https://www.scientificamerican.com/kids/",
        "games": "https://www.pbskids.org/games/",
        "art": "https://www.kidsart.com/",
        "math": "https://www.coolmathgames.com/",
    };

    // If the search query matches one of the kid-friendly topics
    if (kidFriendlySites[query]) {
        window.location.href = kidFriendlySites[query];
    } else {
        // Otherwise, just show a safe message if the search term is unknown
        alert("Sorry, we couldn't find a safe result for that search. Try searching for something else like 'dinosaurs', 'space', or 'animals'!");
    }
}
