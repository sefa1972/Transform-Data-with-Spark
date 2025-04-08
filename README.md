# Lab 6 - Using Spark in Azure Synapse Analytics to Transform Data

This project demonstrates how to use a Spark notebook within Azure Synapse Analytics to transform data. The lab is based on a Microsoft Learn module and involves working with a data lake and a Spark pool to analyze and transform data.

## 🚀 Objective

- Create an Azure Synapse Analytics workspace
- Set up a Spark pool and connect it to a data lake
- Use a Spark notebook to analyze and transform data

## 🧰 Technologies Used

- Azure Synapse Analytics
- Apache Spark
- Azure Data Lake Storage
- PowerShell
- ARM (Azure Resource Manager) Template
- Python (PySpark)
- Jupyter Notebook (.ipynb)

## 🔧 Steps Followed

1. **Workspace Setup**  
   A Synapse workspace with access to a data lake and Spark pool was created using a combination of a PowerShell script and an ARM template.

2. **Notebook Preparation**  
   The notebook `Spark Transform.ipynb` was downloaded from the `Allfiles/labs/06/notebooks` directory and uploaded to Synapse Studio.

3. **Connecting to Spark Pool**  
   The notebook was connected to the Spark pool created earlier.

4. **Running Code Cells and Data Transformation**  
   The code cells in the notebook were reviewed and executed step-by-step. Basic analysis and transformation operations were performed on the data.

5. **Resource Cleanup**  
   To avoid unnecessary Azure costs, all created resources were deleted after completing the lab.

## 📂 Project Structure

```
📁 lab6-spark-transform
├── README.md
├── Spark Transform.ipynb
└── deployment/
    ├── setup.ps1
    └── template.json
```

## ✅ Outcome

This lab provided hands-on experience with **data transformation** using Spark in Azure. It also helped to better understand working with notebooks in Synapse Studio and handling Spark-based operations in a cloud environment.

---

💡 Note: All resources used in this project were for educational purposes and structured for individual learning.
