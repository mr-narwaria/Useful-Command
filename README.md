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
1. See the list of pip packages in the virtual environment
```bash
pip list
```
2. Create requirements.txt file
```bash
pip freeze > requirements.txt
```

### 4. Install-Package from requirements.txt file
```bash
pip install -r requirements.txt
```
### 5. Forced delete any file that is not deleted normally
Open CMD as Admistrations and use the command
```bash
del /f 'location of file'
```
eg. C:\Windows\System32><b>del /f C:\Users\Sham\Desktop\lab1<b>

<br>
mailed me for updations
> narwaria242ss@gmail.com
