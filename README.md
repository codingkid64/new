# new
<!DOCTYPE html>
<html>
  <head>
    <title>SeeStream</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#signup">Signup</a></li>
          <li><a href="#login">Login</a></li>
          <li><a href="#about">About</a></li>
        </ul>
      </nav>
    </header>
    <section id="home">
      <h1>A platform for watching videos</h1>
      <p>Recomended for you</p>
    </section>
    <section id="about">
      <h2>Signup</h2>
      <p>Signup here to create an account to start watching videos.</p>
    </section>
    <section id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Website Design</li>
        <li>Website Development</li>
        <li>Search Engine Optimization</li>
      </ul>
    </section>
    <section id="contact">
      <h2>Contact Us</h2>
      <form action="submit-form.php" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
        <button type="submit">Submit</button>
      </form>
    </section>
    <footer>
      <p>Copyright ©2022 My Website</p>
    </footer>
  </body>
</html>
