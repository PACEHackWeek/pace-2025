# PACE Hackweek JupyterBook

This the JupyterBook content for the PACE Hackweek 2025.

![image](https://github.com/noaa-nwfsc/Hackweek-2024-book/assets/2545978/8f4eda29-eec2-4263-bc1f-600ef5567996)

## Users

This repo is the source for our website: https://pacehackweek.github.io/pace-2025/. Go check it out!

## Developers

### Changes other than notebooks

1. Clone this repo, or pull updates.
1. Make the necessary changes, and commit them to a new branch, and push.
1. Create a PR and add the `preview` label.
1. A link to a website preview will appear in the comments.
   Check to ensure that it looks good and make add commits as necessary.
1. Once the PR is reviewed by another team member, it can be merged.

### New or updated notebooks

1. Clone this repo, or pull updates.
1. Clone the oceandata-noteboooks in an adjacent directory, and follow those README instructions to build that book.
1. Copy updates to the executed notebooks from the src/_build folder of the oceandata-notebooks repo to the book in this repo.
   ```
   rsync -a ../oceandata-notebooks/src/_build/jupyter_execute/notebooks/hackweek/ book/presentations/hackweek/
   ```
1. Commit to a new branch and proceed as above with a PR.

### Local preview

Install the tools you need.

```shell
uv tool install --with jinja_markdown cookiecutter
uv tool install jupyter-book # probably <2?
```

Build the HTML.

```shell
./scripts/build_resources.sh
```

Run a local web server.

```shell
python -m http.server -d book/_build/html/
```

## Template courtesy of (by permission) eScience University of Washington

This is a clone of the eScience template repository designed to streamline creating two linked websites for a [UW eScience Hackweek](https://uwhackweek.github.io/hackweeks-as-a-service/intro.html).

Please see the [eScience repository template](https://github.com/uwhackweek/jupyterbook-template) for usage, contributors and citation information.

Setting up the template: Read the instructions [here](https://github.com/uwhackweek/jupyterbook-template/blob/main/docs/), in particular you will need to [setup netlify](https://github.com/uwhackweek/jupyterbook-template/blob/main/docs/netlify-setup.md) for preview feature.
