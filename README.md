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
        <source src="videoplayback (12).webm" type="audio/mp3">
        Your browser does not support the audio element.
      </audio>
      <img src="Brown Aesthetic Vintage Scrapbook Background Instagram Story_20241217_110506_0000.png" alt="Welcome Message">" alt="Kiana Infante Bitara">
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
<iframe width="560" height="315" 
        src="https://www.youtube.com/embed/hDnN9TeN65E" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>

          <p>Plagiarism is the act of taking someone else’s work, ideas, or intellectual property without proper acknowledgment. It is a serious offense across various domains, including academia, art, music, literature, and journalism. The consequences of plagiarism vary depending on the severity of the infringement and the country’s legal framework governing intellectual property rights. In academia, plagiarism can lead to severe academic sanctions, including revocation of degrees, expulsion from institutions, or professional discredit. Notably, Karl-Theodor zu Guttenberg, the German defense minister, had his doctoral degree revoked and was forced to resign after it was revealed he plagiarized large parts of his thesis. Similarly, in the U.S., Senator John Walsh faced public backlash and the revocation of his master's degree after his thesis was found to contain extensive plagiarism (Klein, 2014). These cases underscore how plagiarism can have long-lasting consequences on individuals’ careers and reputations./p>
          <table border="1" style="width: 100%; border-collapse: collapse; color: black;">
  <tr>
    <th style="text-align: left; padding: 10px;">Context</th>
    <th style="text-align: left; padding: 10px;">Details</th>
  </tr>
  <tr>
    <td style="padding: 10px;">Music Plagiarism</td>
    <td style="padding: 10px;">
      In the realm of music, plagiarism often involves copyright infringement, with artists sometimes being required to pay royalties or settle out of court. 
      For example, Radiohead’s song <em>Creep</em> was found to be similar to a song by Albert Hammond and Mike Hazlewood, leading to a settlement where 
      Radiohead credited the original composers and shared royalties.
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">Academic Plagiarism</td>
    <td style="padding: 10px;">
      In China, cheating in exams, which can be considered academic plagiarism, leads to annulled scores and criminal charges for fraud. For instance, 
      in 2013, students caught using smartphones to cheat in national exams faced severe penalties, including criminal charges and the invalidation 
      of their results (Chinese Ministry of Education, 2013).
    </td>
  </tr>
</table>

          <p>Different countries treat plagiarism based on their legal and cultural views on intellectual property, but it is universally seen as a breach of ethical and legal norms. Whether through legal action, academic sanctions, or professional consequences, plagiarism remains a violation that can have serious and far-reaching implications.</p>
        `;
      } else if (page === "blog") {
        content.innerHTML = `
          <h2>BLOG</h2>
          <iframe width="560" height="315" 
        src="https://www.youtube.com/embed/NMYbkzjI5EY" 
        title="YouTube video player" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>

          <p>In today's digital age, navigating cybersecurity threats like viruses, malware, and spam is crucial for individuals and businesses alike. These malicious programs and activities not only disrupt systems but also pose significant risks to privacy and security. Here’s an overview of these threats and the role of antivirus software in combating them.
</p>
<table border="1" style="width: 100%; border-collapse: collapse; color: black;">
  <tr>
    <th style="text-align: left; padding: 10px;">Topic</th>
    <th style="text-align: left; padding: 10px;">Details</th>
  </tr>
  <tr>
    <td style="padding: 10px;">1. Viruses and Malware</td>
    <td style="padding: 10px;">
      Viruses are malicious programs designed to replicate and spread by attaching themselves to legitimate files or programs. They can corrupt data, crash systems, and even steal sensitive information.<br><br>
      Malware (malicious software) encompasses a broader category, including spyware, ransomware, and trojans. These programs are used by cybercriminals to:
      <ul>
        <li>Steal personal and financial information.</li>
        <li>Monitor user activity.</li>
        <li>Demand ransoms (ransomware) or install other harmful software.</li>
      </ul>
      To protect against these threats, it's essential to use up-to-date security software and exercise caution when downloading files or clicking on unfamiliar links.
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">2. Spam and Email Threats</td>
    <td style="padding: 10px;">
      Spam involves unsolicited emails, often sent in bulk, that can contain misleading advertisements, phishing attempts, or links to malware. Laws like the CAN-SPAM Act in the United States regulate email marketing practices, ensuring that consumers can opt out of such communications and protecting them from deceptive content.<br><br>
      Phishing emails, a form of spam, aim to trick recipients into divulging sensitive information, such as login credentials or credit card numbers. Recognizing suspicious emails and avoiding unverified links are critical for maintaining cybersecurity.
    </td>
  </tr>
  <tr>
    <td style="padding: 10px;">3. Role of Antiviruses</td>
    <td style="padding: 10px;">
      Antivirus software is designed to detect, quarantine, and remove viruses and other malware. Modern antivirus programs also include features like:
      <ul>
        <li>Real-time scanning of files and websites.</li>
        <li>Firewalls to block unauthorized access.</li>
        <li>Anti-spam tools to filter harmful emails.</li>
      </ul>
    </td>
  </tr>
</table>

          <p>Choosing reputable antivirus solutions and keeping them updated ensures robust protection against emerging threats.</p>
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
