<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Movie Recommendation App</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #121212;
      color: #ffffff;
      margin: 0;
      padding: 0 20px;
      line-height: 1.6;
    }
    header {
      padding: 30px 0;
      text-align: center;
    }
    h1 {
      color: #ff4c60;
    }
    h2 {
      color: #ffaa33;
      margin-top: 30px;
    }
    code, pre {
      background-color: #1e1e1e;
      color: #00e6e6;
      padding: 10px;
      border-radius: 5px;
      display: block;
      overflow-x: auto;
    }
    .section {
      margin-bottom: 40px;
    }
    ul {
      list-style: square;
      padding-left: 20px;
    }
    a {
      color: #66ccff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .project-structure {
      background-color: #1e1e1e;
      padding: 10px;
      border-radius: 5px;
      font-family: monospace;
      color: #aaffaa;
    }
  </style>
</head>
<body>

  <header>
    <h1>🎬 Movie Recommendation App</h1>
    <p>Built with Streamlit and KNN</p>
  </header>

  <div class="section">
    <h2>🚀 Features</h2>
    <ul>
      <li>Search and select a movie from the list</li>
      <li>Get personalized movie recommendations using KNN</li>
      <li>Backend powered by preprocessed movie feature data</li>
      <li>Simple and fast machine learning model with no retraining needed</li>
      <li>Deployed using Streamlit</li>
    </ul>
  </div>

  <div class="section">
    <h2>🛠️ How It Works</h2>
    <p>
      A KNN model is trained on movie features. When you pick a movie, it finds the top N most similar titles using a distance metric like cosine similarity or Euclidean distance.
    </p>
  </div>

  <div class="section">
    <h2>📁 Project Structure</h2>
    <pre class="project-structure">
movie-recommender/
├── app.py                  # Streamlit app
├── model/
│   └── knn_model.pkl       # Trained KNN model
├── data/
│   └── movies.csv          # Movie metadata
├── requirements.txt        # Dependencies
└── README.html             # Project documentation
    </pre>
  </div>

  <div class="section">
    <h2>▶️ How to Run Locally</h2>
    <p><strong>Clone the repository:</strong></p>
    <pre>git clone https://github.com/yourusername/movie-recommender.git
cd movie-recommender</pre>

    <p><strong>Install dependencies:</strong></p>
    <pre>pip install -r requirements.txt</pre>

    <p><strong>Run the Streamlit app:</strong></p>
    <pre>streamlit run app.py</pre>
  </div>

  <div class="section">
    <h2>📦 Requirements</h2>
    <ul>
      <li>Python 3.7+</li>
      <li>pandas</li>
      <li>scikit-learn</li>
      <li>streamlit</li>
      <li>numpy</li>
    </ul>
  </div>

  <div class="section">
    <h2>🧠 Model Info</h2>
    <ul>
      <li><strong>Algorithm:</strong> K-Nearest Neighbors</li>
      <li><strong>Distance metric:</strong> Cosine similarity or Euclidean</li>
      <li><strong>Trained on:</strong> Features from movie metadata</li>
    </ul>
  </div>

  <div class="section">
    <h2>📌 Future Improvements</h2>
    <ul>
      <li>Genre/actor-based filtering</li>
      <li>User login and personalization</li>
      <li>Cloud deployment (e.g., Streamlit Cloud, Heroku)</li>
    </ul>
  </div>

  <div class="section">
    <h2>🙋‍♂️ Author</h2>
    <p><strong>Your Name</strong></p>
    <p>
      <a href="https://github.com/yourusername" target="_blank">GitHub</a> |
      <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
    </p>
  </div>

</body>
</html>
