# [ssciwr.github.io/jupyter-slides-template](https://ssciwr.github.io/jupyter-slides-template)

A simple way to convert a jupyter notebook into an online web presentation.

The notebook [index.ipynb](index.ipynb) is converted into [reveal.js](https://revealjs.com/) html slides and hosted by github pages at [ssciwr.github.io/jupyter-slides-template](https://ssciwr.github.io/jupyter-slides-template)

## How to set up

- click the 'Use this template' button to create your own repo based on this one
- enable gh-pages for your repo: Settings -> Pages -> Source branch: gh-pages
- (optional) go to https://pre-commit.ci/ to enable automatic code formatting for your repo
- (optional) install pre-commit to also do this locally
  - `pip install pre-commit`
  - `pre-commit install`
- make a change to index.ipynb, see the changes at `YOUR_USERNAME.github.io/YOUR_REPO_NAME`
- add any Python libraries your notebook needs to [requirements.txt](requirements.txt)
