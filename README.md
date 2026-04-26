# Explanation document - How to use this repository

## Loading into your branch
1) Load into your branch before starting
- If it is your first time, do the following
   ```
   python -m venv venv
   ```
   ```
   source venv/bin/activate 
   ```
   ```
   pip install requirements.txt 
   ```

- After setting up environment (you are continuing on work):
   - If you cannot see (venv) and your name [it should be your name instead of (tutorial)] in terminal, like the image<br>
   
  ![image](https://github.com/hivan04/ml-finance/blob/tutorial/explanation_images/1.png)
  <br>

   Do the following:
   ```
   git switch your_name
   ```
   ```
   source venv/bin/activate 
   ```
## Updating your repository 
2) To make any changes/updates to your repository, do the following (**ensure you have saved the file(s) you want to upload**) 
**Make sure you are in your branch**<br>

![image](https://github.com/hivan04/ml-finance/blob/tutorial/explanation_images/2.png)<br>

*You can check yourself by running the following (you should see an * next to your name if you are in your branch)*
   ```
   git branch
   ```
   
- If you just want to update everything (easiest method for updating repository)
   ```
   git add .
   git commit -m "write something here"
   git push
   ```

- If you only want to upload a specific file, instead of '.', write the file path name 
   - You can find the file path name by right-clicking on the file and clicking ''copy path''
      ```
      git add '/put_pathname_here'
      git commit -m "write something here"
      git push
      ```

## Pulling from a repository
If you want to pull a file from a specific branch (e.g. you want to)

