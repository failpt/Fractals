# Fractals
The project consists of a series of interactive fractal visualizations with `ipywidgets` and their descriptions *in Ukrainian*. A formatting cell is included at the end, made for the purpose of converting the `Fractals.ipynb` file into a website with [Voilà](https://voila.readthedocs.io/en/stable/using.html), but it is recommended you run the code cells in JupyterLab for a smoother experience.

## Visualized topics (in order)
- Cantor set
- Sierpiński triangle
- Mandelbrot set
- Julia set
- Koch snowflake
- Trees
- Barnsley fern
- The diamond-square algorithm
  + 3D terrains
  + Plasma fractal
  + Midpoint displacement for 2D terrains
- Coastlines

## Required packages
- Python 3.11.5
- [Matplotlib 3.7.2](https://matplotlib.org/) — plotting
- [NumPy 1.24.3](https://numpy.org/) — numerical operations
- [ipywidgets 8.0.4](https://ipywidgets.readthedocs.io/) — interactive controls
- [Voilà 0.5.5](https://voila.readthedocs.io/) — web app rendering (optional)
- [JupyterLab 3.6.3](https://jupyterlab.readthedocs.io/) — notebook interface

Create the environment with:

```bash
conda env create -f environment.yml
```
