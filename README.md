# Ashura-profile
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Profile Webpage - Dark Theme</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0d0d0d;
      color: #e6e6e6;
      overflow-x: hidden;
    }/* Smooth fade-in animation */
* {
  animation: fadeIn 1.2s ease;
}
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

/* Animated gradient header */
header {
  background: linear-gradient(270deg, #1f1f1f, #4a90e2, #1f1f1f);
  background-size: 600% 600%;
  animation: gradientMove 12s ease infinite;
  color: white;
  padding: 40px;
  text-align: center;
}
@keyframes gradientMove {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

.container {
  max-width: 900px;
  margin: 40px auto;
  background: #1a1a1a;
  padding: 30px;
  border-radius: 15px;
  box-shadow: 0 0 25px rgba(0,0,0,0.6);
}

.profile-pic {
  width: 160px;
  height: 160px;
  border-radius: 50%;
  object-fit: cover;
  display: block;
  margin: 0 auto 20px;
  border: 4px solid #4a90e2;
  box-shadow: 0 0 15px #4a90e2;
}

h2 {
  text-align: center;
  color: #4a90e2;
}

.section {
  margin-top: 35px;
  padding: 15px;
  background: #111;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0,0,0,0.4);
}

.section h3 {
  margin-bottom: 10px;
  color: #4a90e2;
}

footer {
  text-align: center;
  padding: 20px;
  color: #777;
}
  /* Background video styling */
#bg-video {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: -1;
  filter: brightness(40%);
}

  </style>
</head>
<body>
  <!-- Background Video -->
  <video autoplay loop muted playsinline id="bg-video">
    <source src="pxxrtto-20251211-0001.mp4" type="video/mp4" />
  </video>  <header>
    <h1>My Profile</h1>
  </header>  <div class="container">
    <img src="https://via.placeholder.com/160" class="profile-pic" alt="Profile Picture" />
    <h2>121 Ashura</h2><div class="section">
  <h3>About Me</h3>
  <p>Hello! I am Ashura. This is my official profile webpage.</p>
</div>

<div class="section">
  <h3>Social & Contact Info</h3>
  <p><strong>Instagram:</strong> @121_ashura_</p>
  <p><strong>Telegram:</strong> @ashurahupgl</p>
</div>

  </div>  <footer>
    <p>© 2025 Ashura Profile Website</p>
  </footer>
</body>
</html>
