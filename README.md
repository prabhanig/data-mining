
# **CMU-MisCOV19 Dataset Analysis**

## **Overview**
This repository contains an analysis of the CMU-MisCOV19 dataset, a Twitter-based dataset that categorizes misinformation and factual content related to COVID-19. The primary objectives of this project are:
1. Perform text mining and preprocessing to clean and analyze the data.
2. Conduct sentiment analysis to understand emotional trends across different annotation categories.
3. Apply topic modeling to uncover hidden trends within the tweets and characterize the information landscape.

The dataset, code, and analysis results are organized for clarity and reproducibility.

---

## **Repository Structure**
The project is structured into the following folders:

```
CMU_MisCOV19_Analysis/
├── data/
│   └── CMU-MisCOV19.csv  # Raw dataset containing annotated tweets
├── code/
│   └── Data Mining and Analysis.Rmd  # R Markdown file with preprocessing and analysis code
├── report/
│   └── Data Mining and Analysis Using R_PG.pdf  # PDF report summarizing findings
└── README.md  # Documentation of the project
```

---

## **How to Use**

### **Prerequisites**
1. Install [R](https://cran.r-project.org/) on your system.
2. Install required R packages listed in the `.Rmd` file. Run this in R:
   ```R
   install.packages(c("tidyverse", "tm", "topicmodels", "sentimentr", "ggplot2", "wordcloud"))
   ```

### **Steps to Reproduce Analysis**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/CMU_MisCOV19_Analysis.git
   cd CMU_MisCOV19_Analysis
   ```
2. Open `Data Mining and Analysis.Rmd` in RStudio.
3. Run the R Markdown file to:
   - Clean and preprocess tweets.
   - Perform sentiment analysis.
   - Generate topic modeling insights.
4. View the PDF report in the `report/` folder for detailed findings.

---

## **Analysis Highlights**
### **Text Mining**
- Preprocessing included tokenization, stopword removal, and lemmatization.
- Visualizations such as word clouds and frequency plots were generated.

### **Sentiment Analysis**
- Compared positive, negative, and neutral sentiment distributions across annotation categories.
- Identified sentiment trends in conspiracy, misinformation, and factual tweets.

### **Topic Modeling**
- Applied Latent Dirichlet Allocation (LDA) to extract topics and key themes.
- Characterized clusters of tweets based on their linguistic and topical patterns.

---

## **Dataset Information**
The `CMU-MisCOV19.csv` dataset is sourced from a study at Carnegie Mellon University:
- **Number of Tweets**: Slightly less than 4573 (due to account suspensions).
- **Annotations**: Tweets are categorized into 17 different classes, including conspiracy, true treatment, fake cure, politics, and more.

---

## **References**
- Memon, S. A., & Carley, K. M. (2020). Characterizing COVID-19 Misinformation Communities Using a Novel Twitter Dataset. *Proceedings of the 29th ACM International Conference on Information and Knowledge Management (CIKM)*. [Link to Arxiv](https://arxiv.org/abs/2008.00791)
- COVID-19 Misinformation Annotation Codebook: Twitter. Carnegie Mellon University, School of Computer Science.

---

## **License**
The dataset and code are intended for academic and research purposes only. Please refer to the original dataset's terms for details.

---

## **Acknowledgments**
This project is based on the dataset and methodology presented in:
> **Characterizing COVID-19 Misinformation Communities Using a Novel Twitter Dataset**  
> Presented at CIKM 2020 by the Centre for Machine Learning and Health, Carnegie Mellon University.

---

## **Contributing**
Contributions are welcome! If you'd like to contribute, please:
1. Fork this repository.
2. Create a feature branch.
3. Submit a pull request with your changes.

---

## **Contact**
For any questions, feel free to open an issue or reach out via GitHub.
