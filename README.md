# **Phishing URL Detection using Machine Learning** 🛡️  

A machine learning-based project to detect phishing websites using URL features and **Logical regression and XGBoost Classifier**.

## **📌 Features Extracted**
This model analyzes the URL structure to detect phishing attempts. Some extracted features include:
- URL length, number of dots, hyphens, and special characters
- Presence of HTTPS (`has_https`)
- Subdomain count
- Ratio of digits to letters
- Path length and number of double slashes  
... and **many more!**

---

## **🖥️ How It Works?**
1. Extracts features from the URL dynamically.  
2. Preprocesses the extracted features (scaling, cleaning).  
3. Loads the **trained XGBoost model** and makes a prediction.  
4. Outputs whether the URL is **phishing or legitimate**.  

---

## **📊 Model Performance**
- **Algorithm Used:** XGBoost Classifier  
- **Accuracy:** `XX%` _(Replace with your model’s accuracy)_  
- **Confusion Matrix Visualization**:  

---

## **🛠️ Future Improvements**
- ✅ Integrate with **Flask/Streamlit** for a web interface  
- ✅ Train on a **larger dataset** for better accuracy  
- ✅ Deploy as a **real-time API**  

---

## **👨‍💻 Contributing**
Pull requests are welcome! If you’d like to contribute, please open an issue first to discuss your ideas.  

---

## **📬 Contact**
📧 **Email:** iamaradhya840@gmail.com

📜 **GitHub:** aradhyagh 
