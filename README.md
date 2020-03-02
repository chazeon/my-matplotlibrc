# My `matplotlibrc`

My default preferences for Matplotlib

## Usage

Copy the `matplotlibrc` to the following directories. And check with

```bash
python3 -c "import matplotlib; print(matplotlib.matplotlib_fname())"
```

or in Python


```python
import matplotlib
matplotlib.matplotlib_fname()
```

Result should point to the absolute path to your custom `matplotlibrc`.

### Unix/Linux:

```bash
$HOME/.config/matplotlib/matplotlibrc or
$XDG_CONFIG_HOME/matplotlib/matplotlibrc (if $XDG_CONFIG_HOME is set)
```

## Other platforms:

```bash
$HOME/.matplotlib/matplotlibrc
```
