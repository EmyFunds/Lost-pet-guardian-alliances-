<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Lost Pet Guardian Alliances</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #fef9f0;
    margin: 0;
    color: #4b4b4b;
  }
  header {
    background-color: #7f9e89;
    padding: 20px;
    text-align: center;
    color: white;
    font-size: 2em;
    font-weight: bold;
  }
  nav {
    background-color: #a3c4a2;
    display: flex;
    justify-content: center;
    gap: 25px;
    padding: 12px 0;
  }
  nav a {
    text-decoration: none;
    color: #2b3a2e;
    font-weight: 600;
  }
  nav a:hover {
    color: #1a2a1a;
  }
  main {
    max-width: 900px;
    margin: 30px auto;
    padding: 0 20px;
  }
  section {
    margin-bottom: 40px;
  }
  h2 {
    color: #2f4f2f;
    border-bottom: 3px solid #7f9e89;
    padding-bottom: 8px;
    margin-bottom: 15px;
  }
  p {
    line-height: 1.6;
  }
  form {
    background: #f0f6f0;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 8px #b2d3b2;
  }
  label {
    display: block;
    margin: 10px 0 6px;
    font-weight: 600;
  }
  input[type="text"],
  input[type="email"],
  textarea {
    width: 100%;
    padding: 8px;
    border: 2px solid #7f9e89;
    border-radius: 5px;
    font-size: 1em;
    resize: vertical;
  }
  textarea {
    height: 100px;
  }
  button {
    margin-top: 15px;
    padding: 10px 20px;
    background-color: #7f9e89;
    border: none;
    color: white;
    font-weight: 700;
    font-size: 1em;
    border-radius: 5px;
    cursor: pointer;
  }
  button:hover {
    background-color: #678561;
  }
  footer {
    text-align: center;
    padding: 20px;
    background-color: #a3c4a2;
    color: #2b3a2e;
    margin-top: 40px;
  }
  @media (max-width: 600px) {
    nav {
      flex-direction: column;
      gap: 15px;
    }
  }
</style>
</head>
<body>

<header>
  Lost Pet Guardian Alliances
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#services">Services</a>
  <a href="#report">Report a Lost Pet</a>
  <a href="#about">About Us</a>
  <a href="#contact">Contact</a>
</nav>

<main>
  <section id="home">
    <h2>Welcome to Lost Pet Guardian Alliances</h2>
    <p>Your trusted partner in reuniting lost pets with their loving families. We provide support, guidance, and community alerts to help find your furry friends quickly and safely.</p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <ul>
      <li><strong>Lost Pet Support:</strong> Personalized assistance during your search.</li>
      <li><strong>Search Guidance:</strong> Proven strategies to maximize search success.</li>
      <li><strong>Community Alerts:</strong> Notify local pet lovers and shelters instantly.</li>
    </ul>
  </section>

  <section id="report">
    <h2>Report a Lost Pet</h2>
    <form id="lostPetForm" action="mailto:emmanueljoeboy81@gmail.com" method="POST" enctype="text/plain" onsubmit="alert('Thank you for reporting. We will help you find your pet!');">
      <label for="ownerName">Your Name:</label>
      <input type="text" id="ownerName" name="Owner Name" required />

      <label for="email">Your Email:</label>
      <input type="email" id="email" name="Email" required />

      <label for="petName">Pet's Name:</label>
      <input type="text" id="petName" name="Pet Name" required />

      <label for="petDescription">Description of Your Pet:</label>
      <textarea id="petDescription" name="Pet Description" required></textarea>

      <label for="lastSeen">Where and When Was Your Pet Last Seen?</label>
      <textarea id="lastSeen" name="Last Seen Location and Time" required></textarea>

      <button type="submit">Submit Report</button>
    </form>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Lost Pet Guardian Alliances was created out of love and commitment to help families reunite with their lost pets. We understand how heartbreaking it can be, and our mission is to provide compassionate support, expert guidance, and a strong community network to bring pets home safely.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Have questions or need immediate assistance? Reach out to us anytime!</p>
    <p>Email: <a href="mailto:emmanueljoeboy81@gmail.com">emmanueljoeboy81@gmail.com</a></p>
  </section>
</main>

<footer>
  &copy; 2025 Lost Pet Guardian Alliances. All rights reserved.
</footer>

</body>
</html># Lost-pet-guardian-alliances-
Pet service 
