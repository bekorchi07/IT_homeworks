<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Exercise 5: Full Semantic Portfolio Page</title>
</head>
<body>
  <header>
    <h1>Lee Jin — Web Developer</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#skills">Skills</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section id="about">
      <h2>About Me</h2>
      <figure>
        <img src="https://picsum.photos/200/200?random=1" alt="Profile photo of Lee Jin" width="200" height="200">
        <figcaption>Lee Jin, Full-stack Web Developer</figcaption>
      </figure>
      <p>I'm a passionate <mark>web developer</mark> with expertise in modern web technologies. I specialize in building responsive, accessible web applications using <abbr title="HyperText Markup Language">HTML</abbr>, CSS, and JavaScript.</p>
    </section>
       <section id="projects">
      <h2>Projects</h2>
      <article>
        <header>
          <h3>E-commerce Platform</h3>
          <p><time datetime="2026-08">August 2026</time></p>
        </header>
        <p>Built a full-featured e-commerce site using <code>React</code> and <code>Node.js</code>. The platform includes product listings, shopping cart functionality, and secure payment processing.</p>
      </article>
    </section>

    <aside>
      <h2>Skills</h2>
      <ul>
        <li>HTML5 & Semantic Markup</li>
        <li>CSS3 & Responsive Design</li>
        <li>JavaScript & ES6+</li>
        <li>React & Vue.js</li>
        <li>Node.js & Express</li>
        <li>Database Design & SQL</li>
      </ul>
    </aside>

    <section id="contact">
      <h2>Contact</h2>
      <address>
        Email: <a href="mailto:leejin@example.com">leejin@example.com</a><br>
        Phone: <a href="tel:+82-10-1234-5678">+82-10-1234-5678</a><br>
        Location: Seoul, South Korea
      </address>
    </section>

 
  </main>

  <footer>
    <p>&copy; 2026 Lee Jin. All rights reserved.</p>
  </footer>

</body>
</html>
