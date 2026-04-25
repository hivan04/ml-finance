# Machine Learning and Finance Group Project 

### Group Reference for installing venv (*remove this later*) on codespace

## 1. On your original device

Activate your venv and export dependencies:
```
pip freeze > requirements.txt
```
Commit `requirements.txt` to your repo.

## 2. On the new device (after cloning repo)

### Create a new virtual environment:
```
python -m venv venv
```

### Activate it:
   ```  
    source venv/bin/activate
   ```    

### Install dependencies:

```
pip install-r requirements.txt
```

# ⚠️ Important tips

### 🔹 Match Python version

Make sure both machines use the **same Python version**:
```
python --version
```

### 🔹 Don’t commit venv

Your repo should include a `.gitignore` like:

### Loading into a branch and pushing

```
git checkout name-of-branch
```
```
git push -u origin name-of-branch
```
