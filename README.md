## Background

This is a simple dash web app deployed on heroku.

## Resources

- [Guide from dash](https://dash.plot.ly/deployment) for full details.
- [YouTube video](https://www.youtube.com/watch?v=9VXrWKrNuoU)

## How to create

*Note these steps are not comprehensive*.

**Step 1:** set up the virtual environment

```
conda create --name dash-app-env python=3.7
conda activate dash-app-env
conda install -c conda-forge dash
conda install -c plotly plotly
conda install -c anaconda gunicorn
conda install -c conda-forge dash
conda install -c anaconda pandas
```

**Step 2:** set up the git

```
git init
```