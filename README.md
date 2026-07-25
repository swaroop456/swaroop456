# Hi 👋, I'm Swaroop Kumar Vathada

Top Priority 📊 Data Analyst → Data Scientist | 🤖 AI/ML Enthusiast | 🎯 Next Preferred Role: Power BI Developer

📍 Visakhapatnam, India  
📧 swaroop.vathada@gmail.com
---

## 🚀 About Me

- 💼 Data Analyst with **17 months of experience at TCS**
- 📊 Specialized in **SAP Analytics Cloud & Business Intelligence**
- 🐍 Strong in **Python, SQL, Power BI, Tableau & Excel**
- 🔍 Passionate about **data-driven decision making**
- 📈 Experienced in **EDA, Data Cleaning, Visualization & Dashboarding**
- 🤖 Exploring **Machine Learning & Generative AI** — clustering, RAG pipelines, and agentic workflows**
- 🔬 Built real-world **ML projects** including customer segmentation and AI-powered document Q&A systems**
- 📚 Continuously upskilling from **Data Analytics into Data Science** through hands-on projects**
- 🎯 Goal: To evolve from Data Analyst to Data Scientist — combining BI expertise with Machine Learning & AI to solve real-world problems

---

## 🛠️ Technical Skills

### 💻 Programming & Query Languages
![Python](https://img.shields.io/badge/Python-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-orange?logo=mysql)

### 📊 Data Analytics & Visualization
![Power BI](https://img.shields.io/badge/Power%20BI-yellow?logo=powerbi)
![Tableau](https://img.shields.io/badge/Tableau-blue?logo=tableau)
![Excel](https://img.shields.io/badge/Excel-green?logo=microsoft-excel)

### 🧠 Python Libraries
![Pandas](https://img.shields.io/badge/Pandas-purple)
![NumPy](https://img.shields.io/badge/NumPy-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-orange)

### 🧬 Data Science & AI

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-orange?logo=scikitlearn)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-orange?logo=scikitlearn)
![FAISS](https://img.shields.io/badge/FAISS-blue?logo=meta)
![Hugging Face](https://img.shields.io/badge/HuggingFace-yellow?logo=huggingface)
![Groq](https://img.shields.io/badge/Groq%20API-black?logo=groq)
![LangChain](https://img.shields.io/badge/LangChain-green?logo=langchain)

### 🧪 Data Science Concepts
- K-Means Clustering & Customer Segmentation
- Retrieval-Augmented Generation (RAG)
- Embeddings & Vector Databases
- Exploratory Data Analysis (EDA) for ML
- Agentic AI & Autonomous Workflows

### ⚙️ Tools & Technologies
- MySQL, MySQL Workbench  
- SAP Analytics Cloud  
- Power Query, DAX  
- Git & GitHub
- - Scikit-learn (Machine Learning models — clustering, regression, classification)
- FAISS (Vector similarity search / vector database)
- Hugging Face (Pretrained embeddings & transformer models)
- Groq API (Fast LLM inference — Llama models)
- Google Colab & Jupyter Notebook (already in your list, but worth highlighting here too)
- Seaborn / Matplotlib (Statistical data visualization)

---

## 💼 Professional Experience

### 🏢 Tata Consultancy Services (TCS)
**Assistant System Engineer**  
📅 May 2024 – Oct 2025  

- Developed **5+ dashboards** using SAP Analytics Cloud  
- Built **data models & KPI reports** for enterprise analytics  
- Worked on **Ledvance Digital Future (LDF) Project**  
- Ensured **data accuracy, integrity & real-time reporting**  
- Collaborated with cross-functional teams for analytics solutions  

---

## 📊 Projects

### employee-attrition-analytics 
- Built an end-to-end ML pipeline on 20,000 employee records to predict attrition, achieving [X]% F1-score and [X] ROC-AUC using Random Forest, Decision Tree, and Logistic Regression
- Identified the top 5 drivers of attrition (e.g. overtime, income, tenure) through feature importance analysis, cutting through 29 raw features to the ones that actually matter
- Segmented the workforce into [X] clusters using K-Means, uncovering a high-risk group with a [X]% attrition rate — [X]x higher than the company average of [X]%

🔗 https://github.com/swaroop456/employee-attrition-analytics  


### customer-purchase-prediction-ann
- Built a binary classification ANN (TensorFlow/Keras) predicting e-commerce purchase intent from session behavior data, achieving 95% test accuracy, 100% precision, and 87.5% recall
- Engineered a preprocessing pipeline handling missing values, categorical encoding, and feature scaling on an 8-feature dataset with a 60/40 class split
- Compared SGD vs Adam optimizers on identical architecture, with Adam converging in 96 epochs vs SGD's 100, using early stopping to prevent overfitting
- Designed a 3-layer neural network (16→8→1 neurons) with ReLU/sigmoid activations, achieving an F1-score of 0.933 on unseen test data

🔗 https://github.com/swaroop456/customer-purchase-prediction-ann


### fashion-mnist-cnn-classifier 
- Built a CNN (TensorFlow/Keras) that classifies clothing images into 10 categories, achieving 90.85% test accuracy on the Fashion-MNIST dataset (70,000 images)
- Reduced overfitting through Dropout (0.5) and real-time data augmentation, keeping the train-validation accuracy gap under 1% across 28 training epochs
- Designed a 3-block convolutional architecture (241K parameters) with early stopping, cutting unnecessary training time by ~7% (28 of 30 max epochs)
- Diagnosed model weaknesses via confusion matrix analysis, identifying a 15%+ accuracy gap on visually similar classes (Shirt vs. T-shirt/Pullover/Coat)

🔗 https://github.com/swaroop456/fashion-mnist-cnn-classifier


### nlp-sentiment-tfidf-vs-embeddings
- Built an end-to-end NLP sentiment classification pipeline on 100 movie reviews, engineering a full text-preprocessing workflow (HTML stripping, lemmatization, negation-aware stop-word removal) that fed two competing model architectures.
- Implemented and benchmarked TF-IDF + Logistic Regression against a Keras word-embedding neural network, achieving 100% accuracy, precision, recall, and F1-score with the TF-IDF approach on the held-out test set.
- Diagnosed and explained a 30-point accuracy gap (100% vs. 70%) between the two models by tracing it to training-data volume, demonstrating applied understanding of when classical ML outperforms deep learning on small datasets.

🔗 https://github.com/swaroop456/nlp-sentiment-tfidf-vs-embeddings


### research-agent-ai 
- Built an autonomous research agent in Python that processes a batch of 5+ topics end-to-end (search → summarize → save), generating structured Markdown reports with zero manual intervention per topic
- Designed a modular 3-tool pipeline (search, summarize, save) orchestrated by a single agent function, with a pluggable LLM layer supporting both offline extractive summarization and OpenAI-based abstractive summarization
- Implemented 3 layers of guardrails — input sanitization, keyword-based content filtering, and automatic retry logic (up to 2 retries per step) — to handle malformed input, unsafe topics, and transient failures without crashing

🔗 https://github.com/swaroop456/research-agent-ai


### 🛒 Customer Segmentation Using K-Means Clustering & RFM Analysis
- Analyzed **541,909 transaction records** from a UK-based Online Retail Store 
  (Dec 2010 – Dec 2011) using Python
- Engineered **RFM features** (Recency, Frequency, Monetary) from raw 
  transaction data, aggregating 4,338 unique customers
- Removed outliers using the **IQR method**, reducing dataset to 3,710 
  clean customer records before clustering
- Determined optimal **K=3 clusters** using Elbow Method and validated 
  with Silhouette Score of **0.4600**

🔗 https://github.com/swaroop456/Customer-Segmentation-ML-Project

### 🔹 Amazon Orders Data Analytics Project — Key Insights
- Analyzed 1,13,698 Amazon order records spanning across India using Python, Excel, MySQL, and Power BI.
- Built a 5-page interactive Power BI dashboard to track KPIs, revenue trends, customer behavior, and fulfillment performance.
- Identified INR 75M+ total revenue with an average order value of INR 663.
- Discovered that Kurta & Set categories contributed 77% of total orders, making them the highest-performing product categories.
- Found that promotional campaigns generated 2.5x higher revenue compared to non-promoted orders.
- Revealed that Expedited Shipping contributed nearly 75% of total revenue, showing strong customer preference for faster delivery.

🔗 https://github.com/swaroop456/Amazon-Orders-Data-Analytics-Project


### 🔹 Cafeteria Sales Data Analysis (Python)
- Cleaned & analyzed **10,000+ rows** using Pandas  
- Performed **EDA & correlation analysis**  
- Built visualizations using Matplotlib  

🔗 https://github.com/swaroop456/python-pandas-mini-project  

---

### 🔹 Classic Models Database Analysis (MYSQL)
- Wrote **complex SQL queries (JOIN, GROUP BY, Aggregations)**  
- Performed structured database analysis  

🔗 https://github.com/swaroop456/MYSQL-Classic-models-DB-Analysis  

---

### 🔹 Retail Sales Analysis (Advanced Excel)
- Worked on **12,000+ rows dataset**  
- Used **17+ advanced Excel formulas**  
- Built **interactive dashboards & pivot reports**  

🔗 https://github.com/swaroop456/Advanced-Excel-Retail-Sales-Analysis  

---

### 🔹 HR Analytics Dashboard (Power BI)
- Created **4-page interactive dashboard**  
- Developed **7 DAX measures**  
- Identified key insights like **16% attrition rate**  

🔗 https://github.com/swaroop456/Power-BI-HR-Analytics-Mini-Project  

---

### 🔹 Store Sales Dashboard (Tableau)
- Analyzed **31,000+ records**  
- Built **interactive Tableau dashboard & story**  
- Derived insights on **sales trends & customer behavior**  

🔗 https://github.com/swaroop456/Tableau-Store-sales-dashboard  

---

### Financial Sales Dashboard (Power BI)
- Built 4-page interactive Power BI dashboard on Microsoft Financial Sample dataset
- Developed 6 DAX measures including Total Sales, Total Profit, Profit Margin %
- Created calculated column for row-level Profit Margin analysis
- Analyzed 700 rows across 5 countries, 6 products & 5 segments

🔗 https://github.com/swaroop456/Power-BI-Financial-Sales-Dashboard

---

## 🎓 Education

🎓 B.Tech – Mechanical Engineering  
Avanthi Institute of Engineering and Technology  
📊 CGPA: 7.18  

---

## 📜 Certifications

- 📘 SAP Analytics Cloud – Record of Achievement (SAP) [Credly](https://www.credly.com/badges/28b70f9c-22ce-4f3a-99a7-57d09312ef1b)

---

## 🌐 Connect with Me

- 🔗 LinkedIn: https://linkedin.com/in/swaroopkumarvathada  
- 💻 GitHub: https://github.com/swaroop456  
- 📧 Email: swaroop.vathada@gmail.com  

---

## ⚡ Fun Fact

🔍 Fun fact: I get genuinely excited when messy data turns into a clean dashboard — and lately I've been just as excited teaching machines to spot the patterns themselves (RAG pipelines, clustering models, you name it) 🤖📊 📊🚀
