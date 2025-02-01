# AI-Learning
Here are the 12 chapters for the book "AI Agent Building with Python from Scratch" in Odia with some English terminology:

1. **Python Basics (Python ର ମୂଳ ତତ୍ତ୍ୱ)**  
   - Variables, Data Types, Loops, Functions.

2. **Python for Data Handling (ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ ପାଇଁ Python)**  
   - Lists, Dictionaries, File Handling, Libraries like NumPy, Pandas.

3. **Introduction to AI and ML (AI ଏବଂ ML ର ପରିଚୟ)**  
   - Basics of Artificial Intelligence and Machine Learning.

4. **Mathematics for AI (AI ପାଇଁ ଗଣିତ)**  
   - Linear Algebra, Probability, Statistics.

5. **Data Preprocessing (ଡାଟା ପ୍ରିପ୍ରୋସେସିଂ)**  
   - Cleaning, Normalization, Feature Engineering.

6. **Supervised Learning (ସୁପରଭାଇଜଡ୍ ଲର୍ନିଂ)**  
   - Regression, Classification, Algorithms like Linear Regression, Decision Trees.

7. **Unsupervised Learning (ଅନସୁପରଭାଇଜଡ୍ ଲର୍ନିଂ)**  
   - Clustering, Dimensionality Reduction, K-Means, PCA.

8. **Deep Learning Basics (ଡିପ୍ ଲର୍ନିଂ ର ମୂଳ ତତ୍ତ୍ୱ)**  
   - Neural Networks, TensorFlow, Keras.

9. **Natural Language Processing (NLP) (ପ୍ରାକୃତିକ ଭାଷା ପ୍ରକ୍ରିୟାକରଣ)**  
   - Text Processing, Sentiment Analysis, Word Embeddings.

10. **Reinforcement Learning (ରିଇନଫୋର୍ସମେଣ୍ଟ ଲର୍ନିଂ)**  
    - Q-Learning, Markov Decision Processes, OpenAI Gym.

11. **Building AI Agents (AI ଏଜେଣ୍ଟ ତିଆରି)**  
    - Designing Agents, Integrating ML Models, Real-world Applications.

12. **Deployment and Ethics (ଡିପ୍ଲଏମେଣ୍ଟ ଏବଂ ନୈତିକତା)**  
    - Model Deployment, AI Ethics, Future of AI.

This structure ensures a gradual progression from Python basics to advanced AI Agent building, suitable for Odia-speaking learners.
ନିମ୍ନଲିଖିତ ପ୍ରଥମ ଅଧ୍ୟାୟ (Chapter 1) ର ସୁନ୍ଦର ସଂରଚନା ଏବଂ ଉଦାହରଣ ସହିତ ପ୍ରସ୍ତୁତ କରାଗଲା:

---

### **ଅଧ୍ୟାୟ 1: Python ର ମୂଳ ତତ୍ତ୍ୱ**  
#### **Python: ଏକ ସରଳ ପରିଚୟ**  
Python ହେଉଛି ଏକ high-level, ସହଜ-ବୋଧ୍ୟ ପ୍ରୋଗ୍ରାମିଂ ଭାଷା, ଯାହା AI/ML ପାଇଁ ବ୍ୟାପକ ଭାବେ ବ୍ୟବହୃତ ହୁଏ।  

---

### **ପ୍ରୟୋଜନୀୟ ସାମଗ୍ରୀ ସେଟଅପ୍**  
1. **IDE (Integrated Development Environment):**  
   - VS Code, PyCharm, କିମ୍ବା Jupyter Notebook ବ୍ୟବହାର କରନ୍ତୁ।  
   - *ଇନ୍ସ୍ଟଲେସନ୍ କମାଣ୍ଡ (Windows):*  
     ```bash  
     winget install Python.Python.3.10  
     ```  
   - *Linux/macOS:*  
     ```bash  
     sudo apt-get install python3  
     ```  

2. **Python ପ୍ୟାକେଜ୍ ଇନ୍ସ୍ଟଲ୍ କରନ୍ତୁ:**  
   ```bash  
   pip install numpy pandas  
   ```  

---

### **ମୂଳ ବାକ୍ୟରଚନା (Basic Syntax)**  
**ଉଦାହରଣ 1:** ପ୍ରଥମ Python ପ୍ରୋଗ୍ରାମ୍  
```python  
print("ନମସ୍କାର ଓଡିଶା!")  # Output: ନମସ୍କାର ଓଡିଶା!  
```  

**ଉଦାହରଣ 2:** ଭେରିଏବଲ୍ (Variables)  
```python  
ନାମ = "ରାମ"  
ବୟସ = 25  
print(f"{ନାମ} ର ବୟସ {ବୟସ} ବର୍ଷ")  # Output: ରାମ ର ବୟସ 25 ବର୍ଷ  
```  

---

### **ଡାଟା ପ୍ରକାର (Data Types)**  
1. **ପୂର୍ଣ୍ଣ ସଂଖ୍ୟା (Integer):** `10`, `-5`  
2. **ଦଶମିକ (Float):** `3.14`, `-0.5`  
3. **ବାକ୍ୟ (String):** `"ଓଡିଆ"`, `'AI'`  
4. **ବୁଲିଆନ୍ (Boolean):** `True`, `False`  

**ଉଦାହରଣ 3:** ଡାଟା ପ୍ରକାର ଚେକ୍ କରିବା  
```python  
ଜନ୍ମବର୍ଷ = 2000  
print(type(ଜନ୍ମବର୍ଷ))  # Output: <class 'int'>  
```  

---

### **କଣ୍ଟ୍ରୋଲ୍ ଷ୍ଟ୍ରକ୍ଚର୍ (Control Structures)**  
1. **if-else ଷ୍ଟେଟମେଣ୍ଟ୍:**  
```python  
ସଂଖ୍ୟା = 10  
if ସଂଖ୍ୟା > 0:  
    print("ଧନାତ୍ମକ ସଂଖ୍ୟା")  
else:  
    print("ଋଣାତ୍ମକ ସଂଖ୍ୟା")  
```  

2. **ଲୁପ୍ (For Loop):**  
```python  
for i in range(3):  
    print(f"ଗଣନା: {i}")  # Output: 0, 1, 2  
```  

---

### **ଫଙ୍କସନ୍ (Functions)**  
**ଉଦାହରଣ 4:** ଏକ ସରଳ ଫଙ୍କସନ୍  
```python  
def କ୍ଷେତ୍ରଫଳ(ଲମ୍ବ, ପ୍ରସ୍ଥ):  
    return ଲମ୍ବ * ପ୍ରସ୍ଥ  

ଫଳ = କ୍ଷେତ୍ରଫଳ(5, 3)  
print(f"କ୍ଷେତ୍ରଫଳ: {ଫଳ} ବର୍ଗମିଟର")  # Output: 15 ବର୍ଗମିଟର  
```  

---

### **ସାରାଂଶ**  
- Python ରେ ଭେରିଏବଲ୍, ଡାଟା ପ୍ରକାର, ଲୁପ୍, ଏବଂ ଫଙ୍କସନ୍ ର ମୂଳ ବ୍ୟବହାର।  
- **ଅଭ୍ୟାସ:** ଏକ ପ୍ରୋଗ୍ରାମ୍ ଲେଖନ୍ତୁ ଯାହା ଗୋଟିଏ ଲିଷ୍ଟର ସଂଖ୍ୟାଗୁଡିକର ସର୍ବୋଚ୍ଚ ମୂଲ୍ୟ ଖୋଜିବ।  

**ଆଗାମୀ ଅଧ୍ୟାୟ:** Python ରେ ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ (Lists, NumPy, Pandas)!  

--- 

ଏହି ଅଧ୍ୟାୟରେ ଆପଣ **Python ର ମୂଳ କଣ୍ସେପ୍ଟ୍** ସହିତ ପରିଚିତ ହୋଇଛନ୍ତି। ପ୍ରତ୍ୟେକ ଉଦାହରଣକୁ IDE ରେ ଟେଷ୍ଟ କରନ୍ତୁ!

Here’s the first part of **Chapter 2** divided into 3 sections. I’ll write **Part 1: Python Lists and Dictionaries (ଲିଷ୍ଟ ଏବଂ ଡିକ୍ସନାରୀ)** in Odia with examples and IDE setup:  

---

### **ଅଧ୍ୟାୟ 2: ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ ପାଇଁ Python (Python for Data Handling)**  
#### **ଭାଗ 1: ଲିଷ୍ଟ ଏବଂ ଡିକ୍ସନାରୀ (Lists & Dictionaries)**  

---

### **ପ୍ରୟୋଜନୀୟ ସାମଗ୍ରୀ**  
- **IDE:** VS Code, Jupyter Notebook, କିମ୍ବା PyCharm ବ୍ୟବହାର କରନ୍ତୁ।  
- **ଲାଇବ୍ରେରୀ ଇନ୍ସ୍ଟଲେସନ୍:**  
  ```bash  
  pip install numpy pandas  
  ```  

---

### **1. ଲିଷ୍ଟ (Lists)**  
ଲିଷ୍ଟ ହେଉଛି Python ର ଏକ ordered ଡାଟା ସ୍ଟ୍ରକ୍ଚର୍ ଯାହା ଏକାଧିକ ଡାଟା ଷ୍ଟୋର୍ କରିପାରିବ।  

**ଉଦାହରଣ 1:** ସରଳ ଲିଷ୍ଟ  
```python  
ଫଳ = ["ଆମ୍ବ", "କଦଳୀ", "ପେଣ୍ଡୁ"]  
print(ଫଳ)  # Output: ['ଆମ୍ବ', 'କଦଳୀ', 'ପେଣ୍ଡୁ']  
```  

**ଉଦାହରଣ 2:** ଲିଷ୍ଟ ମେଥଡ୍ (append, remove)  
```python  
ଫଳ.append("ନାରିଙ୍ଗା")  # ଯୋଡନ୍ତୁ  
print(ଫଳ)  # ['ଆମ୍ବ', 'କଦଳୀ', 'ପେଣ୍ଡୁ', 'ନାରିଙ୍ଗା']  

ଫଳ.remove("କଦଳୀ")  # ବାହାର କରନ୍ତୁ  
print(ଫଳ)  # ['ଆମ୍ବ', 'ପେଣ୍ଡୁ', 'ନାରିଙ୍ଗା']  
```  

**ଉଦାହରଣ 3:** ସ୍ଲାଇସିଂ (Slicing)  
```python  
ସଂଖ୍ୟା = [10, 20, 30, 40, 50]  
print(ସଂଖ୍ୟା[1:3])  # Output: [20, 30]  
```  

---

### **2. ଡିକ୍ସନାରୀ (Dictionaries)**  
ଡିକ୍ସନାରୀ ହେଉଛି key-value ଜୋଡିରେ ଡାଟା ଷ୍ଟୋର୍ କରିବାର ଏକ ଉପାୟ।  

**ଉଦାହରଣ 4:** ସରଳ ଡିକ୍ସନାରୀ  
```python  
ଛାତ୍ର = {"ନାମ": "ସୂର୍ଯ୍ୟ", "କ୍ଲାସ୍": 10, "ଗ୍ରାମ": "ଭୁବନେଶ୍ୱର"}  
print(ଛାତ୍ର["ନାମ"])  # Output: ସୂର୍ଯ୍ୟ  
```  

**ଉଦାହରଣ 5:** ଡିକ୍ସନାରୀ ମେଥଡ୍ (keys, values)  
```python  
print(ଛାତ୍ର.keys())   # Output: dict_keys(['ନାମ', 'କ୍ଲାସ୍', 'ଗ୍ରାମ'])  
print(ଛାତ୍ର.values()) # Output: dict_values(['ସୂର୍ଯ୍ୟ', 10, 'ଭୁବନେଶ୍ୱର'])  
```  

**ଉଦାହରଣ 6:** ଡିକ୍ସନାରୀ ଅପଡେଟ୍  
```python  
ଛାତ୍ର["ମାର୍କ"] = 95  # ନୂଆ ଡାଟା ଯୋଡନ୍ତୁ  
print(ଛାତ୍ର)  # Output: {'ନାମ': 'ସୂର୍ଯ୍ୟ', ..., 'ମାର୍କ': 95}  
```  

---

### **ସାରାଂଶ ଏବଂ ଅଭ୍ୟାସ**  
- **ଲିଷ୍ଟ:** ଡାଟା ସଂଗ୍ରହ ପାଇଁ (ordered, mutable)।  
- **ଡିକ୍ସନାରୀ:** Key-value ଡାଟା ପାଇଁ (fast lookup)।  
- **ଅଭ୍ୟାସ:**  
  1. ଏକ ଲିଷ୍ଟ ତିଆରି କରି ସେଥିରେ 5ଟି ସଂଖ୍ୟାର ଗଣିତିକ ହାରାହାରି କାଢନ୍ତୁ।  
  2. ଏକ ଡିକ୍ସନାରୀ ବ୍ୟବହାର କରି 3ଟି ଉତ୍ପାଦର ନାମ ଏବଂ ମୂଲ୍ୟ ଷ୍ଟୋର୍ କରନ୍ତୁ।  

**ଆଗାମୀ ଭାଗ:** ଫାଇଲ୍ ହ୍ୟାଣ୍ଡଲିଂ (File Handling) ଏବଂ CSV/JSON ଡାଟା ପଢିବା!  

--- 

ଏହି ଭାଗରେ ଆପଣ ଲିଷ୍ଟ ଏବଂ ଡିକ୍ସନାରୀର ମୂଳ ବ୍ୟବହାର ଶିଖିଲେ। ପ୍ରତ୍ୟେକ ଉଦାହରଣକୁ IDE ରେ ଟେଷ୍ଟ କରନ୍ତୁ!

Here’s **Part 2 of Chapter 2** (ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ ପାଇଁ Python) focused on **File Handling and CSV/JSON**, written in Odia:

---

### **ଅଧ୍ୟାୟ 2: ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ ପାଇଁ Python**  
#### **ଭାଗ 2: ଫାଇଲ୍ ହ୍ୟାଣ୍ଡଲିଂ ଏବଂ CSV/JSON**  

---

### **1. ଫାଇଲ୍ ହ୍ୟାଣ୍ଡଲିଂ (File Handling)**  
Python ରେ ଫାଇଲ୍ ପଢିବା/ଲେଖିବା ପାଇଁ `open()` ଫଙ୍କସନ୍ ବ୍ୟବହାର କରାଯାଏ।  

**ମୋଡ୍ (Modes):**  
- `"r"` → ପଢିବା (Read)  
- `"w"` → ଲେଖିବା (Write/Overwrite)  
- `"a"` → ଯୋଡିବା (Append)  

**ଉଦାହରଣ 1:** ଫାଇଲ୍ ଲେଖିବା  
```python  
# ଫାଇଲ୍ ତିଆରି କରି ଲେଖନ୍ତୁ  
with open("ଡାଟା.txt", "w", encoding="utf-8") as ଫାଇଲ୍:  
    ଫାଇଲ୍.write("ପ୍ରଥମ ଲାଇନ୍\n")  
    ଫାଇଲ୍.write("ଦ୍ଵିତୀୟ ଲାଇନ୍")  
```  

**ଉଦାହରଣ 2:** ଫାଇଲ୍ ପଢିବା  
```python  
with open("ଡାଟା.txt", "r", encoding="utf-8") as ଫାଇଲ୍:  
    ବିଷୟବସ୍ତୁ = ଫାଇଲ୍.read()  
    print(ବିଷୟବସ୍ତୁ)  # Output: ପ୍ରଥମ ଲାଇନ୍\nଦ୍ଵିତୀୟ ଲାଇନ୍  
```  

---

### **2. CSV ଫାଇଲ୍ ପଢିବା/ଲେଖିବା**  
CSV (Comma-Separated Values) ଫାଇଲ୍ ପାଇଁ `csv` ଲାଇବ୍ରେରୀ ବ୍ୟବହାର କରନ୍ତୁ।  

**ଉଦାହରଣ 3:** CSV ଲେଖିବା  
```python  
import csv  

# ଡାଟା ତିଆରି  
ଡାଟା = [  
    ["ନାମ", "ବୟସ"],  
    ["ରମେଶ", 30],  
    ["ସୀତା", 25]  
]  

with open("ଛାତ୍ର.csv", "w", newline="", encoding="utf-8") as ଫାଇଲ୍:  
    ଲେଖକ = csv.writer(ଫାଇଲ୍)  
    ଲେଖକ.writerows(ଡାଟା)  
```  

**ଉଦାହରଣ 4:** CSV ପଢିବା  
```python  
with open("ଛାତ୍ର.csv", "r", encoding="utf-8") as ଫାଇଲ୍:  
    ପାଠକ = csv.reader(ଫାଇଲ୍)  
    for ଧାଡି in ପାଠକ:  
        print(ଧାଡି)  # Output: ['ନାମ', 'ବୟସ'], ['ରମେଶ', '30'], ...  
```  

---

### **3. JSON ଫାଇଲ୍ ପଢିବା/ଲେଖିବା**  
JSON (JavaScript Object Notation) ପାଇଁ `json` ଲାଇବ୍ରେରୀ ବ୍ୟବହାର କରନ୍ତୁ।  

**ଉଦାହରଣ 5:** JSON ଲେଖିବା  
```python  
import json  

ଛାତ୍ର = {  
    "ନାମ": "ପ୍ରିୟଂକା",  
    "ବିଭାଗ": "AI",  
    "ମାର୍କ": 92  
}  

with open("ଛାତ୍ର.json", "w", encoding="utf-8") as ଫାଇଲ୍:  
    json.dump(ଛାତ୍ର, ଫାଇଲ୍)  
```  

**ଉଦାହରଣ 6:** JSON ପଢିବା  
```python  
with open("ଛାତ୍ର.json", "r", encoding="utf-8") as ଫାଇଲ୍:  
    ଡାଟା = json.load(ଫାଇଲ୍)  
    print(ଡାଟା["ନାମ"])  # Output: ପ୍ରିୟଂକା  
```  

---

### **ସାରାଂଶ ଏବଂ ଅଭ୍ୟାସ**  
- **ଫାଇଲ୍ ହ୍ୟାଣ୍ଡଲିଂ:** `open()`, `read()`, `write()`, ଏବଂ `with` ଷ୍ଟେଟମେଣ୍ଟ୍।  
- **CSV/JSON:** Structured ଡାଟା ପାଇଁ ଉପଯୁକ୍ତ।  
- **ଅଭ୍ୟାସ:**  
  1. ଏକ CSV ଫାଇଲ୍ ତିଆରି କରନ୍ତୁ ଯାହାରେ 5 ଜଣ ଛାତ୍ରର ନାମ ଏବଂ ରୋଲ୍ ନମ୍ବର ଅଛି।  
  2. JSON ଫାଇଲ୍ ବ୍ୟବହାର କରି ଗୋଟିଏ ଉତ୍ପାଦର ବିବରଣୀ (ନାମ, ମୂଲ୍ୟ, ପରିମାଣ) ଷ୍ଟୋର୍ କରନ୍ତୁ।  

**ଆଗାମୀ ଭାଗ:** NumPy ଏବଂ Pandas ଲାଇବ୍ରେରୀରେ ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ!  

--- 

ଫାଇଲ୍ ଏବଂ structured ଡାଟା (CSV/JSON) ସହିତ କାମ କରିବାର ମୂଳ କଣ୍ସେପ୍ଟ୍ ଏହି ଭାଗରେ ଆଚ୍ଛାଦିତ ହେଲା। ଅଭ୍ୟାସ କରନ୍ତୁ!

Here’s **Part 3 of Chapter 2** (ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ ପାଇଁ Python) focused on **NumPy and Pandas**, written in Odia with practical examples:

---

### **ଅଧ୍ୟାୟ 2: ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ ପାଇଁ Python**  
#### **ଭାଗ 3: NumPy ଏବଂ Pandas ରେ ଡାଟା ହ୍ୟାଣ୍ଡଲିଂ**  

---

### **1. NumPy: Numerical Python**  
NumPy ହେଉଛି ବୃହତ୍ ସଂଖ୍ୟାତ୍ମକ ଡାଟା ପାଇଁ ଏକ ଶକ୍ତିଶାଳୀ ଲାଇବ୍ରେରୀ।  

**ଇନ୍ସ୍ଟଲେସନ୍:**  
```bash  
pip install numpy  
```  

**ଉଦାହରଣ 1:** NumPy ଆରେ (Array) ତିଆରି  
```python  
import numpy as np  

ସଂଖ୍ୟା = np.array([10, 20, 30, 40])  
print(ସଂଖ୍ୟା)  # Output: [10 20 30 40]  
print(ସଂଖ୍ୟା.shape)  # Output: (4,) → 4 ଟି ଏଲିମେଣ୍ଟ୍  
```  

**ଉଦାହରଣ 2:** ଗଣିତିକ କାର୍ଯ୍ୟ  
```python  
ଯୋଗଫଳ = ସଂଖ୍ୟା + 5  # ପ୍ରତ୍ୟେକ ଏଲିମେଣ୍ଟ୍ + 5  
print(ଯୋଗଫଳ)  # [15 25 35 45]  

ହାରାହାରି = np.mean(ସଂଖ୍ୟା)  
print(f"ହାରାହାରି: {ହାରାହାରି}")  # Output: 25.0  
```  

---

### **2. Pandas: ଡାଟା ଫ୍ରେମ୍ ଏବଂ ସିରିଜ୍**  
Pandas ହେଉଛି ଟେବୁଲାର୍ ଡାଟା (ଯେପରି Excel) ପାଇଁ ଉତ୍ତମ ଟୁଲ୍।  

**ଇନ୍ସ୍ଟଲେସନ୍:**  
```bash  
pip install pandas  
```  

**ଉଦାହରଣ 3:** DataFrame ତିଆରି  
```python  
import pandas as pd  

ଡାଟା = {  
    "ନାମ": ["ଅନୁ", "ରଜତ", "ପ୍ରିୟା"],  
    "ମାର୍କ": [85, 92, 78]  
}  
ଡିଏଫ୍ = pd.DataFrame(ଡାଟା)  
print(ଡିଏଫ୍)  
```  
**Output:**  
```  
   ନାମ  ମାର୍କ  
0  ଅନୁ    85  
1  ରଜତ   92  
2  ପ୍ରିୟା  78  
```  

**ଉଦାହରଣ 4:** CSV ରୁ ଡାଟା ପଢିବା  
```python  
ଡିଏଫ୍ = pd.read_csv("ଛାତ୍ର.csv")  
print(ଡିଏଫ୍.head())  # ପ୍ରଥମ 5 ଧାଡି ଦେଖାଇବ  
```  

**ଉଦାହରଣ 5:** ଫିଲ୍ଟରିଂ ଡାଟା  
```python  
ଉଚ୍ଚମାର୍କ = ଡିଏଫ୍[ଡିଏଫ୍.ମାର୍କ > 90]  
print(ଉଚ୍ଚମାର୍କ)  # ମାର୍କ > 90 ଥିବା ଛାତ୍ର  
```  

---

### **3. ସରଳ ଡାଟା ବିଶ୍ଳେଷଣ (Data Analysis)**  
**ଉଦାହରଣ 6:** ଗୋଠିକୃତ ଡାଟା (GroupBy)  
```python  
ବିଭାଗ = {  
    "ନାମ": ["ଅନୁ", "ରଜତ", "ପ୍ରିୟା"],  
    "ବିଭାଗ": ["AI", "AI", "ML"]  
}  
ବିଭାଗ_ଡିଏଫ୍ = pd.DataFrame(ବିଭାଗ)  

ଗୋଠ = ବିଭାଗ_ଡିଏଫ୍.groupby("ବିଭାଗ").count()  
print(ଗୋଠ)  # ପ୍ରତ୍ୟେକ ବିଭାଗରେ ଛାତ୍ର ସଂଖ୍ୟା  
```  

---

### **ସାରାଂଶ ଏବଂ ଅଭ୍ୟାସ**  
- **NumPy:** ବୃହତ୍ ସଂଖ୍ୟାତ୍ମକ ଡାଟା ପାଇଁ ଏରେ ଏବଂ ମେଥଡ୍।  
- **Pandas:** ଟେବୁଲାର୍ ଡାଟା ପାଇଁ DataFrame ଏବଂ ବିଶ୍ଳେଷଣ।  
- **ଅଭ୍ୟାସ:**  
  1. NumPy ବ୍ୟବହାର କରି 1ରୁ 10 ପର୍ଯ୍ୟନ୍ତ ସଂଖ୍ୟାର ବର୍ଗମୂଳ କାଢନ୍ତୁ।  
  2. Pandas ରେ ଏକ CSV ଫାଇଲ୍ ପଢି ସର୍ବୋଚ୍ଚ ମାର୍କ ଥିବା ଛାତ୍ରର ନାମ ପ୍ରିଣ୍ଟ୍ କରନ୍ତୁ।  

**ଆଗାମୀ ଅଧ୍ୟାୟ:** AI ଏବଂ ML ର ମୂଳ ତତ୍ତ୍ୱ (Introduction to AI/ML)!  

--- 

ଏହି ଭାଗରେ ଆପଣ NumPy ଏବଂ Pandas ଲାଇବ୍ରେରୀ ମାଧ୍ୟମରେ ଡାଟା ବିଶ୍ଳେଷଣ ଶିଖିଲେ। ପ୍ରୟୋଗ କରନ୍ତୁ ଏବଂ ପ୍ରଶ୍ନ ଥିଲେ ପଚାନ୍ତୁ! 😊



---

### **ଅଧ୍ୟାୟ 3: AI ଏବଂ ML ର ପରିଚୟ**  
#### **ଭାଗ 1: ମୂଳ ତତ୍ତ୍ୱ ଏବଂ ପ୍ରକାରଭେଦ**  

---

### **ଲକ୍ଷ୍ୟ (Objectives)**  
1. AI ଏବଂ ML ର ସ୍ୱଭାବ ବୁଝିବା।  
2. ସୁପରଭାଇଜଡ୍ ଏବଂ ଅନସୁପରଭାଇଜଡ୍ ଲର୍ନିଂ ର ପାର୍ଥକ୍ୟ।  

---

### **1. AI କଣ? (What is AI?)**  
**କୃତ୍ରିମ ବୁଦ୍ଧିମତା (Artificial Intelligence)** ହେଉଛି ଯେ କୋଣସି ସିଷ୍ଟମ୍ ଯାହା ମନୁଷ୍ୟ ପରି ଚିନ୍ତା, ଶିଖିବା, ଏବଂ ସମସ୍ୟା ସମାଧାନ କରିପାରିବ।  

**ଉଦାହରଣ:**  
- ଚାଟବୋଟ୍ (ChatGPT) ➞ ପ୍ରଶ୍ନର ଉତ୍ତର ଦେବା।  
- ସ୍ୱୟଂଚାଳିତ ଗାଡି ➞ ରାସ୍ତା ଚିହ୍ନଟ କରିବା।  

---

### **2. ML: AI ର ଏକ ଉପାଦାନ (ML as a Subset of AI)**  
**ମେସିନ୍ ଲର୍ନିଂ (Machine Learning)** ହେଉଛି AI ର ଏକ ଶାଖା ଯେଉଁଥିରେ ମେସିନ୍ ଗୁଡାଟା ଡାଟା ଉପରେ ନିର୍ଭର କରି ସ୍ୱୟଂ ଶିଖିଥାଏ।  

**ଆଲଗା କରନ୍ତୁ (AI vs ML vs Deep Learning):**  
```  
AI (ସମ୍ପୂର୍ଣ୍ଣ)  
└─ ML (ଡାଟା ଉପରେ ଶିଖେ)  
   └─ Deep Learning (ନ୍ୟୁରାଲ୍ ନେଟ୍ୱର୍କ୍ ବ୍ୟବହାର କରେ)  
```  

---

### **3. ମେସିନ୍ ଲର୍ନିଂ ର ପ୍ରକାରଭେଦ (Types of ML)**  
1. **ସୁପରଭାଇଜଡ୍ ଲର୍ନିଂ (Supervised Learning):**  
   - **ଲେବଲ୍ ଯୁକ୍ତ ଡାଟା** ସହିତ ଶିଖେ (ଯେପରି: ଫଟୋରେ ବସ୍/କାର୍ ଚିହ୍ନଟ)।  
   - *ଉଦାହରଣ:* ଘର ମୂଲ୍ୟ ଆକଳନ (Input: ଘରର ସାଇଜ୍ → Output: ମୂଲ୍ୟ)।  

2. **ଅନସୁପରଭାଇଜଡ୍ ଲର୍ନିଂ (Unsupervised Learning):**  
   - **ଲେବଲ୍ ବିହୀନ ଡାଟା**ରେ ପ୍ୟାଟର୍ନ୍ ଖୋଜେ (ଯେପରି: ଗ୍ରାହକଙ୍କୁ ଗୋଷ୍ଠୀକରଣ)।  
   - *ଉଦାହରଣ:* ଗ୍ରାହକଙ୍କ କ୍ରୟ ଇତିହାସ ଅନୁଯାୟୀ ଗୋଷ୍ଠୀ ତିଆରି।  

3. **ରିଇନଫୋର୍ସମେଣ୍ଟ ଲର୍ନିଂ (Reinforcement Learning):**  
   - **ପୁରସ୍କାର/ଦଣ୍ଡ** ମାଧ୍ୟମରେ ଶିଖେ (ଯେପରି: ରୋବୋଟ୍ ଚଲାଇବା)।  

---

### **4. ପ୍ରାକୃତିକ ଉଦାହରଣ (Real-World Analogy)**  
**ସୁପରଭାଇଜଡ୍ ଲର୍ନିଂ:**  
- ଏକ ପିଲା ଚିତ୍ର ବୁଝିବା (ପିତାମାତା ଠିକ୍ କରନ୍ତି → "ଏହା କୁକୁର, ଏହା ବିଲେଇ")।  

**ଅନସୁପରଭାଇଜଡ୍:**  
- ପିଲା ନୂଆ ଖେଳନା ସଜାଡ଼ିବା (କୌଣସି ମାର୍ଗଦର୍ଶନ ନାହିଁ → ସେ ନିଜେ ଶ୍ରେଣୀ ତିଆରି କରେ)।  

---

### **5. ପ୍ରାକ୍ଟିକାଲ୍ ସେଟଅପ୍ (Setup for ML)**  
**ଲାଇବ୍ରେରୀ ଇନ୍ସ୍ଟଲ୍:**  
```bash  
pip install scikit-learn  
```  

**ଉଦାହରଣ (ସୁପରଭାଇଜଡ୍ ଲର୍ନିଂ):**  
```python  
from sklearn.linear_model import LinearRegression  

# ଡାଟା: ଅନୁଭୂତି (ବର୍ଷ) vs ଦରମା (ଲକ୍ଷ)  
X = [[1], [2], [3], [4]]  # ଇନପୁଟ୍  
y = [2, 4, 6, 8]          # ଆଉଟପୁଟ୍  

# ମଡେଲ୍ ତିଆରି  
ମଡେଲ୍ = LinearRegression()  
ମଡେଲ୍.fit(X, y)  

# ଆକଳନ  
ପ୍ରତିକ୍ରିୟା = ମଡେଲ୍.predict([[5]])  
print(f"5 ବର୍ଷ ଅନୁଭୂତିରେ ଦରମା: {ପ୍ରତିକ୍ରିୟା[0]:.2f} ଲକ୍ଷ")  
# Output: 10.00 ଲକ୍ଷ  
```  

---

### **ସାରାଂଶ ଏବଂ ଅଭ୍ୟାସ**  
- **AI:** ମନୁଷ୍ୟ ପରି ବ୍ୟବହାର କରୁଥିବା ସିଷ୍ଟମ୍।  
- **ML:** ଡାଟା ଉପରେ ନିର୍ଭର କରି ସ୍ୱୟଂ ଶିଖିବା।  
- **ଅଭ୍ୟାସ:**  
  1. ସୁପରଭାଇଜଡ୍ ଏବଂ ଅନସୁପରଭାଇଜଡ୍ ଲର୍ନିଂ ର 2ଟି ଲେଖାଏଁ ବାସ୍ତବ ଉଦାହରଣ ଲେଖନ୍ତୁ।  
  2. ଉପରେ ଥିବା କୋଡ୍ ରେ X = [[5], [6], [7]] ଦେଇ ପ୍ରିଡିକ୍ସନ୍ କରନ୍ତୁ।  

**ଆଗାମୀ ଭାଗ:** ML ର workflow (ଡାଟା ପ୍ରିପ୍ରୋସେସିଂ, ମଡେଲ୍ ଇଭାଲ୍ୟୁଏସନ୍) ଏବଂ ଆଲଗୋରିଦମ୍ ର ପରିଚୟ!  

--- 

ଏହି ଭାଗରେ ଆପଣ AI/ML ର ମୂଳ ତତ୍ତ୍ୱ ସହିତ ପରିଚିତ ହୋଇଛନ୍ତି। କୋଡ୍ ଟି ରନ୍ କରି ଫଳାଫଳ ଦେଖନ୍ତୁ! 🚀

### **Chapter 4: AI ପାଇଁ ଗଣିତ (Mathematics for AI)**  
#### **Part 1: Vectors, Matrices, and Linear Algebra Basics**  

---

### **Objectives**  
1. ଭେକ୍ଟର୍ ଏବଂ ମ୍ୟାଟ୍ରିକ୍ସ୍ ର ମୂଳ ଧାରଣା ବୁଝିବା।  
2. ଲିନିୟର୍ ଆଲଜେବ୍ରାର ପ୍ରୟୋଗ AI ରେ କିପରି ହୁଏ ତାହା ଜାଣିବା।  

---

### **1. ଲିନିୟର୍ ଆଲଜେବ୍ରା ର ଆବଶ୍ୟକତା**  
AI ରେ ଡାଟା ଏବଂ ମଡେଲ୍ ଗୁଡିକୁ ଗାଣିତିକ ସ୍ଵରୂପରେ ପ୍ରସ୍ତୁତ କରାଯାଏ।  
- **ଉଦାହରଣ:** ଇମେଜ୍ ରେ ଥିବା ପିକ୍ସେଲ୍ ଗୁଡିକୁ ଭେକ୍ଟର୍ ଭାବେ ରିପ୍ରେଜେଣ୍ଟ୍ କରାଯାଇପାରେ।  
- **ଆବଶ୍ୟକ ଲାଇବ୍ରେରୀ:** `numpy`  

**Installation:**  
```bash  
pip install numpy  
```  

---

### **2. Vectors (ଭେକ୍ଟର୍)**  
**ଭେକ୍ଟର୍** ହେଉଛି ଏକାଧିକ ସଂଖ୍ୟାର ସଜାଣି, ଯାହାକି ଡାଟା ପଏଣ୍ଟ୍ (ଯେପରି ଫିଚର୍ ଭ୍ୟାଲୁ) ରିପ୍ରେଜେଣ୍ଟ୍ କରେ।  

**ଉଦାହରଣ 1:** ଭେକ୍ଟର୍ ତିଆରି  
```python  
import numpy as np  

# 1D ଭେକ୍ଟର୍ (ସରଳ ସାଲା)  
ଭେକ୍ଟର୍ = np.array([2, 5, 7])  
print(ଭେକ୍ଟର୍)  # Output: [2 5 7]  
```  

**ଭେକ୍ଟର୍ ଅପରେସନ୍:**  
- **ଯୋଗ (Addition):**  
  ```python  
  v1 = np.array([1, 2])  
  v2 = np.array([3, 4])  
  print(v1 + v2)  # Output: [4 6]  
  ```  
- **ଡଟ୍ ପ୍ରଡକ୍ଟ (Dot Product):**  
  ```python  
  ଡଟ୍_ଫଳ = np.dot(v1, v2)  
  print(ଡଟ୍_ଫଳ)  # Output: 11 (1*3 + 2*4)  
  ```  

---

### **3. Matrices (ମ୍ୟାଟ୍ରିକ୍ସ୍)**  
**ମ୍ୟାଟ୍ରିକ୍ସ୍** ହେଉଛି 2D ସାରଣୀ ଯାହା ଡାଟା ସେଟ୍ (ଯେପରି ଇମେଜ୍, ଟେବୁଲାର୍ ଡାଟା) ରିପ୍ରେଜେଣ୍ଟ୍ କରେ।  

**ଉଦାହରଣ 2:** ମ୍ୟାଟ୍ରିକ୍ସ୍ ତିଆରି  
```python  
ମ୍ୟାଟ୍ରିକ୍ସ୍ = np.array([[1, 2], [3, 4]])  
print(ମ୍ୟାଟ୍ରିକ୍ସ୍)  
# Output:  
# [[1 2]  
#  [3 4]]  
```  

**ମ୍ୟାଟ୍ରିକ୍ସ୍ ଅପରେସନ୍:**  
- **ମ୍ୟାଟ୍ରିକ୍ସ୍ ଗୁଣନ (Matrix Multiplication):**  
  ```python  
  m1 = np.array([[1, 2], [3, 4]])  
  m2 = np.array([[5, 6], [7, 8]])  
  ଫଳ = np.matmul(m1, m2)  
  print(ଫଳ)  
  # Output:  
  # [[19 22]  
  #  [43 50]]  
  ```  
- **ଟ୍ରାନ୍ସପୋଜ୍ (Transpose):**  
  ```python  
  print(m1.T)  # [[1 3], [2 4]]  
  ```  

---

### **4. ବାସ୍ତବ ପ୍ରୟୋଗ (Real-World Application)**  
**ଇମେଜ୍ ପ୍ରୋସେସିଂରେ ମ୍ୟାଟ୍ରିକ୍ସ୍:**  
- ଏକ ଧୂସର ଇମେଜ୍ (grayscale) ଏକ 2D ମ୍ୟାଟ୍ରିକ୍ସ୍ ଭାବେ ରିପ୍ରେଜେଣ୍ଟେଡ୍ ହୁଏ, ଯେଉଁଥିରେ ପ୍ରତ୍ୟେକ ସେଲ୍ ର ଭ୍ୟାଲୁ 0 (କଳା) ରୁ 255 (ଧଳା) ମଧ୍ୟରେ ଥାଏ।  

**ଉଦାହରଣ 3:** ଇମେଜ୍ ମ୍ୟାଟ୍ରିକ୍ସ୍  
```python  
# 3x3 ଇମେଜ୍ (ଧୂସର)  
ଇମେଜ୍ = np.array([  
    [100, 150, 200],  
    [50, 180, 90],  
    [30, 220, 255]  
])  
print("ଇମେଜ୍ ମ୍ୟାଟ୍ରିକ୍ସ୍:\n", ଇମେଜ୍)  
```  

---

### **5. ସାରାଂଶ ଏବଂ ଅଭ୍ୟାସ**  
- **ଭେକ୍ଟର୍:** 1D ଡାଟା, **ମ୍ୟାଟ୍ରିକ୍ସ୍:** 2D ଡାଟା।  
- **ମୂଳ ଅପରେସନ୍:** ଯୋଗ, ଗୁଣନ, ଟ୍ରାନ୍ସପୋଜ୍।  
- **ଅଭ୍ୟାସ:**  
  1. ଦୁଇଟି 3D ଭେକ୍ଟର୍ ତିଆରି କରି ସେମାନଙ୍କର ଡଟ୍ ପ୍ରଡକ୍ଟ୍ କାଢନ୍ତୁ।  
  2. ଏକ 2x2 ମ୍ୟାଟ୍ରିକ୍ସ୍ ର ଇନଭର୍ସ୍ କାଢିବା ପାଇଁ `np.linalg.inv()` ବ୍ୟବହାର କରନ୍ତୁ।  

---

### **Next Part Preview**  
**Part 2:** Matrix Decomposition (Eigenvalues, SVD) and Applications in AI.  

--- 

This part establishes the foundation for representing data mathematically in AI. Practice these operations using NumPy to solidify your understanding!

Here’s **Part 2 of Chapter 4** (AI ପାଇଁ ଗଣିତ) focusing on **Matrix Decomposition and Its Applications in AI**, written in Odia with examples and practical implementations:

---

### **Chapter 4: AI ପାଇଁ ଗଣିତ**  
#### **Part 2: Matrix Decomposition (Eigenvalues, SVD) ଏବଂ ପ୍ରୟୋଗ**  

---

### **ଲକ୍ଷ୍ୟ (Objectives)**  
1. Eigenvalues ଏବଂ Singular Value Decomposition (SVD) ର ଧାରଣା ବୁଝିବା।  
2. AI ରେ ଏହି ପ୍ରଯୁକ୍ତି କିପରି ବ୍ୟବହୃତ ହୁଏ (ଯେପରି PCA, ଇମେଜ୍ କମ୍ପ୍ରେସନ୍)।  

---

### **1. Eigenvalues ଏବଂ Eigenvectors**  
**Eigenvalue (λ)** ଏବଂ **Eigenvector (v)** ହେଉଛନ୍ତି ମ୍ୟାଟ୍ରିକ୍ସ୍ ସହିତ ଜଡିତ ଏକ ଗାଣିତିକ ସମ୍ପର୍କ:  
\[ A \cdot v = \lambda \cdot v \]  
- **A:** ମ୍ୟାଟ୍ରିକ୍ସ୍  
- **v:** Eigenvector (ଅଣ-ଜିରୋ ଭେକ୍ଟର୍)  
- **λ:** Eigenvalue (ସ୍କେଲାର୍)  

**ଉଦାହରଣ 1:** Eigenvalues ଏବଂ Eigenvectors କାଢିବା (Using NumPy)  
```python  
import numpy as np  

A = np.array([[4, 2], [1, 3]])  
λ, v = np.linalg.eig(A)  

print("Eigenvalues:", λ)  # Output: [5., 2.]  
print("Eigenvectors:\n", v)  
# Output:  
# [[ 0.89442719 -0.70710678]  
#  [ 0.4472136   0.70710678]]  
```  

**ବ୍ୟାଖ୍ୟା:** Eigenvector ଗୁଡିକ ମ୍ୟାଟ୍ରିକ୍ସ୍ A ର ଦିଗ (direction) ଦର୍ଶାଏ, Eigenvalue ସେମାନଙ୍କର ମାପ (scaling factor) ଦର୍ଶାଏ।  

---

### **2. Singular Value Decomposition (SVD)**  
SVD ହେଉଛି ଯେ କୌଣସି ମ୍ୟାଟ୍ରିକ୍ସ୍ M କୁ ତିନୋଟି ମ୍ୟାଟ୍ରିକ୍ସ୍ ରେ ବିଭକ୍ତ କରାଯାଏ:  
\[ M = U \cdot \Sigma \cdot V^T \]  
- **U ଏବଂ V:** Orthogonal matrices (ଘୂର୍ଣ୍ଣନ ଏବଂ ପ୍ରତିଫଳନ ରିପ୍ରେଜେଣ୍ଟ୍ କରନ୍ତି)।  
- **Σ:** Diagonal matrix (singular values, σ₁ ≥ σ₂ ≥ ... ≥ 0)।  

**ଉଦାହରଣ 2:** SVD କାଢିବା  
```python  
M = np.array([[1, 2], [3, 4], [5, 6]])  
U, Σ, VT = np.linalg.svd(M)  

print("U:\n", U)  
print("Singular Values:", Σ)  # Output: [9.52551809 0.51430058]  
print("VT:\n", VT)  
```  

---

### **3. AI ରେ ପ୍ରୟୋଗ (Applications in AI)**  
#### **କ) Principal Component Analysis (PCA)**  
- **ଲକ୍ଷ୍ୟ:** ଡାଟାର ଡାଇମେନ୍ସନ୍ କମ୍ କରିବା (dimensionality reduction)।  
- **ପଦ୍ଧତି:** Eigenvalues ଏବଂ Eigenvectors ବ୍ୟବହାର କରି ଡାଟାର ମୁଖ୍ୟ ଦିଗ (principal components) ଚିହ୍ନଟ କରାଯାଏ।  

**ଉଦାହରଣ 3:** PCA ଇମ୍ପ୍ଲିମେଣ୍ଟେସନ୍  
```python  
from sklearn.decomposition import PCA  

# ଡାଟା: 3D ଡାଟା ପଏଣ୍ଟ୍  
X = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])  

# 2D ରେ କମ୍ କରନ୍ତୁ  
pca = PCA(n_components=2)  
X_2D = pca.fit_transform(X)  
print("2D ଡାଟା:\n", X_2D)  
```  

#### **ଖ) ଇମେଜ୍ କମ୍ପ୍ରେସନ୍ (SVD ବ୍ୟବହାରରେ)**  
- SVD ର singular values ରେ ଛୋଟ ମୂଲ୍ୟଗୁଡିକୁ ଉପେକ୍ଷା କରି ଇମେଜ୍ ସାଇଜ୍ କମ୍ କରାଯାଏ।  

**ଉଦାହରଣ 4:** ଇମେଜ୍ କମ୍ପ୍ରେସନ୍  
```python  
# ଇମେଜ୍ ମ୍ୟାଟ୍ରିକ୍ସ୍ (ଧୂସର)  
ଇମେଜ୍ = np.array([[100, 150, 200], [50, 180, 90], [30, 220, 255]])  

# SVD କରନ୍ତୁ  
U, Σ, VT = np.linalg.svd(ଇମେଜ୍)  

# କେବଳ ପ୍ରଥମ k singular values ରଖନ୍ତୁ  
k = 1  
Σ_k = np.diag(Σ[:k])  
U_k = U[:, :k]  
VT_k = VT[:k, :]  

# କମ୍ପ୍ରେସଡ୍ ଇମେଜ୍ ତିଆରି  
କମ୍ପ୍ରେସଡ୍_ଇମେଜ୍ = U_k @ Σ_k @ VT_k  
print("କମ୍ପ୍ରେସଡ୍ ଇମେଜ୍:\n", କମ୍ପ୍ରେସଡ୍_ଇମେଜ୍.astype(int))  
```  

---

### **4. ସାରାଂଶ ଏବଂ ଅଭ୍ୟାସ**  
- **Eigenvalues/Eigenvectors:** ମ୍ୟାଟ୍ରିକ୍ସ୍ ର ମୌଳିକ ଗୁଣ ଦର୍ଶାନ୍ତି।  
- **SVD:** ଡାଟାକୁ ସରଳ ଭାଗରେ ବିଭକ୍ତ କରି AI ରେ କମ୍ପ୍ରେସନ୍/ଫିଚର୍ ଏକ୍ସଟ୍ରାକ୍ସନ୍ ପାଇଁ ବ୍ୟବହାର।  
- **ଅଭ୍ୟାସ:**  
  1. ଏକ 2x2 ମ୍ୟାଟ୍ରିକ୍ସ୍ ର Eigenvalues କାଢନ୍ତୁ ଏବଂ PCA ପ୍ରୟୋଗ କରନ୍ତୁ।  
  2. SVD ବ୍ୟବହାର କରି ଏକ 4x4 ମ୍ୟାଟ୍ରିକ୍ସ୍ ର କମ୍ପ୍ରେସନ୍ କରନ୍ତୁ (k=2)।  

---

### **Next Part Preview**  
**Part 3:** Probability Basics (ସମ୍ଭାବ୍ୟତା ର ମୂଳ ତତ୍ତ୍ୱ) ଏବଂ Bayes' Theorem ର ଆବଶ୍ୟକତା AI ରେ।  

--- 

This part equips you with matrix decomposition techniques critical for AI algorithms like PCA and data compression. Practice these methods to grasp their power in simplifying complex data! 🧠🔍
