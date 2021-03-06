
# keras 2.0.7 (unreleased)

- `install_keras()` function which installs both TensorFlow and Keras

- Use keras package as default implementation rather than tf.contrib.keras

- Training metrics plotted in realtime within the RStudio Viewer during fit 

- `serialize_model()` and `unserialize_model()` functions for saving 
  Keras models as 'raw' R objects.

- Automatically convert 64-bit R floats to backend default float type

- Ensure that arrays passed to generator functions are normalized to C-order 

- `to_numpy_array()` utility function for custom generators (enables
  custom generators to yield C-ordered arrays of the correct float type)
  
- Added `batch_size` and `write_grads` arguments to `callback_tensorboard()`

- Added `return_state` argument to recurrent layers.

- `is_keras_available()` function to probe whether the Keras python 
  package is available in the current environment.
  
- `as.data.frame()` S3 method for Keras training history

- Remove names from `keras_model()` inputs


# keras 2.0.5

- Initial CRAN release

