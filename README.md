# DAGReducer - Reducing Graphs for Structural Equation Modeling

Takes in a networkx DiGraph() object and reduces it to its 'essential' form for Structural Equation Modeling.

### Note:

- The function assumes interest in mediating processes (and so keeps all causal paths).
- The function removes variables which might be useful for precision purposes (thus prioritising reduction in graph complexity over estimation).

s
There are two worked examples in the ```reducer.ipynb``` file. 