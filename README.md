# Minimal Model Reasoning with Machine Learning Models
This repository uses the pre-trained models and code from https://github.com/porscheofficial/sls_sat_solving_with_deep_learning/blob/main/python/src/evaluate_with_given_params.py.

Modifications to the code have been made and it has been adapted to use the Deep Learning SLS Sat Solving Model for Minimal Model Solving.

**Installation Instructions** <br>
1*) On Windows, run WSL2, and install Ubuntu. <br>
2*) Run the WSL2 Ubuntu instance. <br>
3) Within WSL2 Ubuntu instance, create a Conda virtual environment and ensure it is activated. <br>
4) Follow the "Setup" instructions from the original repository. <br>
5) Run Jupyter Notebook using `jupyter-notebook --no-browser`. Click on the local host link to launch Jupyter Notebook in your browser. <br>
6) In Jupyter Notebook, navigate to "python/src" and open "minimalmodel.ipynb".
7) At the top bar, go to "Kernel" > "Change kernel" and ensure the Conda virtual environment's kernel is selected^. <br>
8) You should now be able to run the code blocks. <br>

*If you are using Linux, skip steps 1 and 2.

^If the Conda virtual environment's kernel is not showing up, you may need to install the kernel first: <br>
a) Run `conda install ipykernel` <br>
b) Run `python -m ipykernel install --user --name={name of Conda virtual environment}` <br>
c) Run `jupyter kernelspec list`, which should show the installed virtual environment's kernel. <br>
d) Restart Jupyter Notebook.