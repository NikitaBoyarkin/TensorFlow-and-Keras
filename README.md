# TensorFlow and Keras

A single Jupyter notebook of TensorFlow / Keras practice — an early deep-learning
exercise kept as a learning artifact. No tests, no packaging and no CI.

## What's inside

- `TensorFlow_and_Keras_1.ipynb` — a worked notebook that loads the **MNIST**
  handwritten-digit dataset with `tf.keras.datasets.mnist`, normalizes it, builds
  and trains a small Keras sequential model, evaluates it on the test set, saves
  the model (`epic_num_reader.model`) and reloads it to make predictions. It also
  plots sample digits with matplotlib.

## Requirements

- Python 3
- `tensorflow` (bundles Keras)
- `matplotlib`
- `jupyter` (or any notebook front-end)

```bash
pip install tensorflow matplotlib jupyter
```

## How to run

```bash
jupyter notebook TensorFlow_and_Keras_1.ipynb
```

Then run the cells from top to bottom. The notebook installs TensorFlow and
downloads MNIST itself, so the first run needs a network connection.

## Topics

`tensorflow` · `keras` · `deep-learning` · `mnist` · `neural-networks` · `jupyter-notebook`

## License

Released under the MIT License — see [LICENSE](LICENSE).

## Links

- Portfolio: <https://nikitaboyarkin.github.io/>
