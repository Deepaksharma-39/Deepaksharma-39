<!DOCTYPE html>
<html>

<head>
  <style>
    body {
      background-color: #0c1117;
      color: #c9d1d9;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      margin: 0;
    }

    .container {
      text-align: center;
    }

    .profile-img {
      border-radius: 50%;
      border: 2px solid #58a6ff;
      width: 150px;
      height: 150px;
      object-fit: cover;
    }

    .heading {
      font-size: 2.5rem;
      margin-top: 1rem;
    }

    .subheading {
      font-size: 1.5rem;
      margin-top: 0.5rem;
      color: #58a6ff;
    }

    .social-icons a {
      margin: 0 0.5rem;
      color: #58a6ff;
      transition: color 0.3s ease;
    }

    .social-icons a:hover {
      color: #79c0ff;
    }

    .languages {
      margin-top: 2rem;
    }

    .stats {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 2rem;
    }

    .stats img {
      margin: 0 1rem;
      width: 40px;
      height: 40px;
    }
  </style>
</head>

<body>
  <div class="container">
    <img src="profile.jpg" alt="Profile Image" class="profile-img">
    <h1 class="heading">Hi 👋, I'm Deepak Sharma</h1>
    <h3 class="subheading">A Java Developer from India</h3>

    <div class="social-icons">
      <a href="https://linkedin.com/in/d33pak-sharma" target="blank">&#128100;</a>
      <a href="https://stackoverflow.com/users/deepak-sharma" target="blank">&#128640;</a>
      <a href="https://www.hackerrank.com/deepaksharmaa_39" target="blank">&#127891;</a>
    </div>

    <div class="languages">
      <img src="java.svg" alt="Java" title="Java">
      <img src="spring.svg" alt="Spring" title="Spring">
      <img src="javascript.svg" alt="JavaScript" title="JavaScript">
      <img src="aws.svg" alt="AWS" title="AWS">
      <img src="mysql.svg" alt="MySQL" title="MySQL">
      <img src="nodejs.svg" alt="Node.js" title="Node.js">
    </div>

    <div class="stats">
      <img src="code.svg" alt="Code">
      <p>Working on Java, Spring, and Rest APIs</p>
    </div>
  </div>
</body>

</html>
