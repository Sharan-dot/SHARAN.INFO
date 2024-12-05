<!-- styles.css -->
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styling */
body {
    font-family: Arial, sans-serif;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}


/* Header Navigation */
header {
    position: absolute;
    top: 10px;
    text-align: center;
    width: 100%;
}

header button {
    padding: 15px 30px;
    font-size: 16px;
    font-weight: bold;
    border: none;
    background-color: #333;
    color: white;
    cursor: pointer;
    margin: 0 10px;
}

header button:hover {
    background-color: #555;
}

/* Footer */
footer {
    position: absolute;
    bottom: 10px;
    width: 100%;
    text-align: center;
    background-color: rgba(0, 0, 0, 0.8);
    padding: 10px 0;
}

/* Center Text with Solid Black Background */
main h1 {
    font-size: 48px;
    font-weight: bold;
    margin-bottom: 20px;
    background-color: black; /* Fully black background */
    padding: 10px 20px;
    border-radius: 10px;
    display: inline-block;
}

main p {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
    background-color: black; /* Fully black background */
    padding: 10px 20px;
    border-radius: 10px;
    display: inline-block;
}

/* Highlighted Background for Specific List Items */
.highlight {
    background-color: rgba(0, 0, 0, 0.7); /* Dark transparent background */
    color: white; /* Text color */
    padding: 10px;
    border-radius: 5px; /* Rounded corners */
    margin: 10px 0; /* Space between list items */
    display: inline-block; /* Keeps the background tight around the text */
}


/* Backgrounds */
.home {
    background: url('../home.jpg') no-repeat center center/cover;
}

.about {
    background: url('../about.jpg') no-repeat center center/cover;
}

.contact {
    background: url('../contact.jpg') no-repeat center center/cover;
}

.work {
    background: url('../work.jpg') no-repeat center center/cover;
}

<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - Sharan Muhhuku</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body class="home">
    <header>
        <nav>
            <button onclick="window.location.href='about.html'">Forward</button>
            <button onclick="window.location.href='contact.html'">Skip</button>
        </nav>
    </header>
    <main>
        <h1>Welcome to Sharan's UX Portfolio</h1>
        <p>Hi, I'm Sharan Muhhuku. Welcome to my portfolio website where I introduce myself to you and the accomplishments 
            I've achieved in the field of Ux design.</p>
        <p>Please use the buttons at the top to skip from page to page and the skip button to jump to my contact page</p>
    </main>
    <footer>
        <p>@ Sharan 2024</p>
    </footer>
</body>
</html>

<!-- about.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me - Sharan Muhhuku</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body class="about">
    <header>
        <nav>
            <button onclick="window.location.href='index.html'">Back</button>
            <button onclick="window.location.href='work.html'">Forward</button>
            <button onclick="window.location.href='contact.html'">Skip</button>
        </nav>
    </header>
    <main>
        <h1>About Me</h1>
        <p>Hello! My name is Sharan Muhhuku, and I am currently pursuing a Bachelor of Arts in User Experience (UX) Design at Wilfrid Laurier University. Based in Canada, I am passionate about creating meaningful and user-friendly digital experiences that make a positive impact on people's lives..</p>
        <p>As a UX Design student, I enjoy exploring the intersection of creativity and functionality. My studies have deepened my understanding of how design influences user behavior, and I’m constantly inspired by the challenge of solving real-world problems through innovative and accessible solutions.</p>
        <p>When I’m not immersed in design projects, I love exploring new ideas, connecting with others, and learning about emerging trends in technology and design. I’m always eager to grow my skills and collaborate with like-minded individuals who share a passion for improving the way we interact with the digital world.</p>
        <p>Feel free to reach out or connect—I’d love to share ideas!</p>
    </main>
    <footer>
        <p>@ Sharan 2024</p>
    </footer>
</body>
</html>

<!-- work.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Work - Sharan Muhhuku</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body class="work">
    <header>
        <nav>
            <button onclick="window.location.href='about.html'">Back</button>
            <button onclick="window.location.href='contact.html'">Forward</button>
            <button onclick="window.location.href='contact.html'">Skip</button>
        </nav>
    </header>
    <main>
        <h1>My Work</h1>
        <p>Coming soon! I will be showcasing my projects,case studies, and accomplishments here as I progress through University, Co-op and starting work.</p>
    </main>
    <footer>
        <p>@ Sharan 2024</p>
    </footer>
</body>
</html>

<!-- contact.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact - Sharan Muhhuku</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body class="contact">
    <header>
        <nav>
            <button onclick="window.location.href='work.html'">Back</button>
            <button onclick="window.location.href='index.html'">Skip</button>
        </nav>
    </header>
    <main>
        <h1>Contact me📞</h1>
        <p>Feel free to reach out for collaborations or just a friendly chat!</p>
        <ul>
        <li class="highlight">Email: <a href="mailto:sharan@example.com">sharan@example.com</a></li>
        <li class="highlight">LinkedIn: <a href="https://www.linkedin.com/in/sharan">Sharan's LinkedIn Profile</a></li>
       </ul>

    </main>
    <footer>
        <p>@ Sharan 2024</p>
    </footer>
</body>
</html>
