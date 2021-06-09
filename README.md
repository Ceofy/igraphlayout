# IGraph layout
Jupyter notebooks to apply igraph layouts to CX networks.

## Usage
1. Clone the repo.

```
git clone https://github.com/Ceofy/igraphlayout.git
cd igraphlayout
```

2. If you are laying out a CX network from NDEx or from a ```.cx``` file, navigate to the ```using_cx``` directory.

```
cd using_cx
```

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Otherwise, if you are using the notebook to lay out a network that is currently open in Cytoscape, navigate to the ```using_cytoscape``` directory.

```
cd using_cytoscape
```

3. Start the jupyter notebook server in the directory you are in.

```
jupyter notebook
```

4. Open the ```apply_igraph_layout_to_..._network.ipynb``` file by clicking on it, then follow the instructions in the notebook.

## Requirements

For laying out both CX and Cytoscape networks:
* [igraph](https://igraph.org/python/)

For laying out CX networks only:
* [ndex2](https://pypi.org/project/ndex2/)

For laying out Cytoscape networks only:
* [py4cytoscape](https://py4cytoscape.readthedocs.io/en/latest/)
* [shapely](https://pypi.org/project/Shapely/)
