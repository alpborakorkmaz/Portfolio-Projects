# Text Analysis with Apriori Algorithm

This project aims to perform a word-based frequency analysis using the **Apriori Algorithm**. **Apriori** is a widely used algorithm for discovering relational rules in large datasets. In this project, patterns of specific words that are frequently used together are examined and analyzed.

## 🔍 Project Objective
In this study, the **Apriori Algorithm** is applied to find frequently co-occurring word groups within a text dataset. Specifically:
- To understand customer habits in **marketing** strategies,
- To discover significant relationships in **Customer Relationship Management**,
- To gain valuable insights through **text analysis**.

## 📂 Dataset
The project is conducted on a text dataset composed of documents. Each row represents the content of a document, and the words occurring in these documents are analyzed using the Apriori Algorithm.
The operations applied to the dataset include:
- **Data cleaning**, filtering out unwanted words and special characters.
- Formatting the data into a suitable structure.

### Data Cleaning
- **Conjunctions**, **special characters**, and **unwanted words** were removed.
- Turkish character conversions were performed (e.g., "ð" → "ğ", "þ" → "ş").

## 🔨 Operations Performed
1. **Data Cleaning**: 
    - Unwanted words and special characters were removed, preparing the dataset for analysis.
    - Necessary transformations were applied to correctly handle Turkish characters.
  
2. **Data Preparation**: 
    - A data structure suitable for the Apriori Algorithm was created. In this step, each row represents a document, and the relationships of words are structured accordingly.

3. **Application of Apriori Algorithm**: 
    - The Apriori Algorithm was used to identify patterns consisting of frequently co-occurring words. These patterns were utilized for discovering rules and associations.

## 📊 Results
As a result of the project, groups of words frequently found together in the data were identified. The relationships between these words can be particularly useful in:
- **Analyzing customer behavior**,
- **Market basket analysis**,
- **Text mining**.

### Identified Patterns
- The Apriori Algorithm has revealed groups of words that frequently occur together (for example, terms that may be important in marketing efforts).
- The relationships obtained can be used in marketing strategies and provide strong insights for text analysis and customer behavior analysis.

## 🛠️ Technologies Used
The project was implemented using the Python programming language and the following libraries:
- `pandas`: For data manipulation and analysis.
- `mlxtend`: For the application of the Apriori Algorithm.
