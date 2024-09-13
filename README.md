<style>
  /* Existing body and global styles remain unchanged */
  body {
    background-color: #2e2e2e;
    color: #f0f0f0;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }

  /* Main container */
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
  }

  /* Sections and Headings */
  .intro, .projects, .skills, .stats, .contact, .about, .achievements {
    margin-bottom: 30px;
  }

  .intro h1, .projects h2, .skills h2, .stats h2, .contact h2, .about h2, .achievements h2 {
    color: #f0f0f0;
  }

  /* Card Styling */
  .project-card, .stat-card {
    background: rgba(255, 255, 255, 0.1); /* Cloudy translucent background */
    border: 1px solid #444;
    border-radius: 10px;
    padding: 20px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
    text-align: center;
    transition: transform 0.3s, box-shadow 0.3s;
  }

  .project-card:hover, .stat-card:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.5);
  }

  .project-card h3, .stat-card h3 {
    color: #ffcc00; /* Gold color for headings */
  }

  /* Flexbox Container for Stats */
  .stats-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    justify-content: center;
    align-items: stretch;
  }

  /* Mobile First, small devices */
  @media (max-width: 768px) {
    .stats-container {
      grid-template-columns: 1fr;
      gap: 20px;
    }
  }

  /* Adjustments for larger screens */
  @media (min-width: 768px) {
    .stats-container {
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); 
      justify-content: space-evenly;
    }
  }

  /* Stats Cards on Hover */
  .stat-card:hover {
    transform: scale(1.05);
    transition: all 0.3s ease;
  }




.stats {
  width: 90%;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  background-color: #282828;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.4);
}

.stats h2 {
  font-size: 1.8rem;
  text-align: center;
  margin-bottom: 20px;
  color: #f0f0f0;
}

.stats-masonry {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); /* Responsive grid */
  gap: 20px;
}

.stat-card {
  background-color: #333;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
}

.stat-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.6);
}

.stat-card img {
  width: 100%;
  height: auto;
  border-radius: 8px;
}

@media (max-width: 768px) {
  .stats h2 {
    font-size: 1.5rem;
  }

  .stat-card img {
    max-height: 200px; /* To keep the images proportional on smaller screens */
  }
}





</style>




<div class="container" align="center">
  <div class="intro">
    <h1>Hello, I'm Adarsh!</h1>
    <p>Computer Science Student | AI & ML Enthusiast | Space Explorer</p>
    <p>
      <img src="https://img.shields.io/badge/Computer_Science_Student-lightblue?style=flat&logo=github" alt="Student Badge">
      <img src="https://img.shields.io/badge/Specialization-AI%20%26%20ML-lightgreen?style=flat&logo=github" alt="Specialization Badge">
    </p>
  </div>

  <hr style="border: 0; border-top: 3px solid #444;">

  <div class="about">
    <h2>🔍 About Me</h2>
    <p>I'm a passionate Computer Science student with a specialization in AI & ML. My interests include exploring new technologies, coding, and diving deep into space exploration.</p>
  </div>

  <hr style="border: 0; border-top: 3px solid #444;">

  <div class="projects">
    <h2>🚀 Projects</h2>
    <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
      <div class="project-card">
        <a href="https://github.com/Adarshv0524/MedQueue" style="text-decoration: none; color: inherit;">
          <h3>MedQueue</h3>
          <p>Emergency beds are allotted based on vitals, medical history, and other factors by computing an emergency score for each patient and giving the patient with the highest emergency score priority.</p>
        </a>
      </div>
      <div class="project-card">
        <a href="https://github.com/Adarshv0524/Smart-Select" style="text-decoration: none; color: inherit;">
          <h3>Smart Select</h3>
          <p>Our software analyzes millions of reviews to determine what people love and dislike about cellphones. Get tailored suggestions based on favorable experiences, so you can make educated decisions.</p>
        </a>
      </div>
      <div class="project-card">
        <a href="https://github.com/Adarshv0524/Portfolio" style="text-decoration: none; color: inherit;">
          <h3>Personal Website</h3>
          <p>AI created a personal website and portfolio to showcase my accomplishments in an organized manner. I utilized HTML, CSS, and JavaScript, as well as a Web3forms API to add forms for receiving answers.</p>
        </a>
      </div>

  </div>

  <hr style="border: 0; border-top: 3px solid #444;">

  <div class="skills">
    <h2>💼 Skills</h2>
    <div>
      <img src="https://img.shields.io/badge/Python-80%25-lightblue?style=flat&logo=python" alt="Python Badge">
      <img src="https://img.shields.io/badge/Java-70%25-lightgreen?style=flat&logo=java" alt="Java Badge">
      <img src="https://img.shields.io/badge/ML-75%25-lightyellow?style=flat&logo=google" alt="Machine Learning Badge">
      <img src="https://img.shields.io/badge/JavaScript-65%25-lightcoral?style=flat&logo=javascript" alt="JavaScript Badge">
      <img src="https://img.shields.io/badge/SQL-70%25-lightpurple?style=flat&logo=sql" alt="SQL Badge">
    </div>
  </div>

  <hr style="border: 0; border-top: 3px solid #444;">

<div class="stats">
  <h2>📊 GitHub Stats</h2>
  <div class="stats-masonry">
    <div class="stat-card">
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=Adarshv0524&theme=react-dark" alt="GitHub Contribution Graph">
    </div>
    <div class="stat-card">
      <img src="https://github-readme-stats.vercel.app/api?username=Adarshv0524&show_icons=true&hide_title=true&count_private=true" alt="Adarsh's GitHub Stats">
    </div>
    <div class="stat-card">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Adarshv0524&layout=compact" alt="Top Languages">
    </div>
    <div class="stat-card">
      <img src="https://github-profile-trophy.vercel.app/?username=Adarshv0524&theme=onestar&margin-w=15&margin-h=15" alt="GitHub Trophies">
    </div>
    <div class="stat-card">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=Adarshv0524&theme=dark&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub Streak Stats">
    </div>
    <div class="stat-card">
      <img src="https://www.codewars.com/users/Adarshv0524/badges/large" alt="Codewars Badge">
    </div>
    <div class="stat-card">
      <img src="https://visitor-badge.glitch.me/badge?page_id=Adarshv0524.visitor-badge" alt="Visitor Count">
    </div>
  </div>
</div>



  <hr style="border: 0; border-top: 3px solid #444;">

  <!-- <div class="achievements">
    <h2🏆 Achievements</h2>
    <p>Highlight any awards, certifications, or notable accomplishments here.</p>
  </div> -->

  <hr style="border: 0; border-top: 3px solid #444;">

  <div class="contact">
    <h2>🌐 Contact</h2>
    <p>
      <a href="https://www.linkedin.com/in/Adarshv0524" style="text-decoration: none; color: #0077b5;">LinkedIn</a> |
      <a href="https://twitter.com/Adarshv0524" style="text-decoration: none; color: #1da1f2;">Twitter</a> |
      <a href="https://adarshv0524.github.io/Portfolio/" style="text-decoration: none; color: #007acc;">Personal Website</a>
    </p>
    <img src="https://linktoyourimage.com/image.jpg" alt="Adarsh's Image">
  </div>
</div>


