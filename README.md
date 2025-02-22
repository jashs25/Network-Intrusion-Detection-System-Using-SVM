# 🚀 Network Intrusion Detection System Using SVM  

## 📌 Project Overview  
This project implements a **Network Intrusion Detection System (NIDS)** using **Support Vector Machine (SVM)** to classify network traffic as normal or malicious. With the increasing complexity of cyber threats, machine learning-based intrusion detection systems have gained significant attention for enhancing network security.  

## 📂 Dataset  
The dataset used contains **5,000 records** of **Network Port Statistics**, classified into six categories:  
- **Normal (0)**  
- **Blackhole (1)**  
- **TCP-SYN (2)**  
- **PortScan (3)**  
- **Diversion (4)**  
- **Overflow (5)**  

Each record includes features such as received/sent packets, bytes, port activity duration, dropped/error packets, and network load metrics.  

## 🛠 Features & Methodology  
- **Data Preprocessing:** Handling missing values, normalization, and feature selection.  
- **Support Vector Machine (SVM):** Used for classification to detect network intrusions effectively.  
- **Evaluation Metrics:** Accuracy, precision, recall, and F1-score to measure performance.  

## 🖥 Installation & Usage  
### 📥 Prerequisites  
Ensure you have the following installed:  
- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  


## 📊 Results & Insights  
- The SVM model successfully classifies network traffic into various intrusion types.  
- Feature importance analysis highlights key indicators of malicious activity.  
- Model performance is evaluated using confusion matrices and classification reports.  

## 🤝 Contributions  
Contributions are welcome! Feel free to fork the repository, create an issue, or submit a pull request.  

## 📜 License  
This project is licensed under the **MIT License**.  

## 📩 Contact  
For any questions or discussions, feel free to reach out or open an issue.  
