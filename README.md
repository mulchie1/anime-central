<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Central</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Anime Central</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#directory">Directory</a></li>
                    <li><a href="#forum">Forum</a></li>
                    <li><a href="#blog">Blog</a></li>
                    <li><a href="#shop">Shop</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Welcome to Anime Central</h2>
            <p>Your go-to site for all things anime!</p>
            <input type="text" placeholder="Search for anime...">
        </div>
    </section>

    <section id="featured">
        <div class="container">
            <h2>Featured Anime</h2>
            <div class="anime-card">
                <img src="https://via.placeholder.com/150" alt="Anime 1">
                <div class="anime-info">
                    <h3>Anime Title 1</h3>
                    <p>Brief description of Anime 1.</p>
                </div>
            </div>
            <div class="anime-card">
                <img src="https://via.placeholder.com/150" alt="Anime 2">
                <div class="anime-info">
                    <h3>Anime Title 2</h3>
                    <p>Brief description of Anime 2.</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Anime Central. All rights reserved.</p>
            <p>Follow us on:
                <a href="#">Facebook</a> | 
                <a href="#">Twitter</a> | 
                <a href="#">Instagram</a>
            </p>
        </div>
    </footer>
</body>
</html>

src/page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Central</title>
    <link href="/path/to/your/styles.css" rel="stylesheet">
</head>
<body>
    <section class="relative bg-cover bg-center h-screen" style="background-image: url('https://via.placeholder.com/1200x800');">
        <div class="absolute inset-0 bg-overlay"></div>
        <div class="relative z-10 flex flex-col items-center justify-center h-full text-center text-white px-4">
            <h1 class="text-5xl md:text-6xl font-bold mb-4 text-primary">Welcome to Anime Central</h1>
            <p class="text-lg md:text-2xl mb-8">Your ultimate source for all things anime!</p>
            <input type="text" placeholder="Search for anime..." class="px-4 py-2 rounded-md text-black w-full max-w-md">
        </div>
    </section>
</body>
</html>
