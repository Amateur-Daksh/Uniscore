# 🎓 UniScore – Standardized Student Ranking System  

**UniScore** is a **normalization-based ranking system** designed to fairly compare students from different educational boards (**CBSE, ICSE, and State Boards**). Since different boards have varying levels of difficulty, UniScore applies **statistical normalization** to ensure **equitable ranking** of students.  

---

## 📌 Problem Statement  

Selection for competitive programs often relies on **raw percentage scores**, which may not be fair due to varying grading standards across different boards.  

✅ **UniScore normalizes scores** using **Z-score normalization** and **percentile ranking**, ensuring a fair comparison among students.  

---

## 🚀 Features  

✔ **Normalization-Based Ranking** – Converts raw scores into a fair percentile-based ranking system.  
✔ **Cross-Board Comparisons** – Ensures students from different boards are evaluated equitably.  
✔ **Automated Data Processing** – Reads student data, applies statistical methods, and outputs **ranked results**.  
✔ **Scalable & Extensible** – Can be adapted for additional datasets and education systems.  

---

## 🏗 How It Works  

1️⃣ **Load Student Scores** – Reads data from **CBSE, ICSE, and State Board CSV files**.  
2️⃣ **Apply Z-Score Normalization** – Standardizes scores across different boards.  
3️⃣ **Calculate Percentiles** – Uses **normal distribution** to compute rankings.  
4️⃣ **Generate Ranked List** – Outputs the **final student rankings** in JSON format.  

---

## 📥 Installation & Usage  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/Amateur-Daksh/Uniscore.git
cd Uniscore
```

### **2️⃣ Install Dependencies**  
```sh
pip install -r requirements.txt
```

### **3️⃣ Generate Sample Data (If Needed)**  
```sh
python generate_state_q1.py
```

### **4️⃣ Run UniScore**  
```sh
python Uniscore.py
```

### **5️⃣ View Results**  
📊 **Top-ranked students** will be displayed in the terminal.  
📂 The full ranking list is stored in **`student_data.json`**.  

---

## 📊 Example Output  

```json
[
    {"Rank": 1, "Name": "Daksh Yadav", "Percentile": "99.87"},
    {"Rank": 2, "Name": "Aditi Chaturvedi", "Percentile": "98.75"},
    {"Rank": 3, "Name": "Neha Gupta", "Percentile": "97.42"}
]
```

---

## 🤝 Contributing  

We welcome contributions! If you'd like to improve **UniScore**, follow these steps:  

1. **Fork the repository**  
2. **Create a new feature branch**  
3. **Submit a pull request**  

For major feature suggestions, open an **issue** first to discuss proposed changes.  

---

## 📜 License  

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

## 📬 Contact  

For inquiries or collaborations, feel free to reach out via:  

📧 **Email:** [16vansh16@gmail.com](16vansh16@gmail.com)  
🔗 **GitHub Issues:** [Report a bug](https://github.com/Amateur-Daksh/Uniscore/issues)  

---

If you find **UniScore** useful, don’t forget to ⭐ star the repository! 🚀
