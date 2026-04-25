# Machine Learning and Finance Group Project 

### Group Reference for installing venv (*remove this later*)

## 1. On your original device

Activate your venv and export dependencies:
```
pip freeze > requirements.txt
```
Commit `requirements.txt` to your repo.

## 2. On the new device (after cloning repo)

### Create a new virtual environment:
```
python-m venv venv
```

### Activate it:
- macOS/Linux:
    
    ```
    source venv/bin/activate
   ```    
- Windows:
    
    ```
    venv\Scripts\activate
    ```

### Install dependencies:
```
pip install-r requirements.txt
```

# ⚠️ Important tips

### 🔹 Match Python version

Make sure both machines use the **same Python version**:
```
python--version
```

### 🔹 Don’t commit venv

Your repo should include a `.gitignore` like:
