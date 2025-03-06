# 🎬 Netflix Data Sentimental Analysis  

This project performs **sentiment analysis** on Netflix user reviews to determine whether users have **Positive, Negative, or Neutral** opinions. The analysis uses **machine learning (Naive Bayes) approaches** to classify reviews.  

---

## 📂 Dataset  
Download the dataset here - ([https://github.com/tanushreer-7/Netflix-Data-Sentimental-Analysis/blob/main/dataset.zip]) and unzip to read the file

The dataset contains Netflix user reviews with the following columns:  
- `reviewId` – Unique ID of the review  
- `userName` – Name of the reviewer  
- `content` – The actual text of the review  
- `score` – Rating given (1 to 5)  
- `thumbsUpCount` – Number of likes on the review  
- `at` – Timestamp of the review  

---

## 📌 Steps in the Analysis  

✔ STEP-1: IMPORTING NECESSARY PACKAGES 
✔ STEP-2: READING THE NETFLIX DATASET  
✔ STEP-3: PRE-PROCESSING NETFLIX DATASET  
✔ SETP-4: ANALYSING THE DATASET
✔ STEP-5: EXPLORATORY DATASET ANALYSIS OF NETFLIX DATASET
✔ STEP-6: ADD A NEW COLUMN 'sentiment' TO THE EXISTING DATASET
✔ STEP-7(A): ANALYSE THE 'sentiment' COLUMN USING BAR GRAPH 
✔ STEP-7(B): ANALYSE THE 'sentiment' COLUMN USING SCATTER PLOT
✔ STEP-8: TRAIN AND TEST THE MODEL(USING NAIVE BAYES)
✔ STEP-9: CALCULATE THE ACCURACY OF THE MODEL
✔ STEP-10:DISPLAY THE CONFUSION MATRIX

---

## 🚀 How to Run  

### **1️⃣ Run in Google Colab**  
Click the link below to open the **Colab Notebook** and run it directly:  
[🔗 Open Colab Notebook] ([https://colab.research.google.com/github/tanushreer-7/Netflix-Data-Sentimental-Analysis/blob/main/Sentimental_Analysis.ipynb])

**2️⃣ Run the notebook**
Open Netflix_Sentiment_Analysis.ipynb in Jupyter or Colab and run the cells step by step.

### **🔹 Run Locally**  
#### 1️⃣ Clone the repository  
```sh
git clone https://github.com/your-username/netflix-sentiment-analysis.git
cd netflix-sentiment-analysis
