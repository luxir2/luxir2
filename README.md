<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hamaad's Personal Home Page</title>
    <!-- External CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.3.0/css/bootstrap.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <!-- Custom CSS -->
    <style>
        /* Custom styles */
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #f8f9fa;
            color: #343a40;
            margin: 0;
            padding: 0;
        }
        .container {
            padding: 30px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2, h3 {
            text-align: center;
            margin-bottom: 20px;
        }
        nav {
            margin-bottom: 30px;
        }
        .nav-link {
            color: #343a40;
        }
        .nav-link:hover {
            color: #007bff;
        }
        section {
            margin-bottom: 40px;
            margin-top: 20px; /* Add margin to the top of each section */
            position: relative; /* Needed for scroll animations */
        }
        img {
            display: block;
            margin: 0 auto;
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            margin-top: 30px;
            padding: 20px 0; /* Add padding to the footer */
            border-top: 1px solid #dee2e6;
        }
        .contact-info li {
            margin-bottom: 10px; /* Add spacing between contact details */
        }
        .gallery img {
            border-radius: 10px; /* Add border-radius to gallery images */
        }
        /* Animations */
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.5s ease, transform 0.5s ease;
        }
        .fade-in.active {
            opacity: 1;
            transform: translateY(0);
        }
        /* Hover Effects */
        .hover-scale {
            transition: transform 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.05);
        }
        /* Anime Section */
        #anime {
            text-align: center;
        }
        #anime p {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <header>
            <h1>Welcome to Hamaad's Personal Home Page</h1>
        </header>

        <!-- Navigation -->
        <nav>
            <ul class="nav justify-content-center">
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#hobbies">Hobbies</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#gallery">Gallery</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
        </nav>

        <!-- Sections -->
        <section id="about" class="fade-in">
            <h2>About Me</h2>
            <p>Hello! I'm Hamaad, a tech enthusiast and adventurer hailing from the breathtaking landscapes of Kashmir. As a Computer Science student at the University of Kashmir, I've mastered various coding languages, including JavaScript, Python, Java, C++, and Ruby. My passion for coding extends beyond mere mastery; it's a journey of continuous learning and innovation.</p>
            <p>In addition to my digital pursuits, I'm deeply engaged in the world of martial arts. From mastering Pencak Silat to delving into Mixed Martial Arts, Jujitsu, and Karate, I find solace and discipline in the art of combat. Beyond the dojo, I indulge in the electrifying realm of electronics, where I tinker with circuits, dismantle gadgets, and unleash my creativity to craft new inventions.</p>
            <p>But what truly sets me apart is my mindset. I thrive in moments of solitude, where I can immerse myself in introspection and self-discovery. I believe in the power of self-improvement and embrace challenges as opportunities for transformation. Whether it's exploring new coding techniques, perfecting martial arts forms, or experimenting with electronics, I constantly seek to push the boundaries of my capabilities.</p>
            <p>Join me on a voyage where technology meets tradition, where the mind transcends boundaries, and where every challenge is an opportunity for growth and discovery.</p>
        </section>

        <section id="hobbies" class="fade-in">
            <h2>My Hobbies</h2>
            <div class="row">
                <!-- Coding -->
                <div class="col-md-4 hover-scale">
                    <h3>Coding</h3>
                    <p>My passion for coding knows no bounds. I've spent countless hours mastering coding languages like JavaScript, Python, Java, C++, and Ruby, among others. But it's not just about mastering languages; it's about exploring the endless possibilities they offer. From crafting elegant algorithms to building robust applications, coding is not just a skill; it's my creative outlet and a gateway to innovation.</p>
                </div>
                <!-- Gaming -->
                <div class="col-md-4 hover-scale">
                    <h3>Gaming</h3>
                    <p>Gaming isn't just a pastime for me; it's a journey of exploration, strategy, and social connection. Whether I'm leading armies to victory in strategy games or immersing myself in the rich narratives of RPGs, gaming offers a unique blend of challenge and escapism. Beyond the virtual realm, I'm also an avid football player and badminton enthusiast, finding joy in both the thrill of competition and the camaraderie of team sports.</p>
                </div>
                <!-- Hiking -->
                <div class="col-md-4 hover-scale">
                    <h3>Hiking</h3>
                    <p>Hiking is my escape into nature's embrace. There's something magical about traversing rugged mountain trails and wandering through serene forests. Each step brings me closer to the beauty of the wilderness, allowing me to disconnect from the chaos of daily life and reconnect with the earth. Whether I'm summiting peaks or meandering along riverbanks, hiking is not just an activity; it's a journey of self-discovery, resilience, and awe-inspiring beauty.</p>
                </div>
                <!-- Martial Arts -->
                <div class="col-md-4 hover-scale">
                    <h3>Martial Arts</h3>
                    <p>Martial arts is more than just a hobby for me; it's a way of life. From the discipline of Pencak Silat to the fluidity of Mixed Martial Arts and the precision of Jujitsu and Karate, each discipline has shaped not only my body but also my mind. Through rigorous training and unwavering dedication, I've learned the value of self-discipline, respect, and personal growth. Martial arts isn't just about mastering techniques; it's about cultivating inner strength and forging a path towards excellence.</p>
                </div>
                <!-- Electronics -->
                <div class="col-md-4 hover-scale">
                    <h3>Electronics</h3>
                    <p>My fascination with electronics fuels my curiosity and ignites my creativity. Whether I'm tinkering with circuits, dismantling gadgets, or engineering new devices, every project is an opportunity to push the boundaries of innovation. From building robots to designing interactive installations, electronics isn't just a hobby; it's a journey of exploration, experimentation, and technological advancement.</p>
                </div>
                <!-- Photography -->
                <div class="col-md-4 hover-scale">
                    <h3>Photography</h3>
                    <p>Photography allows me to capture moments frozen in time, preserving memories and emotions for eternity. Behind the lens, I find beauty in the mundane and inspiration in the extraordinary. Whether I'm exploring urban landscapes or capturing the raw essence of nature, photography is not just a hobby; it's a form of self-expression and a window into the world.</p>
                </div>
                <!-- Cooking -->
                <div class="col-md-4 hover-scale">
                    <h3>Cooking</h3>
                    <p>Cooking is my creative outlet in the culinary world. From experimenting with new recipes to mastering traditional dishes, I find joy in the art of gastronomy. Whether it's the sizzle of a pan or the aroma of freshly baked goods, cooking allows me to express myself and share moments of delight with others.</p>
                </div>
                <!-- Traveling -->
                <div class="col-md-4 hover-scale">
                    <h3>Traveling</h3>
                    <p>Traveling is not just about visiting new places; it's about immersing myself in different cultures, cuisines, and perspectives. Whether I'm exploring ancient ruins, hiking through lush forests, or strolling along bustling streets, each journey leaves an indelible mark on my soul. Traveling broadens my horizons, fosters empathy, and reminds me of the beauty and diversity of our world.</p>
                </div>
                <!-- Reading -->
                <div class="col-md-4 hover-scale">
                    <h3>Reading</h3>
                    <p>Reading is my gateway to new worlds and perspectives. Whether it's diving into a gripping novel, exploring the depths of non-fiction, or devouring articles on the latest technologies, reading fuels my imagination and broadens my understanding of the world. With each page turned, I embark on a journey of discovery and enlightenment.</p>
                </div>
            </div>

            <!-- Anime Section -->
            <div id="anime" class="fade-in">
                <h2>Watching Anime</h2>
                <p>Watching anime is not just entertainment for me; it's a breathtaking experience. Anime has been a significant part of my life, influencing my creativity, imagination, and worldview. From classic series like Naruto and Dragon Ball Z to modern masterpieces like Attack on Titan and Demon Slayer, each anime offers a unique blend of storytelling, artistry, and emotion.</p>
                <p>Immersing myself in the vibrant worlds of anime allows me to explore diverse themes, from friendship and courage to love and loss. Whether I'm following the epic battles of shonen anime or unraveling the intricate plots of psychological thrillers, each episode leaves me spellbound, eagerly anticipating the next chapter of the journey.</p>
                <p>Beyond entertainment, anime has inspired me to pursue my passions with determination and creativity. The rich characters, compelling narratives, and breathtaking visuals fuel my own creative endeavors, whether it's writing stories, drawing artwork, or exploring new forms of expression.</p>
                <p>Watching anime isn't just a hobby; it's a source of inspiration, joy, and connection. It's a reminder that imagination knows no bounds and that the human spirit is capable of overcoming any obstacle. Through the colorful tapestry of anime, I find solace, inspiration, and a sense of belonging in a world filled with endless possibilities.</p>
            </div>
        </section>

        <!-- Gallery -->
        <section id="gallery" class="fade-in">
            <h2>Photo Gallery</h2>
            <div class="row gallery">
                <div class="col-md-4">
                    <img src="hamaad1.jpg" alt="Hamaad in colorful outfit" class="img-fluid">
                </div>
                <div class="col-md-4">
                    <img src="hamaad2.jpg" alt="Hamaad in formal attire" class="img-fluid">
                </div>
                <div class="col-md-4">
                    <img src="hamaad3.jpg" alt="Hamaad in front of a backdrop" class="img-fluid">
                </div>
            </div>
        </section>

        <!-- Contact -->
        <section id="contact" class="fade-in">
            <h2>Contact Me</h2>
            <p>You can reach me via the following:</p>
            <ul class="contact-info">
                <li><strong>Email:</strong> <a href="mailto:bhathamaad68@gmail.com">bhathamaad68@gmail.com</a></li>
                <li><strong>Phone:</strong> +91 6005878067</li>
                <li><strong>Social Media:</strong>
                    <ul>
                        <li><a href="https://instagram.com/iifrit_">Instagram: iifrit_</a></li>
                        <li><a href="https://twitter.com/hamaad">Twitter</a></li>
                        <li><a href="https://www.linkedin.com/in/hamaad/">LinkedIn</a></li>
                        <li><a href="https://github.com/hamaad">GitHub</a></li>
                    </ul>
                </li>
            </ul>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Hamaad's Personal Home Page</p>
    </footer>

    <!-- JavaScript for scroll animations -->
    <script>
        // JavaScript for scroll animations
        window.addEventListener('scroll', reveal);

        function reveal() {
            var reveals = document.querySelectorAll('.fade-in');
            for (var i = 0; i < reveals.length; i++) {
                var windowHeight = window.innerHeight;
                var revealTop = reveals[i].getBoundingClientRect().top;
                var revealPoint = 50;

                if (revealTop < windowHeight - revealPoint) {
                    reveals[i].classList.add('active');
                }
            }
        }
    </script>
</body>
</html>
