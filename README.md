# MDAP-EX_01-Portfolio

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poojasree B - Portfolio</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: "Arial", sans-serif;
            background: #f4f4f4;
            color: #222;
        }

        header {
            background: #000;
            color: white;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.3rem;
            letter-spacing: 1px;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }

        nav a:hover {
            color: orangered;
        }

        .container {
            width: 90%;
            max-width: 900px;
            margin: 40px auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
        }

        h2 {
            font-size: 1.8rem;
            margin-bottom: 10px;
            border-left: 5px solid orangered;
            padding-left: 10px;
        }

        p, li {
            font-size: 1.1rem;
            line-height: 1.7;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 15px;
            margin-top: 30px;
            background: #111;
            color: white;
        }

        footer a {
            color: orangered;
            text-decoration: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>POOJASREE B</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="container">

        <section id="about">
            <h2>About Me</h2>
            <p>
                Hello! I'm <strong>Poojasree B</strong>, a passionate learner who loves building clean, simple, and meaningful tech solutions. 
                I enjoy coding, problem-solving, and creating user-friendly apps and websites.  
                I always aim for clarity, creativity, and continuous improvement.
            </p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li><strong>Wildfire Prediction Model</strong> – Built ML-based wildfire prediction using real-time data.</li>
                <li><strong>BlueAI Fishing Assistant</strong> – Smart assistant for vessel tracking & sustainability.</li>
                <li><strong>FakeArt & Bias Buster</strong> – AI tools for AI-art detection and unbiased news analysis.</li>
            </ul>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:poojasree.balasubramanian@gmail.com">poojasree.balasubramanian@gmail.com</a></p>
            <p>LinkedIn: <a href="https://www.linkedin.com/in/poojasree-balasubramanian/" target="_blank">linkedin.com/in/poojasree-balasubramanian</a></p>
            <p>GitHub: <a href="https://github.com/POOJASREE-B" target="_blank">github.com/POOJASREE-B</a></p>
        </section>

    </div>

    <footer>
        © 2025 Poojasree B — <a href="#about">Back to Top</a>
    </footer>

</body>
</html>

```

## OUTPUT
<img width="1912" height="807" alt="image" src="https://github.com/user-attachments/assets/ff97bcd4-8035-4515-a246-61dcde628a43" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
