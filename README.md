To run the code you may want to create a conda virtual environnement
To do so, start by downloading miniconda (lighter version of anaconda) on this site : https://www.anaconda.com/download/success and go on the bottom of the page to dwonload it

If not done already, clone this git
and in this directory run
conda create --name RS_env --file requirements.txt

Now that everything is installed you can do 
conda activate RS_env to launch the virtual environnement (conda deactivate to exit)

You're ready to run python code !

If you need to install another lib run 
conda install <lib-name> 
in shell while in the RS_env
then, to be sure everyone has it export it by running
conda list --export > requirements.txt
in requirements.txt 's directory

If the requirements.txt had change, you can probably update your lib by doing
conda install requirements.txt

