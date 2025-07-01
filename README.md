# Python Data Structures and Notebooks

Complete the tasks in the Python Notebook in this repository.
To be submitted for credit, all changes must be committed and pushed to this repository (do not create your own repository unless instructed to on the course website).

## Rubric

Each question is worth one point.

Task 1. Get Started by copying the base repository into GitHub account

Task 2. Open Notebook and Complete Tasks

~~~text
-- Copy the starter repo into your GitHub account.
-- Clone down your repo to your local machine,start up Jupyter lab (or Jupyter Notebook)
-- Made edits to Markdown cells and Python code cells
-- Perform add and commit your changes using Git
-- Push commit up to the GitHub repo
-- Exported notebook as HTML (a web page) for submission using the menu
~~~

Task 3. **Export to HTML and Finalize Repo**

**Use the Jupyter Notebook or JupyterLab interface menu:**  
&nbsp;&nbsp;&nbsp;&nbsp;Try: **File -> Save and Export As... -> HTML**

**Add a Python cell at the end of your notebook, enter the following Python command (change the file name as needed), and run the cell:**  
&nbsp;&nbsp;&nbsp;&nbsp;`!jupyter nbconvert --to html python-ds.ipynb`

**Export Using os Package (in a Python Cell)**  
Use the following code in a Python cell and run the cell:  
&nbsp;&nbsp;&nbsp;&nbsp;```python  
&nbsp;&nbsp;&nbsp;&nbsp;import os  
&nbsp;&nbsp;&nbsp;&nbsp;os.system('jupyter nbconvert --to html python-ds.ipynb')  
&nbsp;&nbsp;&nbsp;&nbsp;```

**Export Using a Terminal Command**  
Open a terminal in the project repository root folder and run:  
&nbsp;&nbsp;&nbsp;&nbsp;`jupyter nbconvert --to html python-ds.ipynb`

---

**Had some issues creating the HTML file and fixed by upgrading jupyter:**  
&nbsp;&nbsp;&nbsp;&nbsp;`pip install --upgrade jupyter`
