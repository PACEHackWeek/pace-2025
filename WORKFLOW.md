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


## Merge Executed Notebooks

```bash
export CACHE="../oceandata-notebooks/.jupyter_cache"
jcache notebook -p $CACHE list
```

```bash
export DST="book/presentations/notebooks"
export SRC="../oceandata-notebooks/book/notebooks"

for i in \
  hackweek/earthdata_cloud_access \
  hackweek/modis_lombscargle_periodogram \
  oci/oci_no2 \
  oci/oci_terrestrial_data \
  oci/oci_project_and_format \
  oci/oci_data_visualization \
  oci/oci_ocssw_processing_overview \
  harp2/harp2_basic_visualizations \
  harp2/harp2_l2_aerosol_product \
  spexone/spexone_basic_visualizations \
  spexone/spexone_l2_aerosol_product \
  ; do
  jcache notebook -p $CACHE merge "$SRC/$i.md" "$DST/${i##*/}.ipynb"
done
```

```bash
conda env create -n book -f conda/conda-linux-64.lock.yml
```

```bash
conda run --live-stream -n book ./scripts/build_resources.sh
```

## Preview


Run the next cell to preview the website.
Interrupt the kernel (press ◾️ in the toolbar) to stop the server.

On a JupyterHub? Try viewing at [/user-redirect/proxy/8000/](/user-redirect/proxy/8000/).

```bash
python -m http.server -d book/_build/html/
```
