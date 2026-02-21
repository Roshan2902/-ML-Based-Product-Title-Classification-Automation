**🛍️ ML-Based Product Title Classification Automation**
📌 Project Overview
    This project automates product title classification into correct Category and Sub-Category using Machine Learning.
    Previously, product categorization was done manually by the team. This process was time-consuming and not scalable as data volume increased daily.
    To solve this, I developed an ML-based automation system using XGBoost, reducing manual effort by 70–75% and improving delivery speed.
    
**🚀 Problem Statement**
    Manual product categorization was slow and error-prone.
    Dataset size was increasing daily.
    Existing manual process could not scale efficiently.
    The goal was to build a fast, scalable, and accurate ML model to automate classification.

**🧠 Approach**
    Built a text classification model using TF-IDF + XGBoost Classifier.
    Compared multiple models (SVM, Logistic Regression) before selecting XGBoost for better speed and scalability.
    Added additional required data extraction fields for stakeholder reporting.
    Integrated QC validation logic using keyword checklist.
    
**⚙️ How It Works**
    Install and import required libraries (Pandas, Scikit-learn, XGBoost, etc.).
    Upload training dataset containing product titles with correct categories.
    Clean and preprocess text data using regex.
    Convert product titles into numerical features using TF-IDF Vectorization.
    Train the XGBoost Classifier model.
    Evaluate model performance using accuracy score.
    Upload a new Excel file containing uncategorized product titles.
    The trained model predicts Category and Sub-Category for new data.
    **Extract additional required columns from product title:**
        Brand mapping
        Pack size/type extraction
        Pack quantity detection (e.g., Buy 1 Get 1, Pack of 2, Bundle of 4)
    **Perform QC validation:**
        Directly access Google Sheets checklist file
        Read “Keyword” tab containing relevant and non-relevant keywords
        Flag categorization as correct or incorrect based on keyword match
    Generate final structured output file.
    Download the processed Excel file for reporting and dashboard use.

**🛠️ Technologies Used**
    Python
    Pandas
    Scikit-learn
    XGBoost
    TF-IDF Vectorizer
    Regex
    Google Sheets Integration

**📊 Results**
    Reduced manual categorization effort by 70–75%
    Improved classification speed and scalability
    Automated QC validation process
    Faster delivery turnaround time

📈 Future Improvements
    Hyperparameter tuning for better accuracy
    Model deployment using API
    Real-time prediction integration
    Continuous learning with new product data

🎯 Conclusion
    This project demonstrates how Machine Learning can automate repetitive business tasks, improve efficiency, and scale with growing data.
    It combines text processing, feature engineering, and model optimization to solve a real-world business problem.
    
