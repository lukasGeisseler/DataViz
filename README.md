# DataViz

DataViz Custom Examples

This repository consists of different examples of (custom) DV-Codes:

- [Timeline_stackplot](code/Timeline_stackplot.ipynb) is a jupyter notebook of a stack plot used as a timeline (matplotlib). It shows the duration of an employee (lengths of fields) and the role (colored categories) over time. This timeline is used for a big plot and, is therefore BIG. For smaller use cases, please adapt the plot size and font parameters. [Byron and Wattenberg (2008)](https://leebyron.com/streamgraph/stackedgraphs_byron_wattenberg.pdf) described the influence of different layer orders, and provided hints for better readability. Besides the timeline, you can also find here a class (Font_Library) to temporarily use google fonts with matplotlib in an easy and convenient way.

![timeline_stackplot_example](https://github.com/lukasGeisseler/DataViz/blob/main/plots/timeline_stackplot.png?raw=true)

- [cytoscapejs_graph](code/cytoscapejs_graph/index.html) is a cytoscape.js example of a infinitely running physics simulation (cola) of a graph with nodes and edges. The data was extracted with Llama3 from wikipedia texts and enriched with wikidata querries. The visualization is interactive, which means it is possible to drag and stick, release and remove nodes. Additional it is possible to save the graph as PDF. This example uses beside cytoscape.js the following packages [js-pdf-export](https://github.com/cytoscape/cytoscape.js-pdf-export.git), [js-cola](https://github.com/cytoscape/cytoscape.js-cola.git)

![cytoscapejs_graph_example](https://github.com/lukasGeisseler/DataViz/blob/main/plots/cytoscapejs_graph.png?raw=true)