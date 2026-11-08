# AI/ML Vertical Projects

Three Google Colab notebooks submitted for the DevSoc AI/ML vertical assignment. Each notebook is self-contained.

| Notebook | Task | Needs |
|---|---|---|
| `Final_OB.ipynb` | Obesity risk prediction with ensemble learning (the target column is `NObeyesdad`, as in the UCI obesity-levels dataset) | The dataset CSV at `/content/drive/MyDrive/dataset.csv` (mounted from Google Drive; edit `dataset_path` in the first cell to change it) |
| `Final_NST.ipynb` | Neural style transfer with VGG-19 (TensorFlow) | Nothing local; the content and style images are downloaded from Wikimedia Commons by the notebook |
| `Final_NN.ipynb` | MNIST digit classification with a neural network written from scratch in NumPy | Nothing local; MNIST is downloaded through `sklearn.datasets.fetch_openml` |

## Running

Open a notebook in Google Colab (or Jupyter with the usual scientific Python stack: numpy, pandas, scikit-learn, matplotlib, seaborn; TensorFlow and Pillow for the style-transfer notebook) and run the cells in order. `Final_OB.ipynb` imports `google.colab`, so it runs as-is only in Colab. Saved outputs in the notebooks are from the author's runs.
