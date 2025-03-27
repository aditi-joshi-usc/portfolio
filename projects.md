---
layout: default
title: Projects
permalink: /projects/
---

# Projects

Explore some of the impactful academic, professional, and research projects I've worked on:

<div class="project-card">
  <details>
    <summary><strong>📊 Hybrid Recommender System for Yelp Reviews</strong></summary>

    <img src="{{ '/assets/img/solution_flow_diagram.png' | relative_url }}" alt="Hybrid Recommender System Diagram"
      style="max-width: 80%; height: auto; margin: 1rem auto; display: block; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">

    <p>
      Developed a scalable hybrid recommendation engine using <strong>PySpark</strong> and <strong>XGBoost</strong> to predict user ratings on Yelp businesses.
      Combined item-based collaborative filtering with a model-based approach leveraging user, business, review, tip, and photo metadata.
    </p>

    <ul>
      <li>Engineered a Spark pipeline to preprocess and integrate multi-source data (CSV, JSON: reviews, tips, photos, profiles).</li>
      <li>Implemented item-item collaborative filtering with cosine similarity and bias correction.</li>
      <li>Trained an XGBoost model using features from review sentiment, user activity, tip engagement, and photo content.</li>
      <li>Blended predictions (95% model-based, 5% CF) to reduce RMSE and boost accuracy.</li>
    </ul>

    <p><span style="font-weight:600;">📈 Results:</span> Achieved strong RMSE performance, validated via error distribution analysis.</p>
    <p><span style="font-weight:600;">🧰 Tech Stack:</span> PySpark, Python, XGBoost, NumPy, JSON, CSV</p>
    <p><span style="font-weight:600;">🏷️ Keywords:</span> Recommender Systems, Hybrid Model, Collaborative Filtering, Machine Learning, Spark</p>
    <p><span style="font-weight:600;">🔗 GitHub:</span> <a href="https://github.com/aditi-joshi-usc/Hybrid-Recommendation-System-Using-Spark-RDD-XGBoost" target="_blank">github.com/aditi-joshi-usc/yelp-recommender-system</a></p>
  </details>
</div>


<div class="project-card">
  <details>
    <summary><strong>🧠 Differential Privacy on Genomic Data</strong></summary>
    <p>Created a Django-based portal demonstrating privacy-utility tradeoffs using ML on genomic datasets. Implemented differential privacy techniques and presented results at international competitions.</p>
    <p><strong>Technologies:</strong> Python, Django, MongoDB, Differential Privacy</p>
  </details>
</div>

<div class="project-card">
  <details>
    <summary><strong>📂 Custom File-Based Relational & NoSQL DB</strong></summary>
    <p>Designed and built a Python-based database system supporting both relational and NoSQL structures, improving retrieval and storage efficiency by over 30%.</p>
    <p><strong>Technologies:</strong> Python, File I/O, OOP</p>
  </details>
</div>

<div class="project-card">
  <details>
    <summary><strong>🔍 Boston Crime Rate Prediction</strong></summary>
    <p>Led a team to build a predictive model for Boston crime trends using regression and random forest algorithms, achieving 80% model accuracy.</p>
    <p><strong>Technologies:</strong> Python, Pandas, Scikit-learn, Matplotlib</p>
  </details>
</div>
