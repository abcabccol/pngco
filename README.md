<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PNGCO | Aesthetic Stickers & PNGs</title>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --accent-soft: #ffdae0;
            --accent-vibrant: #ffb7c5;
            --dark-text: #4a3f3f;
            --light-bg: #fffafb;
            --card-white: #ffffff;
        }

        body {
            background-color: var(--light-bg);
            font-family: 'Quicksand', sans-serif;
            color: var(--dark-text);
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }

        /* Navigation Bar */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 25px 8%;
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 1.8rem;
            font-weight: 700;
            color: var(--accent-vibrant);
            letter-spacing: -1px;
            cursor: pointer;
        }

        .logo span {
            color: var(--dark-text);
            font-weight: 300;
        }

        .nav-links a {
            text-decoration: none;
            color: var(--dark-text);
            margin-left: 25px;
            font-weight: 500;
            transition: 0.3s;
        }

        .nav-links a:hover {
            color: var(--accent-vibrant);
        }

        /* Hero Header */
        header {
            text-align: center;
            padding: 80px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin: 0;
            background: linear-gradient(45deg, #ffb7c5, #ff9aa2);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        header p {
            font-size: 1.1rem;
            opacity: 0.8;
            margin-top: 10px;
        }

        /* Search Section */
        .search-wrapper {
            margin: 30px auto;
            max-width: 600px;
            position: relative;
        }

        .search-input {
            width: 100%;
            padding: 18px 30px;
            border-radius: 50px;
            border: 2px solid var(--accent-soft);
            outline: none;
            font-size: 1rem;
            font-family: inherit;
            transition: all 0.3s ease;
            box-shadow: 0 10px 20px rgba(255, 183, 197, 0.1);
        }

        .search-input:focus {
            border-color: var(--accent-vibrant);
            box-shadow: 0 15px 30px rgba(255, 183, 197, 0.2);
        }

        /* Content Section */
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        .section-title {
            margin-bottom: 30px;
            font-size: 1.4rem;
            border-left: 4px solid var(--accent-vibrant);
            padding-left: 15px;
        }

        .sticker-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 30px;
        }

        /* Sticker Card Design */
        .sticker-card {
            background: var(--card-white);
            border-radius: 30px;
            padding: 25px;
            text-align: center;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            border: 1px solid rgba(255, 218, 224, 0.3);
        }

        .sticker-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 20px 40px rgba(255, 183, 197, 0.2);
        }

        .sticker-card img {
            width: 120px;
            height: 120px;
            object-fit: contain;
            margin-bottom: 20px;
            filter: drop-shadow(0 5px 15px rgba(0,0,0,0.05));
        }

        .sticker-card h3 {
            margin: 0 0 15px 0;
            font-size: 1rem;
        }

        .btn-download {
            display: inline-block;
            background: var(--accent-soft);
            color: var(--dark-text);
            text-decoration: none;
            padding: 10px 25px;
            border-radius: 20px;
            font-size: 0.85rem;
            font-weight: 700;
            transition: 0.3s;
        }

        .btn-download:hover {
            background: var(--accent-vibrant);
            color: white;
            box-shadow: 0 5px 15px rgba(255, 154, 162, 0.4);
        }

        footer {
            text-align: center;
            padding: 60px 20px;
            font-size: 0.9rem;
            opacity: 0.7;
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">PNG<span>CO</span></div>
        <div class="nav-links">
            <a href="#">Explore</a>
            <a href="#">Trending</a>
            <a href="#">Premium</a>
        </div>
    </nav>

    <header>
        <h1>Aesthetic Sticker Hub</h1>
        <p>Discover & download thousands of soft-themed PNG assets.</p>
        
        <div class="search-wrapper">
            <input type="text" class="search-input" placeholder="Search for stickers, emojis, gifs...">
        </div>
    </header>

    <div class="container">
        <h2 class="section-title">Trending Now ✨</h2>
        
        <div class="sticker-grid">
            <div class="sticker-card">
                <img src="https://cdn-icons-png.flaticon.com/512/4710/4710816.png" alt="Bunny">
                <h3>Cloud Bunny</h3>
                <a href="#" class="btn-download">Get PNG</a>
            </div>

            <div class="sticker-card">
                <img src="https://cdn-icons-png.flaticon.com/512/2271/2271062.png" alt="Love Heart">
                <h3>Peach Heart</h3>
                <a href="#" class="btn-download">Get PNG</a>
            </div>

            <div class="sticker-card">
                <img src="https://cdn-icons-png.flaticon.com/512/4359/4359675.png" alt="Sanrio Style">
                <h3>Milky Paws</h3>
                <a href="#" class="btn-download">Get PNG</a>
            </div>

            <div class="sticker-card">
                <img src="https://cdn-icons-png.flaticon.com/512/3255/3255463.png" alt="Bear">
                <h3>Brownie Bear</h3>
                <a href="#" class="btn-download">Get PNG</a>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 PNGCO Studio. All rights reserved. Made with ✨</p>
    </footer>

</body>
</html>
