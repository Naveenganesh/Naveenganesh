- 👋 Hi, I’m @Naveenganesh
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SVCE College Library</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #1976D2;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #2196F3;
            overflow: hidden;
            padding: 10px 0;
            text-align: center;
        }

        nav a {
            display: inline-block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            margin: 0 10px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        nav a:hover {
            background-color: #1565c0;
        }

        main {
            padding: 20px;
        }

        .contact-details {
            display: none;
        }

        footer {
            background-color: #1976D2;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            bottom: 0;
            width: 100%;
            transition: background-color 0.3s ease;
        }
    </style>
</head>
<body>

    <header>
        <h1>SVCE College Library</h1>
    </header>

    <nav>
        <a href="#" onclick="showContent('home')">Home</a>
        <a href="#" onclick="showContent('catalog')">Catalog</a>
        <a href="#" onclick="showContent('events')">Events</a>
        <a href="#" onclick="showContent('resources')">Resources</a>
        <a href="#" onclick="showAboutUs()">About Us</a>
        <a href="#" onclick="showContact()">Contact</a>
    </nav>

    <main>
        <div id="home" class="content-section">
            <h2>Welcome to SVCE College Library</h2>
            <p>This is where you can showcase some featured books or library highlights specifically tailored for SVCE College.</p>
        </div>

        <!-- ... (other content sections) ... -->

        <div id="about-us" class="content-section">
            <h2>About SVCE College</h2>
            <p>SVCE College is a renowned institution dedicated to providing quality education...</p>
            <!-- Add more details about the college here -->
        </div>
    </main>

    <section id="events" class="content-section">
        <h2>Upcoming Events</h2>
        <p>Stay tuned for exciting library events at SVCE College.</p>
        <!-- Add details or a calendar widget here -->
    </section>

    <section id="contact" class="content-section contact-details">
        <h2>Contact Us</h2>
        <p>Feel free to reach out with any questions or feedback.</p>
        <p>Email: <a href="mailto:library@example.com">library@example.com</a></p>
        <p>Phone: +1 (123) 456-7890</p>
    </section>

    <footer>
        <p>&copy; 2024 SVCE College Library. All rights reserved.</p>
    </footer>

    <script>
        function showContent(sectionId) {
            // Hide all content sections
            var contentSections = document.querySelectorAll('.content-section');
            contentSections.forEach(function(section) {
                section.style.display = 'none';
            });

            // Show the selected content section
            var selectedSection = document.getElementById(sectionId);
            if (selectedSection) {
                selectedSection.style.display = 'block';
            }
        }

        function showAboutUs() {
            showContent('about-us'); // Assuming the id for the "About Us" section is 'about-us'
        }

        function showContact() {
            var contactSection = document.getElementById("contact");
            contactSection.style.display = "block";
        }
    </script>

</body>
</html>w link to take a look at your changes.
--->
