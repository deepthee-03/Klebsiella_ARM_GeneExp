# 📊 Association Rule Mining in *Klebsiella pneumoniae* Using Gene Expression Data

## 🚀 Overview
This project applies **association rule mining** to analyze gene expression data from *Klebsiella pneumoniae*, identifying significant gene associations that may contribute to **antimicrobial resistance (AMR)**. By leveraging the **Apriori algorithm**, we uncover patterns of gene co-expression, aiding research in antibiotic resistance mechanisms.

## 🌟 Key Features
1. **Frequent Itemset Mining** 🔍:
   - Uses the **Apriori algorithm** to find frequent gene associations from gene expression data.
2. **Filtering Strong Associations** 📊:
   - Filters rules based on **lift > 2.2** to retain biologically significant gene interactions.
3. **Biological Validation** 🧬:
   - Cross-references **CARD (Comprehensive Antibiotic Resistance Database)** and **STRING (Protein Interaction Database)** to validate gene associations.
4. **Network Visualization** 📈:
   - Constructs **gene association networks** using **NetworkX** to display interactions visually.

## 🔬 Methodology
### Step-by-Step Process:
1️⃣ **Data Preprocessing**:
   - Normalizes gene expression data and converts it into a **binary matrix** for analysis.
     
2️⃣ **Association Rule Mining**:
   - Applies the **Apriori algorithm** to extract frequent gene co-expression patterns.
     
3️⃣ **Filtering Significant Rules**:
   - Selects rules with **lift > 2.2** to focus on **strong gene interactions**.
     
4️⃣ **Biological Validation**:
   - Compares identified gene pairs with **known antibiotic resistance genes** in **CARD & STRING**.
     
5️⃣ **Network Visualization**:
   - Constructs a **gene interaction network** for better interpretability.

## ⚙️ Technologies Used
- **Python** 🐍
- **Libraries**: Pandas, NumPy, mlxtend, NetworkX, Matplotlib
- **Algorithms**: Apriori (Association Rule Mining)
- **Databases**: CARD, STRING (for biological validation)

## 📂 Installation & Setup
To run this project locally:

1️⃣ Clone the repository:
```sh
git clone https://github.com/your-username/Klebsiella_ARM_GeneExp.git
cd Klebsiella_ARM_GeneExp
```
2️⃣ Install dependencies:
```sh
pip install -r requirements.txt
```
3️⃣ Run the association rule mining script:
```sh
python apriori_analysis.py
```

## 🚀 Usage
- Run the **Apriori algorithm** on gene expression data:
  ```sh
  python apriori_analysis.py
  ```
- Generate and visualize **gene interaction networks**:
  ```sh
  python visualize_network.py
  ```

## 📊 Results
- **Key Findings**:
  - Identified strong gene associations in *Klebsiella pneumoniae*.
  - Some genes mapped to **antibiotic resistance genes** in the **CARD database**.
  - **Network visualization** revealed potential co-regulated gene clusters.

## 🔮 Future Work
🔹 Extend analysis to **larger datasets** and other bacterial species.

🔹 Apply **deep learning** models for **gene interaction prediction**.

🔹 Conduct **wet-lab validation** of newly identified gene associations.

## 🤝 Contributing
We welcome contributions! Feel free to **fork** the repo, make improvements, and submit a **pull request**.

## 📧 Contact
For questions or collaborations, reach out at **deepthee16@gmail.com**.
