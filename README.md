# How To Run

0. 
    * The Computer Vision Lab CVL-database is required to run this project. The database can be downloaded from: https://zenodo.org/record/1492267#.YoqqB5PMLvU.

    * Python3 is required to run this project. The installation instructions can be found here: https://www.python.org/downloads/.

    * Pip is required to run this project. The installation instructions can be found here: https://pip.pypa.io/en/stable/installation/. Alternatively, Pip can be installed with the following command:
    `sudo apt-get install python3-pip`.

    * Jupyter is required to run this project. The classic Jupyter Notebook program needs to be installed. The install instructions can be found here: https://jupyter.org/install.

    After installation Jupyter may not be added to the PATH of Unix systems, but can be accessed with `~/.local/bin/jupyter-notebook` (https://stackoverflow.com/a/35318514).

1. 'Initialize.ipynb' contains the project set up code. Execute the notebook with the following command: `jupyter Initialize.ipynb` or `~/.local/bin/jupyter-notebook Initialize.ipynb` if using a Unix system.

2. Pytorch is required to run this project. The installation instructions can be found here: https://pytorch.org/get-started/locally/. If not already installed, select your preferences (Stable PyTorch Build, OS, Compute Platform) on the site and copy the install command to the second cell of the opened 'Initialize' notebook.

3. To install the necessary Python libraries, click the 'Cell' button in the menu bar of the opened 'Initialize' notebook, and select 'Run All'. The seventh cell of the notebook will prompt you to enter the location of the 'words' folder from the downloaded CVL dataset and preprocess the images.

4. After initialization, navigate to http://localhost:8888/tree via the address bar or by clicking the Jupyter logo in the top-left and navigating to the dashboard.

5. Select and open either of the desired network notebooks containing the project code, 'Network.ipynb' and 'Network_Labeled.ipynb'. Click the 'Cell' button in the menu bar of the opened notebook, and select 'Run All' to train and evaluate the network.
