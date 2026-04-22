[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19699586.svg)](https://doi.org/10.5281/zenodo.19699586)

# PACE Data Hackweek 2025

This the conent of the landing page and JupyterBook for the PACE Data Hackweek 2025.

![image](https://github.com/noaa-nwfsc/Hackweek-2024-book/assets/2545978/8f4eda29-eec2-4263-bc1f-600ef5567996)

## Users

This repo is the source for our [website](https://pacehackweek.github.io/pace-2025/). Go check it out!

## Developers

This repo came from a template and therefore has extra and complicated stuff!
One change made to the template is in `scripts/build_resources.sh`, which now cleans out the "_sources".

### Changes other than notebooks

1. Clone this repo, or pull updates.
1. Make the necessary changes, and commit them to a new branch, and push.
1. Create a PR and add the `preview` label.
1. A link to a website preview will appear in the PR comments.
   Check to ensure the website preview looks good and add commits as necessary.
1. Request a review from another hackweek mentor and merge once approved!

### New or updated notebooks

1. Clone this repo, or pull updates.
1. Clone the oceandata-noteboooks in an adjacent directory and follow the CONTRIBUTING section on rendering the HTML, which
   updates the executed notebooks in that book's `_build` directory.
1. Run the steps in WORKFLOW.md to:
  - link to the executed notebooks
  - create a conda environment
  - generate a preview. 
1. Commit to a new branch, commit changed notebooks (yes!, ugh!) and proceed as above with a PR, likely skipping the review!

## Template courtesy of (by permission) eScience University of Washington

This is a clone of the eScience template repository designed to streamline creating two linked websites for a [UW eScience Hackweek](https://uwhackweek.github.io/hackweeks-as-a-service/intro.html).

Please see the [eScience repository template](https://github.com/uwhackweek/jupyterbook-template) for usage, contributors and citation information.

Setting up the template: Read the instructions [here](https://github.com/uwhackweek/jupyterbook-template/blob/main/docs/), in particular you will need to [setup netlify](https://github.com/uwhackweek/jupyterbook-template/blob/main/docs/netlify-setup.md) for preview feature.
