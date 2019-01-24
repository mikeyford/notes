

### Auto-reloading notebook functions

`%load_ext autoreload`  
`%autoreload 1`  
`%aimport utils.processing`

### Prod project in jupyter notebook located elsewhere
`import sys`  
`sys.path.append("path/to/project/")`  
`from file import object`  

### Ignore specific warning type

`import warnings`  
`warnings.simplefilter(action='ignore', category=FutureWarning)`

### Set default matplotlib figsize in jupyter

`plt.rcParams['figure.figsize']=[8, 6]`


### Import module file to nb

```
import sys
sys.path.append('/Users/mike/witan.send.analysis/input_data_vis/')
import transitions_vis as tv```

