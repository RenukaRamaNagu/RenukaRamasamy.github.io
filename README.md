
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Renuka Ramasamy</title>
  <style>
    /* Basic styling */
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }

    /* Flexbox container for the image and contact details */
    .container {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px; /* Space between the image and info */
    }

    /* Image styling */
    .profile-img {
      width: 150px;
      height: auto;
      border-radius: 8px;
    }

    /* Right-side content */
    .info {
      flex-grow: 1;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    /* Name and email alignment */
    .info h1 {
      margin: 0;
      font-size: 1.8em;
    }

    .info p {
      margin: 5px 0;
    }

    /* Self-introduction */
    .info .introduction {
      margin-top: 10px;
      font-size: 1em;
      line-height: 1.6;
    }

    /* Link styles */
    .sections a {
      color: blue;
      text-decoration: none;
      font-size: 1.1em;
    }

    .sections a:hover {
      text-decoration: underline;
    }

    /* Additional CSS to reduce the gap between headings and content */
    section {
      margin: 10px 0; /* Reduce the margin around each section */
    }

    h2 {
      margin-bottom: 5px; /* Reduce the bottom margin of the headings */
    }

    /* Responsive design for smaller screens */
    @media screen and (max-width: 768px) {
      .container {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }

      .profile-img {
        margin-bottom: 20px;
      }

      .info {
        align-items: center;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Name, email, and self-introduction on the left -->
    <div class="info">
      <h1>Renuka Ramasamy</h1>
      <p><strong>Email:</strong> <a href="mailto:renukabecs7@gmail.com">renukabecs7@gmail.com</a></p>
      <p class="introduction">
        As an aspiring AI Master's student, I have a deep passion for Artificial Intelligence, Machine Learning, Natural Language Processing, and Computer Vision. I enjoy exploring these fields and applying my knowledge to solve complex problems and create innovative solutions.
      </p>
    </div>

    <!-- Image on the right -->
    <img src="image.jpeg" alt="Renuka Ramasamy" class="profile-img">
  </div>

  <hr>

  <!-- Links to sections -->
  <section class="sections">
    <h2>Quick Links</h2>
    <ul>
      <li><a href="CV.pdf">CV</a></li>
      <li><a href="https://github.com/RenukaRamaNagu" target="_blank">GitHub</a></li>
      <li><a href="#research">Research</a></li>
      <li><a href="#internships">Internships</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#certifications">Certifications</a></li>
    </ul>
  </section>

  <hr>

  <!-- Research Section -->
  <section id="research">
    <h2>Research</h2>
    <ul>
      <li>
        <strong>The Multiple Approaches for Drug-Drug Interaction Extraction using Machine Learning and Transformer-based Model</strong> (2024)<br>
        Gurpreet Singh, Dr. Kim Yong II, Renuka Ramasamy, Sundareswari Thiyagarajan<br>
        <em>Journal on Artificial Intelligence 2024</em> (Under Review). <a href="The Multiple Approaches for Drug-Drug Interaction Extraction using Machine learning and transformer-based Model.pdf">[pdf]</a>
      </li>
      <li>
        <strong>A Multi-Model Approach: Stress Detection using Physiological Signals with LSTM and XGBoost</strong> (2024)<br>
        Dr. Saurabh Singh, Gurpreet Singh, Renuka Ramasamy, Sundareswari Thiyagarajan<br>
        <em>IEEE Access 2024</em> (Under Review). <a href="A Multi-Model Approach- Stress Detection using Physiological Signals with LSTM and XGBoost.pdf">[pdf]</a>
      </li>
    </ul>
  </section>

  <hr>

  <!-- Internships Section -->
  <section id="internships">
    <h2>Internships</h2>
    <ul>
      <li>
        <a href="https://gurpreetsinghwsu.github.io/cv/projects.html"><strong>AI to Detect Criminal Vehicle using License Plate Number</strong> (2024)</a><br>
        Worked on developing an AI model to identify criminal vehicles using license plate recognition. The project involved computer vision and deep learning techniques.
      </li>
    </ul>
  </section>

  <hr>

  <!-- Projects Section -->
  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>
        <strong>Crop and Fertilizer Recommendation System</strong> (Feb - May 2023)<br>
        An end-to-end user-friendly model developed to help farmers identify which crop can give a better yield based on features like N, P, and K values, fertilizer content present in the soil, soil type, pH value, and rainfall in that region, state, and city. Also recommending the best fertilizer for each particular crop. Additionally includes plant leaf disease prediction with suggestions to cure diseases.
      </li>
      <li>
        <strong>Facial Emotion Detection using Deep Learning</strong> (Aug - Nov 2022)<br>
        Developed a handheld portable device for viable embryo detection, funded by CSRC under the Research Support Scheme "Student Innovative Project".
      </li>
      <li>
        <strong>A Novel Method for Handwritten Digit Recognition System</strong> (Aug - Nov 2022)<br>
        This model is developed for recognition of postal code or zip code that can be employed in mail sorting. CNNs were used to recognize and classify the handwritten digits from images.
      </li>
      <li>
        <strong>Online Voting System</strong> (Aug - Dec 2021)<br>
        Designed a user-friendly interface for an online voting system using Eclipse. Data entered is stored in a MySQL database, connected via PHP.
      </li>
    </ul>
  </section>

  <hr>

  <!-- Certifications & Awards Section -->
  <section id="certifications">
    <h2>Certifications & Awards</h2>
    <ul>
      <li>Online Machine Learning course in Simplilearn (11 Feb 2024).</li>
      <li>IBM “A Novel Based on Hand Digit Recognition System” (28 Feb 2023).</li>
      <li>Workshop “Hands-on Training using Android Application Development” (Feb 2020).</li>
      <li>Internship Certificate for AI to Detect Criminal Vehicle using License Plate Number (2024).</li>
    </ul>
  </section>

</body>
</html>
