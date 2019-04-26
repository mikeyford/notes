

### Auto-reloading notebook functions

`%load_ext autoreload`  
`%autoreload 1`  
`%aimport utils.processing`

### Inspect project in jupyter notebook located elsewhere
`import sys`  
`sys.path.append("path/to/project/")`  (needs to be full path)  
`from file import object`  

### Ignore specific warning type

`import warnings`  
`warnings.simplefilter(action='ignore', category=FutureWarning)`

### Set default matplotlib figsize in jupyter

`plt.rcParams['figure.figsize']=[8, 6]`


### Make conda env available in base jupyter environment 
`conda install ipykernel`  
`python -m ipykernel install --user --name=bret`
