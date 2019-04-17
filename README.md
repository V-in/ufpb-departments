# ufpb-departments
Unidades da UFPB - Universidade Federal da Paraiba: jupyter notebook + generated graph.

# Installing dependencies

```bash
$ pip3 install -r ./requirements.txt
```
# Runing

Run `notebooks/build_graph.ipynb` with [jupyter](https://jupyter.org/install)

# Visualization 

Generated `output/departments.graphml` can be visualized in any `.graphml` supporting library/application such as [Cytoscape](https://cytoscape.org/)

# Dataset

JSON Array with elements having 3 required properties:

- idUnidade: unique identifier
- hierarquiaUnidade: "." delimited path to node
- unidadeGestora: imediate ancestor

Any other properties were considered node metadata
