# ML Project

## Project Overview

This project explores gene essentiality in cancer cells across various lineages and primary diseases utilizing the DepMap Cancer Cell Line Encyclopedia (CCLE) data. Through a robust analytical approach combining Pearson correlation analysis, Principal Component Analysis (PCA), t-Distributed Stochastic Neighbor Embedding (t-SNE), and advanced machine learning algorithms, this study aims to unravel the complex relationships between gene expression, knockout effects, and copy number variations.

## Objectives

- **Data Integration**: To integrate multi-omics data from different sources to provide a comprehensive dataset for analysis.
- **Analytical Techniques**: Employ various statistical and machine learning methods to analyze the dataset.
- **Insight Generation**: Generate insights into the molecular mechanisms that drive cancer progression and identify potential therapeutic targets.

## Methods

1. **Pearson Correlation Analysis**: To study linear correlations between different omics data.
2. **PCA & t-SNE**: For data dimensionality reduction and visualization of the data clustering.
3. **Machine Learning Models**: Application of several machine learning algorithms to predict cell lineage from multi-omics data.

## Results

The project successfully demonstrates the capability of machine learning algorithms to predict cancer cell lineage from multi-omics data. The findings indicate that machine learning tools are valuable in identifying potential relationships in cancer cell biology and can significantly aid in cancer research by pinpointing potential therapeutic targets.

## Conclusion

In conclusion, this study investigated the gene essentiality of cancer cells across multiple lineages and primary diseases using the DepMap CCLE data. The study employed a combination of techniques, including Pearson correlation analysis, PCA, t-SNE, and machine learning algorithms, to identify potential relationships between gene expression, knockout effect, and copy number variation in the specific subset of samples represented in all three datasets. The study revealed that machine learning algorithms can be effective in predicting cell lineage based on multi-omics data, with important implications for cancer research and identifying potential therapeutic targets. However, the effectiveness of feature selection is algorithm-dependent and dataset-specific, and it is crucial to weigh the potential advantages and disadvantages of feature selection carefully before employing it in a machine learning task. Overall, the findings of this study contribute to the existing knowledge base of cancer cell biology and provide insights into the molecular mechanisms driving cancer progression.

## Installation and Usage

Please refer to the `requirements.txt` file for the necessary Python libraries and install them using the following command:

```bash
pip install -r requirements.txt
