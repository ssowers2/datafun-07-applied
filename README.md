# datafun-07-applied

## Purpose  
- To create a guided project.

## Step 1: New Project Setup
1. Initialize Repository: Create a new GitHub repository named **datafun-07-applied** with a default `README.md`.
2. Clone the repository to your local machine in the **Projects** folder.
3. Open the project folder in **VS Code**.

## Step 2: Add Essential Files
1. **.gitignore**  
   Add a `.gitignore` file to specify files and folders to exclude from version control. You can reference an existing `.gitignore` template for Python projects.
2. **requirements.txt**  
   This file lists all necessary packages for the project. Review and adjust it to include or exclude packages based on your project’s needs.
3. **README.md**  
   Edit README.md to record commands, process, and notes so far as the project progresses.
4. 5. This is good time to `git add .`, `git commit -m "Message"`, `git push -u origin main` files to GitHub

## Step 3: Create and Manage Virtual Environment
1. Run command `git pull` first, to make sure the current project contents are on the machine.
2. Windows PowerShell: `python -m venv .venv` to create a new .venv environment in the project repo.
3. Activate the Virtual Environment: `.\.venv\Scripts\activate`

## Step 4: Install Required Packages
`pip install -r requirements.txt` to install all packages at once OR use `py -m pip install` commands to add packages on the go (e.g. `py -m pip install pandas` or group installs `pip install numpy pandas matplotlib seaborn`)

## Step 5: Select Python Interpreter in VS Code
1. Ensure VS Code is set to use the .venv environment.
2. Open the command palette using (Windows) Ctrl + Shift + P.
3. Type "Python: Select Interpreter".
4. Choose the interpreter inside the .venv folder located in the project root directory.
5. This is good time to `git add .`, `git commit -m "Message"`, `git push -u origin main` files to GitHub

## Step 6: Create New Jupyter Notebook (File>New>"name.ipynb")
1.  Data Acquisition
2.  Initial Data Inspection
3.  Initial Descriptive Statistics
4.  Initial Data Distribution for Numerical Columns
5.  Initial Data Distribution for Categorical Columns
6.  Build the Model
7.  Test the Model
8.  Predict
9.  Create Visualizations

## Git Commands Reminders 
1. Add Changes: `git add .`
2. Commit Changes: 5. `git commit -m "Message"`
3. Push Changes to GitHub: `git commit -m "Message"`
4. Pull Latest Changes:  `git push -u origin main`