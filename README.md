# pytest-in-action
"Learn pytest by doing – from basics to best practices."

# Overview

A hands-on learning repository for mastering the **pytest** framework.  
This repo contains simple to advanced examples, best practices, and real-world test cases to help you write efficient, maintainable, and reliable Python tests.

---

## 📌 Objectives
- Learn the basics of pytest.
- Understand test discovery and execution.
- Explore fixtures, parameters, and mocking.
- Apply best practices for clean and maintainable tests.
- Gain experience with code coverage and CI integration.

---

## 📂 Repository Structure

```
pytest-in-action/
│
├── src/pytest-in-action/ # Example Python code to test
├── tests/ # Pytest test cases
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```


## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/pytest-in-action.git
cd pytest-in-action
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # For Mac/Linux
venv\Scripts\activate      # For Windows
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

## 🧪 Running Tests
Run all tests:
```bash
pytest
```
Run tests with verbose output:
```bash
pytest -v
```
Run tests with coverage:
```bash
pytest --cov=src --cov-report=term-missing
```
Run tests with coverage and verbose:
```bash
pytest -v --cov=src --cov-report=term-missing
```
Run a specific test file:
```bash
pytest tests/test_example.py
```

## 📚 Topics Covered
- Writing your first test

- Using assertions effectively

- Organizing tests

- Working with fixtures

- Parameterizing tests

- Mocking dependencies

- Measuring code coverage

- Integrating
