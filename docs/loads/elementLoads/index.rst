Elemental Loads
***************

.. toctree::
    :titlesonly:
    :hidden:
    :maxdepth: 2

    concentratedload
    uniformload
    trapezoidalload
	
ElementLoad is a base class that can only apply on the Element. There are several ``ElementLoad``s:

- UniformLoad: A uniform load that can apply on a element or one of its faces or edges.
- TrapezoidalLoad: A Partial linear varying load.
- ConcentratedLoad: TODO