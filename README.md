<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Academic Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="profile">
            <img src="profile.jpg" alt="Profile Picture" class="profile-pic">
            <h1>Dr. [Your Name]</h1>
            <p>Position | Institution | Area of Expertise</p>
        </div>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#research">Research</a></li>
            <li><a href="#publications">Publications</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>Brief bio and current research interests.</p>
        </section>
        <section id="research">
            <h2>Research Areas</h2>
            <ul>
                <li>Topic 1</li>
                <li>Topic 2</li>
                <li>Topic 3</li>
            </ul>
        </section>
        <section id="publications">
            <h2>Publications</h2>
            <ul>
                <li><a href="#">Paper 1</a> - Journal/Conference</li>
                <li><a href="#">Paper 2</a> - Journal/Conference</li>
                <li><a href="#">Paper 3</a> - Journal/Conference</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
            <p>Phone: +1234567890</p>
        </section>
    </main>
    <footer>
        <p>© [Year] [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    text-align: center;
    background: #f4f4f4;
    padding: 20px;
}

.profile-pic {
    width: 150px;
    height: 150px;
    border-radius: 50%;
}

nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    background: #333;
    padding: 10px 0;
    margin: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

nav ul li a:hover {
    text-decoration: underline;
}

main {
    padding: 20px;
    max-width: 800px;
    margin: auto;
}

section {
    margin-bottom: 20px;
}

footer {
    text-align: center;
    background: #333;
    color: white;
    padding: 10px 0;
}
