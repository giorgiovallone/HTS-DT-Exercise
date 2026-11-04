# HTS-DigitalTwin-Exercise

Current sharing between superconducting tapes: a digital-twin exercise.

A Jupyter notebook in which you train a small neural-network surrogate of two
REBCO tapes sharing current, and build its loss function step by step, from
fitting the currents to enforcing Kirchhoff's voltage law.

## How to run it

Nothing needs to be installed: the notebook runs in your browser.

1. Download [`HTS-DigitalTwin-Exercise.ipynb`](HTS-DigitalTwin-Exercise.ipynb)
   (on GitHub: open the file and use the download button).
2. Open JupyterLite: <https://jupyterlite.readthedocs.io/en/stable/_static/tree/index.html>
3. Upload the notebook with the upload button (arrow icon) above the file list,
   and double-click it to open it. Choose the **Python (Pyodide)** kernel if asked.
4. Run the cells in order with **Shift+Enter**.

JupyterLite keeps your work in the browser; use *File → Download* to save your
edited notebook. The notebook also runs in any Jupyter installation with NumPy
and Matplotlib.
