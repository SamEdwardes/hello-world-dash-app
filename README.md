## Background

This is a simple dash web app deployed on heroku. The app uses dash, flask, and the MTCars data set.

## Resources

- [Guide from dash](https://dash.plot.ly/deployment) for full details.
- [YouTube video](https://www.youtube.com/watch?v=9VXrWKrNuoU) Short YouTube video (5 min) I found helpful explaining how to deploy python apps to Heroku.

## Environment

Use the following code with terminal to create the appropriate environment.

```
conda create --name hello-world-dash-app-env python=3.6.8
conda activate hello-world-dash-app-env

pip install pandas
pip install dash
pip install gunicorn
```

*I originally used conda to install the libraries but for some reason that resulted in deployment errors. When using pip to install everything worked.*

Save the requirements using pip and conda

```
pip freeze > requirements.txt # used by Heroku
conda list --export > requirements-conda.txt # you can re-use this to create virtual environment with conda
```