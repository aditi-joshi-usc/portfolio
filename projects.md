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
    <summary><strong>🔍 Boston Crime Rate Prediction</strong></summary>
    <p>Led a team to build a predictive model for Boston crime trends using regression and random forest algorithms, achieving 80% model accuracy.</p>
    <p><strong>Technologies:</strong> Python, Pandas, Scikit-learn, Matplotlib</p>
  </details>
</div>
