# Pandata: The scalable open-source analysis stack

Pandata is a fully open source, high-performance, modern Python data-analytics stack usable in any scientific, engineering, or analytical domain.

<img width="100%" alt="image" src="https://github.com/SOSA-org/sosa/assets/1695496/877ff206-8bdd-4045-87da-550f18270ae9">

## Are you limited by your domain’s software stack?

Every scientific or engineering discipline has its own computing needs
Many such disciplines have developed entirely separate sets of tools for:

- Storing data
- Reading data
- Processing data
- Plotting data
- Analyzing data
- Modeling data
- Exploring data

These stacks are largely tied to outdated architectures and assumptions:

- Not cloud or remote friendly: Tied to a local desktop GUI or OS
- Not scalable: Tied to a single processor (CPU), whether for technical or licensing reasons 
- Not general purpose: Narrow audience, maintained by few, and unknown outside the field

It’s all just data – time for a better way!

## Pandata: the scalable open-source analysis stack

Instead of your outdated stack, use modern Python data-science tools that are:

- Domain independent: Maintained, used, and tested by many people all across the world
- Efficient: Run at machine-code speeds using vectorized data or JIT compilation
- Scalable: Run on anything from a single-core laptop to a thousand-node cluster
- Cloud friendly: Fully usable for local or remote compute using data on any file storage system
- Multi-architecture: Runs on your desktop and on Mac/Windows/Linux CPUs and GPUs
- Scriptable: Run in batch mode for parameter searches and unattended operation
- Compositional: Select which tools you need and put them together to solve your problem
- Visualizable: Support rendering even the largest datasets without conversion or approximation
- Interactive: Support fully interactive exploration, not just rendering static images or text files
- Shareable: Deployable as web apps for use by anyone anywhere
- OSS: Free, open, and ready for research or commercial use, without restrictive licensing

But I don’t do data science, you say? You do! Data science is what’s shared across lots of disciplines; it’s not just for AI and ML (though it supports those well too!)

## What is Pandata and why do I need it?

Pandata is just a name for a specific collection of Python libraries maintained separately by different people. Pandata libraries are designed to work well with each other to achieve the goals listed above (being scalable, interactive, etc.). You don't need Pandata for anything other than to know which libraries are designed to work well together in this way. Just use any library from Pandata and be happy, knowing that if you need something covered by one of the other libraries, you can use them together without jeopardizing scalability, interactivity, and so on.

## Who runs Pandata?

Pandata is just this informational website set up by the authors of some of the Pandata tools; there's no management or policies or software development specifically associated with Pandata. But if you have questions or ideas about what to do with Pandata, feel free to open an issue for discussion!

## Examples

There are lots of examples online of applying Pandata libraries to solve problems, including:

- [Pangeo](https://pangeo.io): JupyterHub, Dask, Xarray for climate science; Pandata is Pangeo but for any field!
- [Attractors](https://examples.pyviz.org/attractors/clifford_panel.html): Processing huge datasets with Numba, rendering with Datashader
- [Census](https://examples.pyviz.org/census): Reading chunked data from Parquet, rendering with Dask + Datashader
- [Ship traffic](https://examples.pyviz.org/ship_traffic): Rendering spatially indexed data with interactive lookup
- [Landsat](https://projectpythia.org/landsat-ml-cookbook/README.html): Intake data catalog, xarray n-D data, hvPlot+Bokeh plotting, Dask ML
- [Minian](https://minian.readthedocs.io/): Jupyter, Dask, and HoloViews for neuroscience

See the [Pandata paper from SciPy 2023](https://procbuild.scipy.org/download/jbednar-sosa) for all the details, and then just download and use any of the packages in Pandata in any combination and enjoy having all this power at your fingertips!
