---
layout: default
title: Projects
permalink: /projects/
---

# Projects

Explore some of the impactful academic, professional, and research projects I've worked on:

<div class="project-card">
  <details open>
    <summary><strong>📊 Hybrid Recommender System for Yelp Reviews</strong></summary>

    <img src="{{ '/assets/img/solution_flow_diagram.png' | relative_url }}" alt="Hybrid Recommender System Diagram"
      style="max-width: 100%; height: auto; margin: 1rem 0; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); display: block;">

    <p>
      Built a hybrid recommendation engine using <strong>PySpark</strong> and <strong>XGBoost</strong> to predict user ratings on Yelp businesses. Combined collaborative filtering with a model-based approach, leveraging data from user profiles, reviews, tips, and photos.
    </p>

    <ul>
      <li>⚙️ Developed a Spark pipeline to integrate multi-source data (CSV, JSON: reviews, tips, photos).</li>
      <li>🔁 Implemented item-item collaborative filtering with cosine similarity & bias correction.</li>
      <li>🎯 Trained an XGBoost regression model on review sentiment, tip engagement, and user activity.</li>
      <li>🧪 Blended CF and model predictions (5% CF, 95% model) to optimize RMSE.</li>
    </ul>

    <p><strong>📈 Results:</strong> RMSE reduced, validated using error distribution analysis.</p>
    <p><strong>🧰 Tech Stack:</strong> PySpark, Python, XGBoost, NumPy, JSON, CSV</p>
    <p><strong>🏷️ Keywords:</strong> Recommender Systems, Hybrid Model, Collaborative Filtering, Machine Learning, Spark</p>
    <p><strong>🔗 GitHub:</strong> <a href="https://github.com/aditi-joshi-usc/Hybrid-Recommendation-System-Using-Spark-RDD-XGBoost" target="_blank">View the project on GitHub</a></p>
  </details>
</div>


<div class="project-card">
  <details>
    <summary><strong>🛡️ Privacy-Preserving Smart Health App – IBM DiffPrivLib</strong></summary>

    <p>
      Developed a smart healthcare monitoring system using <strong>IBM’s open-source Differential Privacy library (Diffprivlib)</strong> to protect patient data during machine learning model training. The app gives personalized health recommendations and predicts re-hospitalization risks using private EHR data.
    </p>

    <ul>
      <li>🔐 Integrated <strong>diffprivlib</strong> with ML models to enforce privacy using noise mechanisms and budget accounting.</li>
      <li>📊 Used statistical tools (mean, histograms) to analyze data without exposing raw values.</li>
      <li>🏥 Simulated Electronic Health Record (EHR) processing to make predictions while preserving user confidentiality.</li>
      <li>☁️ Proposed secure cloud architecture for hospital-user interaction.</li>
    </ul>

    <p><strong>📈 Use Case:</strong> Privacy-preserving personalized health insights + hospitalization risk alerts.</p>
    <p><strong>🧰 Tech Stack:</strong> Python, IBM DiffPrivLib, Scikit-learn, MongoDB, Flask (proposed)</p>
    <p><strong>🏷️ Keywords:</strong> Differential Privacy, Smart Healthcare, EHR, Privacy-Preserving ML</p>
    <p><strong>🔗 GitHub:</strong> <a href="https://github.com/aditi-joshi-usc/Differential-Privacy-Portal-IBM" target="_blank">View on GitHub</a></p>

    <p><strong>🎥 Presentation:</strong></p>
    <iframe src="https://drive.google.com/file/d/1VzWWX0ppZhvN26Pyp-KmkMbMKgBwUDc5/preview" width="100%" height="400" allow="autoplay"></iframe>
  </details>
</div>


<div class="project-card">
  <details>
    <summary><strong>🗃️ Custom File-Based Relational & NoSQL Database Systems</strong></summary>

    <p>
      Designed and implemented two lightweight database engines using Python — a <strong>Relational Database System</strong> for structured CSV data and a <strong>NoSQL Document Store</strong> for semi-structured JSON data. Both systems use custom-built query languages and simulate modern DBMS functionality using file system operations without external libraries or engines.
    </p>

    <h4>📌 Relational DB Engine</h4>
    <ul>
      <li>📁 Built a structured file-based architecture using folders to represent databases and CSVs for tables (e.g., companies, industries, employee counts).</li>
      <li>⚙️ Implemented support for schema enforcement, table joins, and indexing using Python dictionaries.</li>
      <li>💬 Developed a custom SQL-like query parser to handle operations like GET, PUT, UPD, RMV.</li>
      <li>🔗 Supported many-to-many and one-to-one relationships among entities (companies ↔ industries, employee counts).</li>
    </ul>

    <h4>📌 NoSQL Document Store</h4>
    <ul>
      <li>📂 Created a document-oriented engine where JSON files represent documents and collections are folders.</li>
      <li>📜 Supported schema-less flexible documents with varying structure across collections like <em>laureates</em> and <em>awards</em>.</li>
      <li>🔍 Implemented filtering, projection, and indexing on document fields via custom-built search engine.</li>
      <li>🧠 Used real-world datasets (e.g., Nobel Prize) to simulate NoSQL queries and aggregations.</li>
    </ul>

    <p><strong>🧰 Tech Stack:</strong> Python, CSV, JSON, File I/O, Custom Query Parser</p>
    <p><strong>🏷️ Keywords:</strong> NoSQL, RDBMS, Custom DBMS, Python, Query Language, Data Modeling, Indexing</p>
    <p><strong>🔗 GitHub:</strong> <a href="https://github.com/aditi-joshi-usc/NOSQL-File-System-DB" target="_blank">View NoSQL DB Repo</a></p>
  </details>
</div>


<div class="project-card">
  <details>
    <summary><strong>🔍 Boston Crime Rate Prediction</strong></summary>
    <p>Led a team to build a predictive model for Boston crime trends using regression and random forest algorithms, achieving 80% model accuracy.</p>
    <p><strong>Technologies:</strong> Python, Pandas, Scikit-learn, Matplotlib</p>
  </details>
</div>
