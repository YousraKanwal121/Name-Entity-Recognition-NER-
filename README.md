# 🧠 Named Entity Recognition (NER) using spaCy

A Custom Named Entity Recognition (NER) system developed using **Python** and **spaCy** to identify named entities from article-based datasets. The project includes data preprocessing, model training, evaluation, and an interactive **Streamlit dashboard** where users can enter text and receive predicted entities in real time.

---

## 📌 Project Overview

Named Entity Recognition (NER) is a Natural Language Processing (NLP) task that identifies and classifies important entities in text such as **Person, Organization, Location, Date, Money, and more**.

This project was developed using an article dataset. After training the custom spaCy model, a Streamlit dashboard was created that allows users to enter any sentence and instantly view the detected entities.

---

## ✨ Features

- 🔴 Custom Named Entity Recognition (NER) model
- 🔴 Built using Python and spaCy
- 🔴 Trained on an article dataset
- 🔴 Data preprocessing and cleaning
- 🔴 Model training and evaluation
- 🔴 Real-time entity prediction
- 🔴 Interactive Streamlit dashboard
- 🔴 User-friendly interface

---

## 🛠️ Technologies Used

- Python
- spaCy
- Pandas
- NumPy
- Streamlit
- Matplotlib
- Plotly
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
NER-Project/
│
├── Dataset/
├── Model/
├── Dashboard/
├── Images/
├── notebooks/
├── app.py
├── requirements.txt
├── README.md
└── trained_model/
```

---

## ⚙️ Workflow

1. Collect article dataset
2. Clean and preprocess the data
3. Prepare training annotations
4. Train a custom spaCy NER model
5. Evaluate model performance
6. Save the trained model
7. Build an interactive Streamlit dashboard
8. Predict entities from user input

---

## 🎯 Entity Types

The model can identify entities such as:

- PERSON
- ORG (Organization)
- GPE (Location)
- DATE
- MONEY
- CARDINAL
- TIME
- EVENT
- PRODUCT
- LAW
- NORP
- FAC
- LOC
- WORK_OF_ART

---

## 🚀 Dashboard

The Streamlit dashboard allows users to:

- Enter any sentence or paragraph.
- Predict named entities instantly.
- Display detected entities with their labels.
- Provide an easy-to-use interface for text analysis.

Example:

**Input**

```
Apple CEO Tim Cook visited London on 20 June 2025.
```

**Output**

| Entity | Label |
|---------|-------|
| Apple | ORG |
| Tim Cook | PERSON |
| London | GPE |
| 20 June 2025 | DATE |

---

## 📊 Applications

- Information Extraction
- News Article Analysis
- NLP Research
- Text Analytics
- Document Processing
- AI-based Text Understanding

---

## ▶️ How to Run

### Clone the repository

```bash
git clone https://github.com/YousraKanwal121/Your-Repository-Name.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📸 Screenshots

Add screenshots of your dashboard here.

Example:

```
![Dashboard](https://github.com/YousraKanwal121/Named-Entity-Recognition-NER-/blob/main/dashboard.png)
![Dashboard](https://github.com/YousraKanwal121/Named-Entity-Recognition-NER-/blob/main/dashboard.png)
```

---

## 📈 Future Improvements

- Improve model accuracy
- Support more entity types
- Upload PDF and Word documents
- Deploy the application online
- Add confidence scores
- Support multiple languages

---

## 👩‍💻 Author

**Yousra Kanwal**

Software Engineering Student

GitHub: https://github.com/YousraKanwal121


---

