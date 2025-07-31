<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>BISU Calape Campus</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #004a8f;
      color: white;
      padding: 20px 40px;
      text-align: center;
    }
    nav {
      background-color: #003765;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px;
    }
    footer {
      background-color: #004a8f;
      color: white;
      text-align: center;
      padding: 15px;
    }
    .card {
      background: white;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      margin-bottom: 20px;
    }
    .grid {
      display: grid;
      gap: 20px;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    }
  </style>
</head>
<body>
  <header>
    <h1>Bohol Island State University</h1>
    <h2>Calape Campus</h2>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#courses">Courses</a>
    <a href="#news">News</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <div class="card">
      <p>
        BISU Calape Campus is a premier institution committed to academic excellence, innovation, and community development in the Province of Bohol. We offer a variety of programs to equip students for future success.
      </p>
    </div>
  </section>

  <section id="courses">
    <h2>Our Courses</h2>
    <div class="grid">
      <div class="card"><strong>BS in Information Technology-Food Preparation</strong></div>
      <div class="card"><strong>BS in Fisheries</strong></div>
      <div class="card"><strong>BS in Education Major in English, Filipino</strong></div>
      <div class="card"><strong>BS in Secondary Education</strong></div>
    </div>
  </section>

  <section id="news">
    <h2>Latest News & Events</h2>
    <div class="card">
      <h3>Graduation 2025</h3>
      <p>Join us in celebrating the achievements of our graduates on April 2025. Details to follow.</p>
    </div>
    <div class="card">
      <h3>Enrollment for 1st Semester SY 2025–2026</h3>
      <p>Online and in-campus enrollment starts June 15, 2025. Prepare your documents.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <div class="card">
      <p><strong>Location:</strong> San Isidro,Calape, Bohol, Philippines</p>
      <p><strong>Email:</strong> ninoemmanuel.cejas@bisucalape.edu.ph</p>
      <p><strong>Phone:</strong> +63 945 7432 874</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 BISU Calape Campus. All rights reserved.</p>
  </footer>
</body>
</html>
