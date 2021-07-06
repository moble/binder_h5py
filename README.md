[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/moble/binder_h5py/main?filepath=ImportH5PY.ipynb)

# binder_h5py
Basic test to figure out why h5py isn't working on binder

When attempting to import `h5py`, I was getting this error:

```python
ImportError: cannot import name '_errors'
```

The conclusion is that something about versioning is broken with `h5py <3.3.0`, so we just specify a higher version.
