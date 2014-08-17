Mathematica Notebooks
=====================

A collection of my Wolfram Mathematica notebooks.

Development Status
---------------------

### Reuse-ability

These notebooks are mainly exploration of features and possibilities provided by Wolfram Mathematica. They are good demonstration and examples, but not reuse-able software or packages.

### Compatibility

All notebooks included in this repository can run in Wolfram Mathematica 8 or above, even the ones from far early days. Before putting them here, I've reprocessed every single statements to make them runnable in Wolfram Mathematica 8.

### Naming

Notebooks are specifically named to reflect the contents inside them.

### Data

All external data files that these notebooks needs to run are provided. Notebooks load them using relative path, e.g.

```
t = Import["data/c.dat","Table", Path -> NotebookDirectory[] ]
```

The data are either well-known (like the data of chemical elements) or collected by myself, so there's no copyright issue.

Directory Structure
----------------------

* `early-featured`: featured notebooks in various themes from far early days
* `physics`: notebooks about actual physics problems. For now, they are just created during reading the book [Mathematica for Theoretical Physics: Classical Mechanics and Nonlinear Dynamics](http://www.amazon.com/Mathematica-Theoretical-Physics-Classical-Mechanics/dp/0387016740) and [Mathematica for Theoretical Physics: Electrodynamics, Quantum Mechanics, General Relativity, and Fractals](http://www.amazon.com/Mathematica-Theoretical-Physics-Electrodynamics-Relativity/dp/0387219331)

Licence
----------

MIT Licence, see LICENCE. Copyright (c) 2014 Utensil Song (https://github.com/utensil)
