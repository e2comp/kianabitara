<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>E2 Computer Lab Exercises</title>
  <style>
    /* General Styling */
    body {
      font-family: Arial, sans-serif;
      background-color: #ffebe8;
      margin: 0;
      padding: 0;
      color: #333;
    }
    .container {
      max-width: 800px;
      margin: 20px auto;
      background: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    header {
      text-align: center;
      margin-bottom: 20px;
    }
    header h1 {
      font-size: 24px;
      color: #d9534f;
    }
    header p {
      font-size: 18px;
      color: #555;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin-bottom: 20px;
    }
    nav button {
      padding: 10px 20px;
      background-color: #d9534f;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    nav button:hover {
      background-color: #c9302c;
    }
    main {
      font-size: 16px;
      line-height: 1.6;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
    }
    video, audio {
      width: 100%;
      margin: 10px 0;
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>E2 COMPUTER LAB EXERCISES</h1>
      <p>By: Kiana Infante Bitara (2 - India)</p>
      <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
    </header>
    <nav>
      <button onclick="navigate('autobiography')">Autobiography</button>
      <button onclick="navigate('article')">Article</button>
      <button onclick="navigate('blog')">Blog</button>
      <button onclick="navigate('form')">Form</button>
    </nav>
    <main id="content">
      <!-- Dynamic content will load here -->
    </main>
  </div>

  <script>
    // Navigate to different pages
    function navigate(page) {
      const content = document.getElementById("content");
      if (page === "autobiography") {
        content.innerHTML = `
          <h2>AUTOBIOGRAPHY</h2>
          <img src="Messenger_creation_3AE8B9A2-D146-4A0F-B95A-C72BD582AC7A.jpeg" alt="Kiana Infante Bitara">
          <p>Kiana Infante Bitara or simply Kai to her family and close relatives, and Lev on wattpad, is an aspiring writer, and a second year college student under the program Bachelor of Science in Criminology in Sorsogon College of Criminology Inc. Born on 17th of September 2003, in San Jose Del Monte Bulacan, she grew up with her aunt and her parents' marriage godparents. 
Kiana is a middle child with her sister as the eldest and her brother, the youngest. After 10 years of childhood in Bulacan, together with her elder sister and her younger brother, they moved to Sorsogon City to live with their father while her mother went abroad.
Moving to places was not a new thing for her. There she continued elementary in Del Rosario Elementary School and met her relatives from her father side. Then in Junior High in Rawis National High School, she took ICT, same with her sister, because her mother did not allow her to take cookery. When she turned grade 9, her science teacher said in the class that it's a year where lots of change happens to a student and she believed it. From being an average student to a leader. She surpassed her old self in terms of academics and started to be sociable. Attending english and science classes never fail to make her feel valued and appreciated.</p>
          <p>Feeling like she is just following her sisters' path, she did not pursue her passion for med. Though she's been bragging about taking Science, Technology, Engineering, and Mathematics for senior high school, and people knew she wanted to ba a doctor, she took up Humanities and Social Sciences in Senior High in Sorsogon National High School and BS Criminology in College in lieu of nursing, radiologic technologist, or any other premed courses.
Outside of academics, she enjoy playing game of the generals and learning chess. Writing stories became her hobby since she graduated in elementary. And when her childhood friend died, she wrote an unpublished story in her draft as a tribute with the title, The Downfall of Burgos. It was about the first son of Burgos family who was forced to grow up too fast and faces abuse and domestic violence from people who should be the one encouraging and loving him. </p>
          <p>Kiana is a social realist. She wrote stories dealing with psychological issues, about students at risk of dropping out of school, and why it is always the bullied but never the bully. Her theme is dark and was teased for being emo because of the color that represents her but it was for her branding.
Currently, Kiana is focusing on her studies and has no intention of having any romantic relationship with anyone. She thinks it would only hinder her plans knowing she gets distracted easily. She's contented writing happy but mostly heavy angst scenarios in her novels. She's contented having a small circle of friends. Studying while pursuing her writing Hopelessly waiting for the biggest plot twist after college.

The Article page must consist of this:</p>
        `;
      } else if (page === "article") {
        content.innerHTML = `
          <h2>ARTICLE</h2>
          <video controls>
            <source src="https://www.youtube.com/embed/PzZsButRaHs" type="video/mp4">
            Your browser does not support the video tag.
          </video>
          <p>Plagiarism is the act of taking someone else’s work, ideas, or intellectual property...</p>
          <p>Different countries treat plagiarism based on their legal and cultural views...</p>
        `;
      } else if (page === "blog") {
        content.innerHTML = `
          <h2>BLOG</h2>
          <video controls>
            <source src="https://www.youtube.com/embed/NMYbkzjI5EY" type="video/mp4">
            Your browser does not support the video tag.
          </video>
          <p>In today's digital age, navigating cybersecurity threats like viruses, malware, and spam...</p>
          <p>Antivirus software is designed to detect, quarantine, and remove viruses and other malware...</p>
        `;
      } else if (page === "form") {
        content.innerHTML = `
          <h2>FORM</h2>
          <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br><br>
            
            <label>Gender:</label>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br><br>
            
            <label>Favorite Genres:</label><br>
            <input type="checkbox" id="fiction" name="genre" value="Fiction">
            <label for="fiction">Fiction</label><br>
            <input type="checkbox" id="nonfiction" name="genre" value="Non-Fiction">
            <label for="nonfiction">Non-Fiction</label><br><br>
            
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required><br><br>
            
            <label for="book">Favorite Book:</label>
            <select id="book" name="book">
              <option value="none" selected disabled>Select a book</option>
              <option value="1984">1984</option>
              <option value="to_kill_a_mockingbird">To Kill a Mockingbird</option>
            </select><br><br>
            
            <button type="submit">Submit</button>
          </form>
        `;
      }
    }
  </script>
</body>
</html>
