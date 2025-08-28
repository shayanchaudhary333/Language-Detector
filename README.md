# Language Detection & Translation Tool  

This project is a **Language Detection & Translation GUI application** built using **Python, Tkinter, Scikit-learn, and Deep Translator**.  
It allows users to enter a sentence, automatically detects the input language, and provides translations in multiple target languages.  

---

## 🚀 Features  

- Detects the language of the entered text using **Naive Bayes (MultinomialNB)**.  
- Provides translations into multiple languages:
  - English  
  - Hindi  
  - French  
  - Spanish  
  - Bengali  
  - Chinese (Simplified)  
  - Arabic  
  - Russian  
- Simple and interactive **Tkinter GUI**.  

---

## 📂 Project Structure  

```
├── language.csv          # Dataset with text samples and their corresponding language labels
├── app.py                # Main Python code (Tkinter GUI + ML Model + Translator)
├── README.md             # Project documentation
```

---

## ⚙️ Installation  

1. Clone this repository or download the project files.  
2. Install the required dependencies:  

```bash
pip install numpy pandas scikit-learn deep-translator
```

Tkinter comes pre-installed with Python (on Windows/Linux). On some Linux systems, you may need to install it separately:  

```bash
sudo apt-get install python3-tk
```

---

## 📊 Dataset  

- The dataset (`language.csv`) contains two columns:  
  - **Text** → The input text/sentence.  
  - **language** → The corresponding language label.  
- This dataset is used to train the **Naive Bayes classifier** for language detection.  

---

## ▶️ Usage  

Run the application with:  

```bash
python app.py
```

1. Enter a sentence in the input field.  
2. Click on **Detect & Translate**.  
3. The app will:  
   - Detect the language of the entered text.  
   - Show translations in multiple target languages.  

---

## 🖼️ GUI Preview  

- **Input Box** → Type your text.  
- **Detect & Translate Button** → Runs detection + translation.  
- **Output Label** → Displays detected language + translations.  

---

## 🛠️ Technologies Used  

- **Python**  
- **Tkinter** → GUI framework  
- **Scikit-learn** → Machine Learning (Naive Bayes)  
- **Deep Translator** → For translations  
- **Pandas & NumPy** → Data handling  

---

## 📌 Future Improvements  

- Add support for **more languages**.  
- Improve dataset for better accuracy.  
- Add **speech-to-text input**.  
- Provide **text-to-speech output** for translations.  

---

## 👨‍💻 Author  

Developed by **[Your Name]** ✨  
