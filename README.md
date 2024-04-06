# Useful-Command
This is rapo for different commands required during software projects, Linux, and web development.

### 1. Find where Python is installed on Windows.
```bash
python -c "import os, sys; print(os.path.dirname(sys.executable))"
```

### 2. Create a Virtual Environment for Development with Python
1. install virtualenv
```bash
pip install virtualenv
```
2. Create a virtual environment named venv:
```bash
virtualenv venv
```
3. Activate Virtual env
```bash
venv\Scripts\activate
```
4. For Deactivate
```bash
deactivate
```

### 3. Create requirements.txt file
```bash
pip freeze > requirements.txt
```

### 4. Install-Package from requirements.txt file
```bash
pip install -r requirements.txt
```
