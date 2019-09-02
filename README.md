## Steps

See [guide from dash](https://dash.plot.ly/deployment) for full details.

**Step 1:** set up the virtual environment

```
conda create --name dash-app-env python=3.7
conda activate dash-app-env
conda install -c conda-forge dash
conda install -c plotly plotly
conda install -c anaconda gunicorn
```

**Step 2:** set up the git

```
git init
```