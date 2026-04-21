steps in making this work

1. first install VScode

2. Download Anaconda

    a. Go to the official site:
        👉 https://www.anaconda.com/download

    b. Choose Windows
        Download the Python 3.x version (64-bit)
3. Install Anaconda

    After downloading:

    Run the .exe installer
    Click Next → Next → I Agree

    Choose:
    ✅ Just Me (recommended)

    Install location → leave default
    Important options:
    ⛔ DO NOT check “Add Anaconda to PATH”

    ✅ You can check “Register Anaconda as default Python”
    Click Install

4. Open Anaconda prompt
    type: conda --version, enter. then type python --version. 
    if it shows the version of thos two, your anaconda is working.

5. Create a folder where you will put the code.
    for example: C:\Users\"yourusername"\Python Workspace\python files\GraphCalculator

6. Create new env for python.
    a. copy the path you created, then in your anaconda prompt 
    type: cd "the folder you created"
    for example:
    cd C:\Users\"yourusername"\Python Workspace\python files\GraphCalculator
    then enter

    b. after that create the conda env, by typing
        conda create -n graphcalc python=3.11
        wait till it loads all necessary resources.
    c. activate the environment by typing.
        conda activate graphcalc
        then enter you should see
        (graphcalc) in the beginning of your promt line
        (base) C:\Users\"yourusername"\Python Workspace\python files\GraphCalculator
        to 
        (graphcalc) C:\Users\"yourusername"\Python Workspace\python files\GraphCalculator
        if that's the case to you, you are on the right track.
7. Install necessary library.
    in anaconda prompt again, where it should already at:
    (graphcalc) C:\Users\"yourusername"\Python Workspace\python files\GraphCalculator>
    type line by line not simultaenously
    conda config --add channels conda-forge
    conda config --set channel_priority strict
    conda install matplotlib numpy ipywidgets jupyter nomkl

    after it successfully installed.
    type
    jupyter nbextension enable --py widgetsnbextension

8. inside the folder you created copy or cut then paste the file that you downloaded 
    inside that folder.
     it should look like this
     GraphCalculculator
     |notebook.ipynb

9. Go back to anaconda prompt.
    (graphcalc) C:\Users\"yourusername"\Python Workspace\python files\GraphCalculator>
    type: code .
    this will lead you to vscode
    activate the kernel of the notebook and install necessary extension that vscode told you.

10. Run the Notebook.
    email me if there is a problem: trinidadleandroangelo@gmail.com

