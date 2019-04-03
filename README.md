Setting Up Preferred Settings

1. Go to '.jupyter' folder and open up the file 'jupyter_notebook_config.py'
2. Make the following edits

## The directory to use for notebooks and kernels.
c.NotebookApp.notebook_dir = 'C:\Users\Joshua Cho\Documents\GitHub\'

## Specify what command to use to invoke a web browser when opening the notebook.
#  If not specified, the default browser will be determined by the `webbrowser`
#  standard library module, which allows setting of the BROWSER environment
#  variable to override it.
c.NotebookApp.browser = 'C:\Program Files (x86)\Google\Chrome\Application\chrome.exe'


How to change Jupyter Notebook Starting folder
https://stackoverflow.com/questions/35254852/how-to-change-the-jupyter-start-up-folder
Follow 8 steps from Yul
doesn't work 100% yet