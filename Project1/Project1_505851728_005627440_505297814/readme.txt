Python: 3.7.9 (setup via Conda environment)

Jupyter notebook: install using "conda install -c conda-forge jupyterlab" 

jupyter                   1.0.0
jupyter_client		      6.1.7                     
jupyter_console           6.2.0                       
jupyter_core              4.7.0             
jupyterlab_pygments       0.1.2                       
jupyterlab_widgets        1.0.0  


Required Python Packages and versions (installed in Conda environment):
scikit-learn              0.23.2
scipy                     1.5.2 
gensim                    3.4.0
joblib                    1.0.0
matplotlib                3.3.2
numpy                     1.19.1
nltk                      3.5
pandas                    1.1.3 
bokeh                     2.2.3 
colorcet                  2.0.2
datashader                0.11.1 
holoviews                 1.14.0
umap-learn                0.4.6 
jedi                      0.17.2

Steps to run:
1. Make sure your conda environment and jupyter notebook are appropriately set up.
2. Make sure all the Python packages are installed. The version of gensim we used matters and please use only gensim 3.4.0.
4. Activate your conda environment, navigate to the folder where the notebook is located and type "jupyter notebook"
5. Place the GLoVE embedding text files in a folder called 'glove' in the same directory where the notebook is located.
5. Open the notebook and just sequentially run all the sections.
