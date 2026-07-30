# 📝 Context-Aware Word Frequency Analysis and Word Sense Disambiguation for English and Marathi

## 📌 Project Overview

This project is a Natural Language Processing (NLP) application that performs **Word Frequency Analysis** and **Word Sense Disambiguation (WSD)** for both **English** and **Marathi** text. The system analyzes uploaded documents, identifies frequently occurring words, and determines the contextual meaning of ambiguous words using the **Lesk Algorithm** and **WordNet**.

The application provides an interactive interface built with **Gradio**, allowing users to upload text documents and visualize the analysis results.

---

## ✨ Features

- Supports **English** and **Marathi** text analysis
- Automatic text preprocessing
- Tokenization and stop-word removal
- Word Frequency Analysis
- Word Sense Disambiguation using Lesk Algorithm
- WordNet-based semantic analysis
- Interactive Gradio web interface
- PDF and text file support

---

## 🛠 Technologies Used

- Python
- NLTK
- WordNet
- Lesk Algorithm
- Gradio
- Pandas
- NumPy
- Matplotlib

---
## 📚 Marathi Dictionary

The project includes a custom Marathi dictionary containing several hundred Marathi words. Each word is associated with five contextual meanings, enabling richer semantic analysis.
---

## ⚙️ How It Works

The application follows these steps:

1. Upload a PDF or text document.
2. Extract text from the document.
3. Search for the selected word.
4. Count the total number of occurrences.
5. Display every complete sentence containing the searched word.
6. Retrieve and display all **five meanings** of the searched word from the Marathi dictionary.

---

## 📂 Project Structure

```
Word-Frequency-Analysis/
│
├── app.py
├── requirements.txt
├── README.md
├── dataset/
├── images/
│   ├── interface.png
│   ├── english_input.png
│   ├── marathi_input.png
│   ├── frequency.png
│   ├── wsd.png
│   └── output.png
```

---

## 📷 Screenshots

### 🖥️ English Application Interface
 

<img width="1247" height="913" alt="image" src="https://github.com/user-attachments/assets/be5bd809-cfdb-4d0c-bded-0c1a5794794a" />


### 🖥️ Marathi Application Interface

<img width="1891" height="913" alt="image" src="https://github.com/user-attachments/assets/978d7364-456a-43b9-90fa-93305fa839d2" />

---

### 🇬🇧 English Input Document

<img width="1226" height="905" alt="image" src="https://github.com/user-attachments/assets/307c7cba-aa81-44a0-9cc6-df5266c62d85" />

---

### 🇮🇳 Marathi Input Document


<img width="1920" height="918" alt="image" src="https://github.com/user-attachments/assets/780620f2-cbc7-435a-9769-81b4589971b7" />

---

### 📊 English Word Frequency Analysis

<img width="517" height="126" alt="image" src="https://github.com/user-attachments/assets/91852f03-80c6-4005-a283-88b5c582efc5" />

### 📊 Marathi Word Frequency Analysis

<img width="847" height="137" alt="image" src="https://github.com/user-attachments/assets/09d76f93-c3bf-4573-9456-5a51ea59fc35" />



---

### 🧠 English Word Sense Disambiguation

<img width="1920" height="538" alt="image" src="https://github.com/user-attachments/assets/11e1fb56-7f6e-4dfc-9425-97a60c468888" />
<img width="1020" height="470" alt="image" src="https://github.com/user-attachments/assets/75e47823-4795-4ce5-84da-96b2e7ecb012" />

### 🧠 Marathi Word Sense Disambiguation

<img width="1902" height="902" alt="image" src="https://github.com/user-attachments/assets/a79e7d4c-cfbc-4505-b296-b9fab8ad8817" />

<img width="830" height="900" alt="image" src="https://github.com/user-attachments/assets/c8574bcf-02ef-4fb1-a961-da9428b352a6" />

---

### ✅ Final Output (English & Marathi)

<img width="1196" height="918" alt="image" src="https://github.com/user-attachments/assets/bfd40128-0be1-4d0a-97d3-d4ea49a9f14a" />

<img width="1693" height="914" alt="image" src="https://github.com/user-attachments/assets/08568846-a980-495a-856c-4ad534744f04" />

---

## 📊 Results

- Successfully processed both English and Marathi PDF documents.
- Computed the total frequency of searched words.
- Displayed all complete sentences containing the searched word.
- Retrieved five contextual meanings from the custom Marathi dictionary.
- Implemented Word Sense Disambiguation using the Lesk Algorithm and WordNet.
- Built an interactive bilingual NLP application using Gradio.

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/truptip2005/Word-Frequency-Analysis.git
```

Move to the project folder

```bash
cd Word-Frequency-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

---

## 🚀 Future Improvements

- Support additional Indian languages
- Advanced Transformer-based Word Sense Disambiguation
- Named Entity Recognition (NER)
- Sentiment Analysis
- Topic Modeling
- Cloud Deployment

---

## 👩‍💻 Author

**Trupti Shashikant Panchwatkar**

GitHub: https://github.com/truptip2005
