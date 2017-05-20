# python3-physics
Georg Brandl's IPython extension updated for Python 3 compatibility for Jupyter notebooks.

See http://www.southampton.ac.uk/~fangohr/blog/physical-quantities-numerical-value-with-units-in-python.html for a blog giving examples and usage.

See https://bitbucket.org/birkenfeld/ipython-physics for the general README.txt for physics.py.

A few basics: put this file somewhere in PYTHONPATH. My recommendation for Jupyter is to put it in ~/.ipython . Then, in Jupyter you can do `import physics` or `from physics import Q`, or to get the very nice syntactic sugar, use `%load_ext physics`

Then you can do `v = Q(10, "m/s")` or, with the load_ext method, simply `v = 10 m/s`

See the links above for more details, such as converting between units and the sugar for that.

Just to be clear - I added and changed as little as I could get away with, to get it to run in Python 3 and work with Jupyter.

Tested on: `Python 3.6.0 |Anaconda 4.3.1 (64-bit)| (default, Dec 23 2016, 12:22:00) 
[GCC 4.4.7 20120313 (Red Hat 4.4.7-1)]`