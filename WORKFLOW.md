---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.17.2
  kernelspec:
    display_name: Bash
    language: bash
    name: bash
---

# WORKFLOW


## Executed Notebooks

```bash
SRC="../oceandata-notebooks/book/_build/jupyter_execute/notebooks"
DST="book/presentations/notebooks/"

cp -lr $SRC/hackweek/* $DST
cp -lr $SRC/oci/oci_terrestrial_data.ipynb $DST
```

## Create Conda Environment

```bash
conda env create -n book -f conda/conda-linux-64.lock.yml
```

## Preview

```bash
conda run --live-stream -n book ./scripts/build_resources.sh
```

Run the next cell to preview the website.
Interrupt the kernel (press ◾️ in the toolbar) to stop the server.

On a JupyterHub? Try viewing at [/user-redirect/proxy/8000/](/user-redirect/proxy/8000/).

```bash
python -m http.server -d book/_build/html/
```
