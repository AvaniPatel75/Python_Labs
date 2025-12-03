
# Python Labs — Jupyter Notebook Solutions

> README template that explains both:

✔ a collection of Python Lab solutions implemented in Jupyter Notebooks<br>
✔ installation & setup instructions for Python and Jupyter Notebook.

---

**Project name:** Python Labs — Jupyter Notebook Solutions

**Short description:** A repository containing solutions for course labs implemented as Jupyter notebooks. Each lab has a dedicated notebook (`lab01.ipynb`, `lab02.ipynb`, etc.) plus supportive files such as `requirements.txt`, helper modules, and tests where applicable.

**Goals:**

* Provide well-documented, reproducible solutions for each lab.
* Make it easy for instructors and students to run notebooks locally or online (Binder/GitHub Codespaces).
* Include clear instructions for setup, running, and testing.

---

## Repository structure (suggested)

```
/ (root)
├─ README.md                 # This file
├─ Lab_1.ipynb
└─ Lab_2.ipynb
```

---

## Getting started — prerequisites

Choose one of the two common workflows below.

### 1) Using pip (recommended for simple setups)

1. Install Python 3.13+ (3.13 or 3.14 recommended).
2. Check for Python in your PC

```bash
python --version
```

### 2) Run the Installer 

1. After downloading, open the installer file.

2. Check the box that says 'Add python.exe to PATH'.

3. Click on 'Install Now'.

4. After Completing Process click on finish.

## Running the notebooks locally

1. Activate your environment (see above).
2. Install Jupyter if not present:

```bash
pip install notebook jupyterlab
```

3. Start Jupyter Lab (recommended) or classic notebook:

```bash
jupyter lab
# or
jupyter notebook
```

4. Open the appropriate `notebooks/labXX.ipynb` in the browser and run cells.

**Tip:** Use the Kernel ▶ Restart & Run All feature before submitting to ensure notebooks run from a clean state.

---

## Ways to run a python program

### **1. Using Python IDLE – Interactive Mode**

**Steps:**

1. Open IDLE

(Search “IDLE” in Start Menu on Windows, or run ‘idle’ on

Mac/Linux)

2. You will see the Python Shell (looks like this):

3. Type this command.

>>> print(“Hello World”)

4. Press enter and you will see the output. ��

###

Steps:

1. Open IDLE.

2. Click on:

3. A blank editor will open.

File → New File

4. Type python command

>>> print(“Hello World”)

5. Save the file:

File → Save → hello.py (Ctrl + s )

6. Run the program:

Run → Run Module (F5)

7. You will see the output ��

### **3. Using Command Prompt or Terminal**

### Steps:

1. Open command prompt and navigate to directory containing your

python file.

2. Run the following command:

python file_name.py

### **4. Using Visual Studio code**

Steps:

1. Verify python is installed in you system.

2. Open Visual Studio code and go to extension tab on lest panel.

3. Search ‘python’ in the search bar.

4. You will find the following result.

5. Install the first one extension

6. Open a folder and create python file. ( with file extension .py)

7. Write your python code in the file.

8. To run the file, click on on top right corner.

9. It will run the python code in integrated terminal.

### **5. Using Jupyter Notebook**

Steps:

**1. Download Anaconda:**

● Open official website:

[https://www.anaconda.com/download](https://www.anaconda.com/download)

● Scroll down to find Miniconda Installer

● Click on “Download Miniconda Installer”.

● It will open another page.

● Download appropriate installer.

**2. Install Anaconda**

● Open installer

● Click Next

● Agree to License Agreement

● Select Installation Type: Just Me (recommended)

● Choose installation location

● Select Add to PATH environment variables.

● Click on install.

**3. Open Jupyter notebook**

● Open Anaconda Navigator from start menu.

● Look for Jupyter Notebook

● Click Launch. (it opens your system’s default user folder)

**4. Alternate way**

● Open anaconda prompt.

● Go to directory which you want to open in Jupyter notebook

● Type this command and press enter

‘jupyter notebook’

##

---

## Tests and automated checks (optional)

If you include unit tests, run them with `pytest`:

```bash
pip install pytest
pytest -q
```

You can add GitHub Actions workflows to run tests automatically on push/PR.

---

## Code style and checkpoints

* Keep each notebook self-contained: import statements and data-loading steps should be present at the top.
* Avoid writing answers only as Markdown; if a grading script inspects outputs, make sure functions return values that tests can import and call.
* Use clear section headings and short explanatory comments.
* Remove heavy outputs (large images or long printed tables) before committing if they bloat the repo.

---

## Example `requirements.txt` (minimal)

```
notebook
jupyterlab
matplotlib
math
os
```

Add any additional packages required by your labs.

##

---

## Conclusion

This repository provides a complete set of Python lab solutions using Jupyter Notebooks, ensuring that students can learn, practice, and execute Python programs in multiple ways. Whether running code through Jupyter, VS Code, IDLE, or terminal, the steps in this README help beginners start programming easily.

If you find any issues or want to contribute improvements, feel free to update notebooks or suggest changes.

---

### Thank you for using Python Labs 🚀

Keep practicing and exploring — every line of code makes you a better programmer!
