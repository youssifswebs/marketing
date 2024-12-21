<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sailing Adventures</title>
    <style>
        
        * {
            margin: 0px;
            padding: 0px;
            box-sizing: border-box;
        }

        
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f0f8ff;
            color: #333;
        }

        header {
            background: #005f73;
            color: #fff;
            padding: 30px;
            text-align: center;
            height: 500px;
        
        
        }

        header h1 {
            margin-bottom: 10px;
        }

        header nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            padding: 10px;
            transition: .5s;
            border-radius: 8px;
        }

        header nav a:hover {
            background-color: #fff;
            color:#005f73;
        }

        
        section {
            padding: 60px 20px;
            margin: 20px 0;
            background-color: #fff;
            box-shadow: 0 1px 4px rgba(0, 0, 0, 0.45);
            transition: 1s;
        }

section:hover{
    cursor:context-menu;
}

        #home {
        background-color: #333;
            color: white;
            text-align: center;
            padding: 100px 20px;
            border-radius: 8px;
        }

        #about, #blog {
            background-color: #f7f7f7;
            text-align: center;
        }

        #about h2, #blog h2 {
            color: #005f73;
            transition: .5s;
            border-radius: 8px;
        
        }

#blog h2:hover{
    cursor:context-menu;
}

        #about h2:hover{
        cursor:context-menu;
        }

        #about p, #blog p {
            max-width: 800px;
            margin: 20px auto;
            font-size: 18px;
        }

        
        html {
            scroll-behavior: smooth;
        }

        
        footer {
            background-color: #005f73;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .footer-contact p {
    font-size: 1.1rem;
    margin: 5px 0;
}

.footer-contact a {
    color: #a1c4fd;
    text-decoration: none;
}

.footer-contact a:hover {
    text-decoration: underline;
}

    </style>
</head>

<body>

    
    <header>
        <h1>Sailing Adventures</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#blog">Blog</a>
        </nav>
        <section id="home">
            <h2>Welcome to Sailing Adventures</h2>
            <p>Explore the world of sailing, discover new destinations, and learn new skills!</p>
        </section>
    </header>

    
    <section id="about">
        <h2>About Us</h2>
        <p>We are passionate about sailing and want to share our experiences with you. Whether you're a seasoned sailor or just starting out, we have something for everyone. Join us on our adventures around the globe as we explore the open seas.</p>
    </section>

    
    <section id="blog">
        <h2>Latest Blog Posts</h2>
        <p>Stay tuned for our latest blog posts about sailing tips, gear recommendations, and travel destinations. Here’s a sneak peek:</p>
        <ul>
            <p><strong>10 Best Sailing Destinations for Beginners</strong> - Learn where to start your sailing adventures.</p>
            <p><strong>Essential Sailing Gear</strong> - The gear you need to get started on the water.</p>
            <p><strong>How to Navigate the Open Sea</strong> - A guide for those new to navigation and charting.</p>
        </ul>
    </section>
    <br>
    <br>
    <br>

    


    <footer>
        <p>&copy; 2024 Sailing Adventures website made by Romtide Company| All rights reserved</p>
    </footer>

    <script>
        
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href').substring(1);
                document.getElementById(targetId).scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>

</body>

</html>
