# McDonald's Case Study: Market Segmentation Analysis 🟨🍔

This project analyzes customer perceptions of McDonald’s using market segmentation techniques like k-means clustering and mixture models. It is based on the classic fast food dataset from a marketing research case study.

---

## 📊 Objective

To identify distinct customer segments based on their perceptions of McDonald's and explore targeted strategies using:
- K-Means Clustering
- Finite Mixture Models
- Latent Class Regression
- Segment Evaluation & Profiling

---

## 🧠 Key Steps

1. **Data Preprocessing**  
   - Converted binary responses ("Yes"/"No") to numeric
   - Created sentiment scores from "I LOVE IT!" to "I HATE IT!"

2. **Segmentation (Clustering)**  
   - K-Means with 2–8 clusters
   - Mixture models for binary and regression

3. **Segment Profiling**  
   - Gorge plots
   - Segment-level stability
   - Segment vs Like, Gender, Age

4. **Evaluation**  
   - Segment Evaluation Plot (Visit Frequency vs Like Score)
   - Classification tree for predicting segment 3

5. **Marketing Mix Recommendations**  
   - Customised 4Ps for Segment 3 (young, price-conscious fans)

---

## 📁 Folder Structure
<pre>mcdonalds-casestudy-segmentation/ 
├── data/ # Raw data 
├── notebooks/ # Jupyter notebook with full analysis 
├── figures/ # All generated plots (png) 
├── README.md # You are here 
├── .gitignore # Standard ignore rules 
└── requirements.txt # Python dependencies </pre>


---

## 🧪 Requirements

Install dependencies:

```bash
pip install -r requirements.txt

```
💻 How to Run
Clone the repo

Open notebooks/CaseStudy_Analysis.ipynb in Jupyter

Run the cells to reproduce all analysis and plots


📈 Sample Outputs
<pre>
Figure	Description
A.4	Gorge Plot of 4-Segment K-Means
A.7	Information Criteria for Mixture Models
A.11	Mosaic Plot: Segment vs Like
A.15	Segment Evaluation Plot
A.14	Decision Tree for Segment 3 Membership
</pre>


📌 Author
Sreeya Ravikumar
Feynn Labs Internship | Summer 2025

