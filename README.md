# SMS-Spam-Detection-ASSIGNMNET-NO-3--ML
SMS Spam Detection System 🚀 This ML project classifies messages as 'Ham' or 'Spam' using Python &amp; NLP.  Key Features: ✅ Data Preprocessing &amp; Tokenization ✅ TF-IDF Vectorization ✅ Multinomial Naive Bayes Model ✅ Django-based backend for real-time analysis.  Developed for ML Assignment 3 to demonstrate text classification and model deployment.

A **README** file is the first thing people see when they visit your project. For your SMS Spam Detection project, it should clearly explain what the project does, how to set it up, and the results you achieved.

Here is a professional **README.md** template specifically tailored for your project:

---

# SMS Spam Detection System

An end-to-end Machine Learning solution designed to classify SMS messages into **Spam** or **Ham** (Legitimate) using Natural Language Processing (NLP) and the Random Forest algorithm.

## 🚀 Features
* **Automated Text Cleaning:** Handles missing data and messy CSV formatting.
* **NLP Pipeline:** Utilizes `TfidfVectorizer` to convert raw text into meaningful numerical features.
* **Hyperparameter Tuning:** Optimized using `GridSearchCV` for maximum accuracy.
* **Interactive Interface:** A built-in prediction cell for real-time message testing.

## 📊 Performance
The model was tuned to achieve high precision and recall, ensuring that legitimate messages are not incorrectly flagged as spam.

* **Final Accuracy:** ~97%
* **Model:** Tuned Random Forest Classifier
* **Validation:** 5-Fold Cross-Validation

## 🛠️ Tech Stack
* **Language:** Python 3.14
* **Environment:** VS Code / Jupyter Notebook
* **Libraries:** * `pandas` & `numpy` (Data Manipulation)
    * `scikit-learn` (Machine Learning & Preprocessing)
    * `seaborn` & `matplotlib` (Visualization)

## 📁 Project Structure
```text
SMS-SPAM-DETECTION/
├── data/
│   └── spam.csv            # The raw dataset
├── notebooks/
│   └── sms_detection.ipynb  # Main development notebook
├── models/
│   └── spam_model.pkl      # Saved trained model (optional)
├── requirements.txt        # List of dependencies
└── README.md               # Project documentation
```

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/SMS-Spam-Detection.git
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook:**
   Open `notebooks/sms_detection.ipynb` in VS Code or Jupyter and run all cells to train the model and test the interactive interface.

## 🧪 Testing the Model
Once the model is trained, you can input custom messages in the deployment cell:
* **Input:** *"You have won a $1,000 prize! Claim now."* → **Output:** `SPAM`
* **Input:** *"Hey, are you coming to the university today?"* → **Output:** `HAM`

## 📝 License
Distributed under the MIT License. See `LICENSE` for more information.

