# Assignment 3.5 — Blog / Portfolio Mini-Project

**File name: `index.html`**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
</head>
<body>
    <header>
        <h1>Atul Kumar Pal</h1>
        <p>B.Tech CSE Student</p>
    </header>

    <nav>
        <a href="#about">About</a> |
        <a href="#skills">Skills</a> |
        <a href="#projects">Projects</a> |
        <a href="#contact">Contact</a>
    </nav>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>I am learning web development and programming.</p>
            <img src="images/profile.jpg"
                 alt="My profile photo" width="150">
        </section>

        <section id="skills">
            <h2>Skills & Interests</h2>
            <ul>
                <li>HTML</li>
                <li>CSS</li>
                <li>Programming</li>
            </ul>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <article>
                <h3>Personal Webpage</h3>
                <p>My first HTML project.</p>
            </article>
            <a href="https://github.com" target="_blank"
               rel="noopener noreferrer">GitHub</a>
        </section>
    </main>

    <footer id="contact">
        <h2>Contact</h2>
        <p>Email: your-email@example.com</p>
        <p>© 2026 My Portfolio</p>
    </footer>
</body>
</html>
```

### Submission
1. Save as `index.html` and add your image inside the `images` folder.
2. Open the page in a browser and take a screenshot.
3. Upload the project to GitHub and submit your repository link.

**Git commands:**
```bash
git init
git add .
git commit -m "Create portfolio website"
```

*Replace the sample email and image with your own details. The GitHub link must be created after uploading the project.*