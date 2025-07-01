# Python Data Structures and Notebooks

Complete the tasks in the Python Notebook in this repository.  
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

Each question is worth one point.

---

**Task 1. Get Started by copying the base repository into your GitHub account**

**Task 2. Open Notebook and Complete Tasks**

- Copy the starter repo into your GitHub account.
- Clone your repo to your local machine and start up Jupyter Lab (or Jupyter Notebook).
- Make edits to Markdown cells and Python code cells.
- Add and commit your changes using Git.
- Push commits up to your GitHub repo.
- Export the notebook as HTML (a web page) for submission using the menu.

---

**Task 3. Export to HTML and Finalize Repo**

**Option 1: Export using the Jupyter menu**  
Go to: **File → Save and Export As... → HTML**

**Option 2: Export using a Python cell**  
Add a Python cell at the end of your notebook and run:
```python
import os
os.system('jupyter nbconvert --to html python-ds.ipynb')
```

**Option 3: Export using a terminal command**  
Open a terminal in your project folder and run:
```
jupyter nbconvert --to html python-ds.ipynb
```

---

**Note:**  
If you have issues creating the HTML file, try upgrading Jupyter:
```
pip install --upgrade jupyter
```
