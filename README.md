# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.

Good luck and happy coding! 🚀💻

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Blog</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Welcome to My Blog</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="blog.html">Blog</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section>
      <h2>Latest Posts</h2>
      <article>
        <h3><a href="post.html">Understanding CSS Grid</a></h3>
        <p>A brief overview of CSS Grid layout...</p>
      </article>
      <!-- More articles -->
    </section>
  </main>
  <footer>
    <p>&copy; 2025 My Blog</p>
  </footer>
  <script src="script.js"></script>
</body>
</html>


body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header, nav, main, footer {
  padding: 20px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 15px;
}

nav a {
  text-decoration: none;
  color: #333;
}

@media (max-width: 600px) {
  nav ul {
    flex-direction: column;
  }
}


document.addEventListener('DOMContentLoaded', () => {
  const toggleButton = document.createElement('button');
  toggleButton.textContent = 'Toggle Dark Mode';
  document.body.insertBefore(toggleButton, document.body.firstChild);

  toggleButton.addEventListener('click', () => {
    document.body.classList.toggle('dark-mode');
  });
});


