# Tutorials, Demos, and other Notebooks

Hackweek mentors have assembled resources for participants in the notebooks below.
The {term}`JupyterHub` accessible to hackweek participants has all the necessary software to run any of the notebooks below.
Some titles have links to slides that give an overview or background on the accompanying notebook.
Recordings will be linked here as they become available; titles without a YouTube icon are not presented during the hackweek.
You can find additional resources that will help you analyze PACE data on the [Ocean Color Help Hub].

- **Bold** titles are notebooks that will be presented during the hackweek as step-by-step tutorials, so participants can follow along.
- Mentors will demonstrate notebooks with *italicized* titles during the hackweek, giving an overview and highlights without walking through the entire notebook.
- The remaining notebooks show additional use cases involving PACE data products, and participants are encouraged to seek out the authors during the hackweek!

[Ocean Color Help Hub]: https://oceancolor.gsfc.nasa.gov/resources/docs/tutorials/


| Title | Slides | Notebook | Recording |
| :---- | :----: | :------: | :-------: |
| [**Earthaccess & Earthdata Cloud**][eec-n]                  | [{{ l1 }}][eec-l] | [{{ d1 }}][eec-d] | {{ v0 }}          |
| [**Visualizing Satellite Data**][vsd-n]                     | [{{ d1 }}][vsd-l] | [{{ d1 }}][vsd-d] | {{ v0 }}          |
| **Collaborative Coding, for Science!**                      | [{{ l1 }}][ccs-l] | [{{ d1 }}][ccs-d] | {{ v0 }}          |
| [*Matchups of in-situ Data With Satellite Data*][mup-n]     | [{{ l1 }}][mup-l] | [{{ d1 }}][mup-d] | {{ v0 }}          |
| [*Periodogram Analysis of Ocean Color Data*][lsp-n]         |                   | [{{ d1 }}][lsp-d] | {{ v0 }}          |
| [**OCSSW Processing Tools**][opt-n]                         |                   | [{{ d1 }}][opt-d] | {{ v0 }}          |
| [**Orientation to Level-2 Generator**][l2g-n]               |                   | [{{ d1 }}][l2g-d] | {{ v0 }}          |
| [*Rayleigh Correction for PACE by Machine Learning*][mlr-n] | [{{ l1 }}][mlr-l] | [{{ d1 }}][mlr-d] | {{ v0 }}          |
| **Distributed Processing**                                  |                   | {{ d0 }}          | {{ v0 }}          |
| [*HARP2 at Level-1C*][h1c-n]                                |                   | [{{ d1 }}][h1c-d] | {{ v0 }}          |
| [*SPEXone at Level-1C*][s1c-n]                              |                   | [{{ d1 }}][s1c-d] | {{ v0 }}          |
| [*HARP2 Aerosols at Level-2*][ha2-n]                        |                   | [{{ d1 }}][ha2-d] | {{ v0 }}          |
| [*SPEXone Aerosols at Level-2*][sa2-n]                      |                   | [{{ d1 }}][sa2-d] | {{ v0 }}          |
| *Environments for Reusable Projects*                        | {{ l0 }}          |                   | {{ v0 }}          |
| [Machine Learning Cloud Mask][mlc-n]                        |                   | [{{ d1 }}][mlc-d] |                   |
| [OCI Land Products][olp-n]                                  |                   | [{{ d1 }}][olp-d] |                   |
| [Projection and GeoTIFFs from Level-2][rio-n]               |                   | [{{ d1 }}][rio-d] | [{{ v1 }}][rio-v] |
| [OCI NO<sub>2</sub> Product Preview][no2-n]                 |                   | [{{ d1 }}][no2-d] |                   |
| Phytoplankton Pigments (GPig) Preview                       |                   | {{ d0 }}          |                   |
| Running GIOP wtih OCSSW                                     |                   | {{ d0 }}          |                   |
| [GISS Polarimetric Cloud Product][gpc-n]                    |                   | [{{ d1 }}][gpc-d] |                   |

<!--
(Ian) EarthCARE and LandSAT Access
(Skye) EMIT and PACE
(Chamara, Meng) Cloud Products
(Morgaine) SWOT and PACE
(Ian) VirtualiZarr
(???) github.com:ryan-edward-oshea/MDN_tutorials
-->
[eec-n]: notebooks/earthdata_cloud_access
[eec-l]: https://docs.google.com/presentation/d/1DmdHELzkqIwIB3mC7AbHSKUJHt7CSHNgV5X1aDeCppw/present
[eec-d]: nb:earthdata_cloud_access.ipynb

[vsd-n]: notebooks/oci_data_visualization
[vsd-l]: https://drive.usercontent.google.com/download?id=1lv10jP-jKJUh4JCxpse0oZyErMJurMYZ&export=download&authuser=0
[vsd-d]: nb:oci_data_visualization.ipynb

[ccs-l]: https://docs.google.com/presentation/d/1e5W_1MJsYemscRiRemVsGmc9KhAMD3supzhzDAarxLI/present
[ccs-d]: nb:blue-marble.ipynb

[mup-n]: notebooks/satellite_insitu_matchups
[mup-l]: https://docs.google.com/presentation/d/1IQlJtid0CGk2Nd-NGmKTCOCO9a9m4EQs/present
[mup-d]: nb:satellite_insitu_matchups.ipynb

[lsp-n]: notebooks/modis_lombscargle_periodogram
[lsp-d]: nb:modis_lombscargle_periodogram.ipynb

[opt-n]: notebooks/oci_ocssw_processing_overview
[opt-d]: nb:oci_ocssw_processing_overview.ipynb

[l2g-n]: notebooks/oci_ocssw_l2gen
[l2g-d]: nb:oci_ocssw_l2gen.ipynb

[mlr-l]: https://docs.google.com/presentation/d/1wUHsZke7bQ1oW5nAaZKVTqNI8H5sP_Ar/present
[mlr-n]: notebooks/rayleigh_correction
[mlr-d]: nb:rayleigh_correction.ipynb

[h1c-n]: notebooks/harp2_basic_visualizations
[h1c-d]: nb:harp2_basic_visualizations.ipynb

[s1c-n]: notebooks/spexone_basic_visualizations
[s1c-d]: nb:spexone_basic_visualizations.ipynb

[ha2-n]: notebooks/harp2_l2_aerosol_product
[ha2-d]: nb:harp2_l2_aerosol_product.ipynb

[sa2-n]: notebooks/spexone_l2_aerosol_product
[sa2-d]: nb:spexone_l2_aerosol_product.ipynb

[mlc-n]: notebooks/ml_cloud_mask
[mlc-d]: nb:ml_cloud_mask.ipynb

[olp-n]: notebooks/oci_terrestrial_data
[olp-d]: nb:oci_terrestrial_data.ipynb

[rio-n]: notebooks/oci_project_and_format
[rio-d]: nb:oci_project_and_format.ipynb
[rio-v]: https://www.youtube.com/watch?v=hOu8rPd_x6I&t=970s

[no2-n]: notebooks/oci_no2
[no2-d]: nb:oci_no2.ipynb

[gpc-n]: notebooks/harp2_l2_cloud_gpc_product
[gpc-d]: nb:harp2_l2_cloud_gpc_product.ipynb
