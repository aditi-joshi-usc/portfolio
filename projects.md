---
layout: default
title: Projects
permalink: /projects/
---

# Projects

Explore some of the impactful academic, professional, and research projects I've worked on:

<div class="project-card">
  <details>
    <summary><strong>🌐 MCP Weather Server – Claude & Cursor Integration</strong></summary>

    <p>
      Developed my first <strong>Model Context Protocol (MCP)</strong> server using <strong>TypeScript</strong>, <strong>Node.js</strong>, and <strong>Zod</strong>. This project integrates with <strong>Claude Desktop</strong> and <strong>Cursor</strong> to provide real-time weather data through conversational tool invocation.
    </p>

    <ul>
      <li>🌦️ <strong>`get-alerts`</strong>: Returns current weather alerts by US state code using the National Weather Service API.</li>
      <li>📍 <strong>`get-forecast`</strong>: Fetches point-based forecast for latitude and longitude coordinates.</li>
      <li>🧪 Integrated with Claude & Cursor to run weather tools in natural language environments.</li>
      <li>🔒 Validated all inputs using <strong>Zod schemas</strong> and implemented full type safety with TypeScript.</li>
    </ul>

    <p><strong>🧰 Tech Stack:</strong> TypeScript, Node.js, Zod, @modelcontextprotocol/sdk, Claude Desktop, Cursor, NWS API</p>
    <p><strong>🏷️ Keywords:</strong> MCP, Tool Integration, Claude AI, Cursor IDE, Weather API, TypeScript, Zod</p>
    <p><strong>🔗 GitHub:</strong> <a href="https://github.com/aditi-joshi-usc/mcp-weather-server" target="_blank">View on GitHub</a></p>

    <p><strong>🖼️ Screenshots:</strong></p>
    
   <p><strong>🖼️ Screenshots:</strong></p>

<div style="text-align: center; margin-bottom: 1.5rem;">
  <img src="{{ '/assets/img/mcp-claude-demo.png' | relative_url }}"
       alt="Claude running MCP tool"
       style="width: 100%; max-width: 600px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
  <p style="margin-top: 0.5rem; font-size: 0.95rem; color: #555;">Claude Desktop fetching forecast and alerts via MCP</p>
</div>

<div style="text-align: center;">
  <img src="{{ '/assets/img/mcp-cursor-demo.png' | relative_url }}"
       alt="Cursor using MCP server"
       style="width: 100%; max-width: 350px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
  <p style="margin-top: 0.5rem; font-size: 0.95rem; color: #555;">Cursor IDE showing tool invocation and weather results</p>
</div>
  </details>
</div>

<div class="project-card">
  <details>
    <summary><strong>📊 Hybrid Recommender System for Yelp Reviews</strong></summary>

    <img src="{{ '/assets/img/solution_flow_diagram.png' | relative_url }}" 
     alt="Hybrid Recommender System Diagram"
     style="width: 100%; max-width: 600px; max-height: 400px; object-fit: contain; margin: 1rem auto; border-radius: 10px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); display: block;">


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

    <img src="{{ '/assets/img/custom-db-er-diagram.png' | relative_url }}" alt="ER Diagram of Relational and NoSQL DB" style="max-width: 100%; height: auto; margin: 1.5rem 0; border-radius: 10px; box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08); display: block;">

    <h4>📌 Relational DB Engine</h4>
    <ul>
      <li>📁 File-based structure: folders represent databases, CSV files represent tables.</li>
      <li>🧩 Implemented schema enforcement, joins, indexing using Python dictionaries.</li>
      <li>💬 Custom query language: GET, PUT, UPD, RMV operations parsed via Python.</li>
      <li>🔗 Supported many-to-many and one-to-one relationships (e.g., company ↔ industry).</li>
    </ul>

    <h4>📌 NoSQL Document Store</h4>
    <ul>
      <li>📂 Document-based engine: JSON files represent documents in collection folders.</li>
      <li>🌐 Schema-free support for varying document structures (laureates, awards).</li>
      <li>🔍 Built filtering and indexing features with custom index files per field.</li>
      <li>📊 Used real-world Nobel Prize dataset to simulate NoSQL use cases.</li>
    </ul>

    <p><strong>🧰 Tech Stack:</strong> Python, CSV, JSON, File I/O, Query Parser</p>
    <p><strong>🏷️ Keywords:</strong> NoSQL, RDBMS, Custom DBMS, Query Language, Data Modeling</p>
    <p><strong>🔗 GitHub:</strong> <a href="https://github.com/aditi-joshi-usc/NOSQL-File-System-DB" target="_blank">View on GitHub</a></p>
  </details>
</div>


<div class="project-card">
  <details>
    <summary><strong>🚨 Predictive Analysis of Boston Crime Rates</strong></summary>

    <p>
      Led a team project for USC's DSCI 550 course focused on analyzing and predicting crime patterns in Boston using 2015–2018 data. Combined geospatial, temporal, and statistical analysis with machine learning to uncover trends and forecast crime occurrences.
    </p>

    <ul>
      <li>📊 Identified the top 10 most common crimes and visualized their frequency via bar and pie charts.</li>
      <li>🗺️ Mapped crime density using heatmaps and scatter plots across districts, streets, and neighborhoods.</li>
      <li>🕒 Analyzed seasonal and temporal trends — discovered peak crime days (Fridays), months (August), and hours (late night).</li>
      <li>📈 Trained a linear regression model using incident metadata (district, offense group, timestamp) achieving ~66.6% R² score.</li>
      <li>🤝 Used insights to support public safety recommendations for community policing and policymaking.</li>
    </ul>

    <p><strong>📈 Result:</strong> Delivered predictive and visual insights to highlight high-risk areas and times, aiding law enforcement resource allocation.</p>
    <p><strong>👩‍💼 Role:</strong> Team Leader — built predictive model, led spatial analysis, authored final report.</p>
    <p><strong>🧰 Tech Stack:</strong> Python, Pandas, Seaborn, Matplotlib, Scikit-learn, Plotly, Folium, Jupyter</p>
    <p><strong>🏷️ Keywords:</strong> Crime Prediction, Geospatial Analysis, Regression, Time Series, Visualization, Urban Analytics</p>
    <p><strong>📄 Final Report:</strong> <a href="https://github.com/aditi-joshi-usc/boston-crime-predictive-analysis/blob/main/Team12-550FinalProjectReport.pdf" target="_blank">Team12-550FinalProjectReport.pdf</a></p>
    <p><strong>💻 Code Notebook:</strong> <a href="https://github.com/aditi-joshi-usc/boston-crime-predictive-analysis/blob/main/Team12-Project-Final-Code.ipynb" target="_blank">Team12-Project-Final-Code.ipynb</a></p>
  </details>
</div>
<div class="project-card">
  <details>
    <summary><strong>🧠 Predictive Modeling for Conduct Disorder & Autism Using MRI</strong></summary>

    <p>
      Ongoing research project at USC focused on early prediction of Conduct Disorder (CD) and Autism Spectrum Condition (ASC) using structural and functional MRI data from the ABCD and ABIDE datasets. The goal is to develop ML-based screening models to aid early diagnosis and intervention.
    </p>

    <ul>
      <li>🧹 Preprocessed raw MRI data using fMRIPrep and Nilearn to extract region-level activation signals and connectivity matrices.</li>
      <li>🧠 Extracted biomarkers like subcortical volumes, cortical thickness, and resting-state connectivity features.</li>
      <li>📊 Performed dimensionality reduction using PCA and autoencoders to improve signal-to-noise ratio and generalizability.</li>
      <li>🧪 Compared ML models: SVM, XGBoost, and neural networks for binary classification (CD vs. healthy controls).</li>
      <li>📁 Validated on ABIDE for autism screening generalizability.</li>
    </ul>

    <p><strong>🎓 Role:</strong> Research Assistant under Prof. Anita Penkova — leading preprocessing pipeline and algorithm comparison.</p>
    <p><strong>🧰 Tech Stack:</strong> Python, Nilearn, scikit-learn, fMRIPrep, XGBoost, TensorFlow, Nibabel</p>
    <p><strong>🏷️ Keywords:</strong> Neuroimaging, Conduct Disorder, Autism, fMRI, Brain Biomarkers, Classification, ML in Healthcare</p>

  </details>
</div>
