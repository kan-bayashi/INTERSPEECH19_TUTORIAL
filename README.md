# INTERSPEECH2019 Tutorial materials

## Setup

Install jupyter & RISE.

```bash
pip install -U jupyter
pip install -U RISE
jupyter-nbextension install rise --py --sys-prefix
jupyter-nbextension enable rise --py --sys-prefix
```

Copy `custom` directory including CSS for jupyter notebook.

```bash
cp -r custom ~/.jupyter
```

Update configuration of RISE.

```bash
python config_updater.py
```

## How-to-apply CSS for RISE

Make `<notebook_name>.css` and then put it the same directory of the notebook.  
The CSS will be automatically loaded in presentation mode.
