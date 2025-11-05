
# Setup

```
$ conda create -n lab-3.12 python=3.12
$ conda activate lab-3.12

# conda installs old version of execnb, use pip instead
$ pip install nbdev jupyterlab
$ nbdev_install_quarto
$ pip install jupyterlab-quarto

$ nbdev_new
$ nbdev_install_hooks
$ nbdev_export
$ pip install -e '.[dev]'

# In separate terminal
$ nbdev_preview

```
