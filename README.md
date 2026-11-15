<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Bio</title>
  <style>
    * { box-sizing: border-box; }

    body {
      margin: 0;
      padding: 2rem;
      font-family: Arial, sans-serif;
      background: #f3f4f6;
      color: #222;
    }

    .bio-card {
      max-width: 650px;
      margin: 2rem auto;
      padding: 2rem;
      background: white;
      border-radius: 16px;
      box-shadow: 0 8px 24px #00000014;
      text-align: center;
    }

    .bio-card img {
      width: 140px;
      height: 140px;
      object-fit: cover;
      border-radius: 50%;
    }

    h1 { margin-bottom: 0.25rem; }
    .role { color: #555; margin-top: 0; }
    .details { text-align: left; margin-top: 2rem; }
    .details p { line-height: 1.6; }

    a { color: #2563eb; }

    @media (max-width: 480px) {
      body { padding: 1rem; }
      .bio-card { padding: 1.5rem; }
    }
  </style>
</head>
<body>
  <main class="bio-card">
    <img src="https://via.placeholder.com/140" alt="Profile photo">
    <h1>Your Name</h1>
    <p class="role">Your Job Title or Role</p>

    <section class="details">
      <h2>About Me</h2>
      <p>
        Write a short introduction about yourself, your interests,
        and what you do.
      </p>

      <h2>Details</h2>
      <p><strong>Location:</strong> Your City</p>
      <p><strong>Email:</strong> <a href="mailto:you@example.com">you@example.com</a></p>
      <p><strong>Skills:</strong> HTML, CSS, JavaScript</p>
      <p><strong>Interests:</strong> Reading, music, and travel</p>
    </section>
  </main>
</body>
</html>
