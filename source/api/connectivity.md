# IDAES Connectivity Tool

Quickly create visual diagrams showing the connectivity of flowsheet units and streams. 


<!--

## IDAES Connectivity Tool

* Goals: View connectivity of a model in a simple and portable form from Python or command\-line
* Major Features:
  - Python library to look at any model
  - Export connectivity as a table \(CSV\)
  - View connectivity by translating into text\-based drawing formats Mermaid or D2
  - See unit names and stream names
  - Python API to annotate the streams and/or units in the diagram
* Compatibility: Runs on all Pyomo models and IDAES-based flowsheets

Developers trying to see if their model is connected as expected

Works well in Jupyter\, as Mermaid is a supported output format

Lightweight library that does one thing

 __Drawbacks / When not to use __ 

Resulting data is static

Mermaid and D2 diagrams not interactive; i\.e\. they cannot be easily rearranged

Only does one thing\, not an analysis suite

No graphical UI; not for users who want to point\-and\-click


### IDAES Connectivity Tool Screenshots

Accepts any Python script or importable module

```
❯   idaes  \-conn example\.py \-\-to mermaid \-L \-\-build   build\_blocks\_set\_version   \-D TD
```

Output:
```
```

* Diagram when rendered by   MermaidJS
* Generate table or diagram from Python; Render inline in   Jupyter   Notebooks
* Generate Mermaid diagram from console

-->