<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Jaseela Noushad - Fullstack Developer</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet" />
<style>
  body {
    font-family: 'Poppins', sans-serif;
    background: #ffe6f0;
    color: #4a004a;
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    min-height: 100vh;
  }
  h1, h3 {
    text-align: center;
    margin: 0.2em 0;
  }
  h1 {
    font-weight: 600;
    font-size: 2.8rem;
    color: #d6336c;
  }
  h3 {
    font-weight: 400;
    font-size: 1.5rem;
    color: #a8326a;
  }
  p {
    max-width: 600px;
    text-align: center;
    font-weight: 300;
    font-size: 1.1rem;
    margin: 0.5em 1em;
  }
  a {
    color: #d6336c;
    text-decoration: none;
    transition: color 0.3s ease;
  }
  a:hover {
    color: #a8326a;
  }
  .profile-views {
    margin: 1em 0;
  }
  .trophy {
    margin: 1em 0;
  }
  .contact, .resume, .connect, .skills {
    margin: 1.5em 0;
    width: 100%;
    max-width: 700px;
  }
  .contact p, .resume p {
    font-weight: 400;
    font-size: 1.2rem;
  }
  .connect a {
    margin-right: 1em;
    display: inline-block;
    transition: transform 0.3s ease;
  }
  .connect a:hover {
    transform: scale(1.2);
  }
  .skills img {
    margin: 0.3em;
    vertical-align: middle;
    width: 40px;
    height: 40px;
    filter: drop-shadow(0 0 2px #d6336c);
    transition: filter 0.3s ease;
  }
  .skills img:hover {
    filter: drop-shadow(0 0 6px #a8326a);
  }
  .stats {
    margin-top: 2em;
    max-width: 700px;
    background: #fce4f0;
    border-radius: 12px;
    padding: 1em;
    box-shadow: 0 4px 8px rgba(214, 51, 108, 0.2);
  }
  /* Animations */
  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  .fadeInUp {
    animation: fadeInUp 1s ease forwards;
  }
</style>
</head>
<body>
  <h1 class="fadeInUp">Hi 👋, I'm Jaseela Noushad</h1>
  <h3 class="fadeInUp" style="animation-delay: 0.3s;">A passionate Fullstack Developer</h3>

  <p class="profile-views fadeInUp" style="animation-delay: 0.6s;">
    <img src="https://komarev.com/ghpvc/?username=jasln1414&label=Profile%20views&color=ff00d0&style=flat" alt="jasln1414" />
  </p>

  <p class="trophy fadeInUp" style="animation-delay: 0.9s;">
    <a href="https://github.com/ryo-ma/github-profile-trophy" target="_blank" rel="noopener noreferrer">
      <img src="https://github-profile-trophy.vercel.app/?username=jasln1414" alt="jasln1414" />
    </a>
  </p>

  <div class="contact fadeInUp" style="animation-delay: 1.2s;">
    <p>📫 How to reach me <strong>Jaseela1414@gmail.com</strong></p>
  </div>

  <div class="resume fadeInUp" style="animation-delay: 1.5s;">
    <p>📄 Check out my resume ! <a href="https://drive.google.com/file/d/1K26E9HOVCzEeQPmWOPSxc42bJjOmtb6t/view?usp=sharing" target="_blank" rel="noopener noreferrer">Resume Link</a></p>
  </div>

  <h3 class="fadeInUp" style="animation-delay: 1.8s;">Connect with me:</h3>
  <div class="connect fadeInUp" style="animation-delay: 2.1s;">
    <a href="https://linkedin.com/in/https://www.linkedin.com/in/jaseela-noushad-161a332b4/" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" width="40" height="40" />
    </a>
  </div>

  <h3 class="fadeInUp" style="animation-delay: 2.4s;">Languages and Tools:</h3>
  <p class="skills fadeInUp" style="animation-delay: 2.7s;">
    <a href="https://aws.amazon.com" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" />
    </a>
    <a href="https://www.cprogramming.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" />
    </a>
    <a href="https://www.w3schools.com/css/" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" />
    </a>
    <a href="https://www.djangoproject.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" />
    </a>
    <a href="https://www.docker.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" />
    </a>
    <a href="https://www.figma.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" />
    </a>
    <a href="https://www.w3.org/html/" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" />
    </a>
    <a href="https://www.java.com" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" />
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" />
    </a>
    <a href="https://kubernetes.io" target="_blank" rel="noopener noreferrer">
      <img src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg" alt="kubernetes" />
    </a>
    <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noopener noreferrer">
      <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" />
    </a>
    <a href="https://www.mysql.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" />
    </a>
    <a href="https://www.postgresql.org" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" />
    </a>
    <a href="https://www.python.org" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" />
    </a>
    <a href="https://reactjs.org/" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" />
    </a>
    <a href="https://reactnative.dev/" target="_blank" rel="noopener noreferrer">
      <img src="https://reactnative.dev/img/header_logo.svg" alt="reactnative" />
    </a>
    <a href="https://redux.js.org" target="_blank" rel="noopener noreferrer">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="redux" />
    </a>
    <a href="https://tailwindcss.com/" target="_blank" rel="noopener noreferrer">
      <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" />
    </a>
  </p>

  <div class="stats fadeInUp" style="animation-delay: 3s;">
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=jasln1414&show_icons=true&locale=en&layout=compact" alt="jasln1414" />
  </div>
</body>
</html>

