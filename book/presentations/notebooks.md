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
| *Matchups of in-situ Data With Satellite Data*              | {{ l0 }}          | {{ d0 }}          | {{ v0 }}          |
| [*Periodogram Analysis of Ocean Color Data*][lsp-n]         | {{ l0 }}          | {{ d0 }}          | {{ v0 }}          |
| [**OCSSW Processing Tools**][opt-n]                         |                   | {{ d0 }}          | {{ v0 }}          |
| **Orientation to Level-2 Generator**                        |                   | {{ d0 }}          | {{ v0 }}          |
| *Rayleigh Correction for PACE by Machine Learning*          | {{ l0 }}          | {{ d0 }}          | {{ v0 }}          |
| **Distributed Processing**                                  |                   | {{ d0 }}          | {{ v0 }}          |
| [*HARP2 at Level-1C*][h1c-n]                                |                   | [{{ d0 }}][h1c-d] | {{ v0 }}          |
| [*SPEXone at Level-1C*][s1c-n]                              |                   | [{{ d0 }}][s1c-d] | {{ v0 }}          |
| [*HARP2 Aerosols at Level-2*][ha2-n]                        |                   | [{{ d0 }}][ha2-d] | {{ v0 }}          |
| [*SPEXone Aerosols at Level-2*][sa2-n]                      |                   | [{{ d0 }}][sa2-d] | {{ v0 }}          |
| *Environments for Reusable Projects*                        | {{ l0 }}          |                   | {{ v0 }}          |
| Machine Learning Cloud Mask                                 |                   | {{ d0 }}          |                   |
| [OCI Land Products][olp-n]                                  |                   | {{ d0 }}          |                   |
| [Projection and GeoTIFFs from Level-2][rio-n]               |                   | {{ d0 }}          | [{{ v1 }}][rio-v] |
| [OCI NO<sub>2</sub> Product Preview][no2-n]                 |                   | {{ d0 }}          |                   |
| Phytoplankton Pigments (GPig) Preview                       |                   | {{ d0 }}          |                   |
| Running GIOP wtih OCSSW                                     |                   | {{ d0 }}          |                   |

<!--
(Ian) EarthCARE and LandSAT Access
(Skye) EMIT and PACE
(Chamara, Meng) Cloud Products
(Morgaine) SWOT and PACE
(Ian) VirtualiZarr
(???) github.com:ryan-edward-oshea/MDN_tutorials
-->
[eec-n]: notebooks/earthdata_cloud_access
[eec-l]: https://docs.google.com/presentation/d/1DmdHELzkqIwIB3mC7AbHSKUJHt7CSHNgV5X1aDeCppw/present?slide=id.p1
[eec-d]: nb:earthdata_cloud_access.ipynb

[vsd-n]: notebooks/oci_data_visualization
[vsd-l]: https://drive.usercontent.google.com/download?id=1lv10jP-jKJUh4JCxpse0oZyErMJurMYZ&export=download&authuser=0
[vsd-d]: nb:oci_data_visualization.ipynb

[ccs-l]: https://docs.google.com/presentation/d/1e5W_1MJsYemscRiRemVsGmc9KhAMD3supzhzDAarxLI/present?slide=id.p1

[lsp-n]: notebooks/modis_lombscargle_periodogram

[opt-n]: notebooks/oci_ocssw_processing_overview

[h1c-n]: notebooks/harp2_basic_visualizations
[h1c-d]: nb:harp2_basic_visualizations.ipynb

[s1c-n]: notebooks/spexone_basic_visualizations
[s1c-d]: nb:spexone_basic_visualizations.ipynb

[ha2-n]: notebooks/harp2_l2_aerosol_product
[ha2-d]: nb:harp2_l2_aerosol_product.ipynb

[sa2-n]: notebooks/spexone_l2_aerosol_product
[sa2-n]: nb:spexone_l2_aerosol_product.ipynb

[olp-n]: notebooks/oci_terrestrial_data

[rio-n]: notebooks/oci_project_and_format
[rio-v]: https://www.youtube.com/watch?v=hOu8rPd_x6I&t=970s

[no2-n]: notebooks/oci_no2
