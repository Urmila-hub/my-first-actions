# 🚀 Python CI Pipeline using GitHub Actions

## 📌 Project Overview
This project demonstrates how to build a Continuous Integration (CI) pipeline using GitHub Actions for a Python application.

The pipeline automatically runs tests whenever code is pushed to the repository, ensuring code quality and correctness.

---

## ⚙️ Features
- Automated CI pipeline using GitHub Actions  
- Runs on every code push  
- Python environment setup in CI  
- Unit testing using pytest  
- Clear project structure using `src/` and `tests/`  

---

## 🛠️ Tech Stack
- Python  
- Pytest  
- GitHub Actions (CI/CD)  

---


## 📁 Project Structure
```
python-ci-cd-pipeline/
│
├── src/
│   └── addition.py
│
├── tests/
│   └── test_addition.py
│
├── .github/
│   └── workflows/
│       └── python_ci.yml
│
└── README.md
```
---

## 🔄 Workflow Explanation
1. Developer pushes code to repository  
2. GitHub Actions workflow is triggered  
3. Ubuntu runner is created  
4. Python environment is set up  
5. Dependencies are installed  
6. Tests are executed using pytest  
7. Results are displayed in Actions tab  

---

## ▶️ How It Works
### Sample Function
```python
def add(a, b):
    return a + b
```        

### Sample Tests
```python
def test_add_case1():
    assert add(2, 3) == 5

def test_add_case2():
    assert add(3, 3) == 6
```
---

## 📊 Output (CI Result)
collected 2 items  
2 passed  

✔ All tests pass successfully in the CI pipeline.

---

## 🧠 Key Learnings
Writing GitHub Actions workflows using YAML
Understanding CI/CD concepts
Debugging YAML syntax errors
Fixing Python import issues using PYTHONPATH
Structuring Python projects for testing

---

## 🚀 Future Improvements
Run tests on multiple Python versions
Add requirements.txt for dependencies
Add deployment step

---

## 👩‍💻 Author
URMILA BHAURAO
