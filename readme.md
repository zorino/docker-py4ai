# docker-py4ai

see https://github.com/jupyter/docker-stacks/tree/master/base-notebook

```
docker pull zorino/docker-py4ai
# to save your work in ./work-dir (-v)
docker run -d --name py4ai -p 8888:8888 -v ./work-dir:/home/jovyan/work zorino/docker-py4ai
# go at http://locahost:8888
```

## packages
* numpy
* scipy
* scikit-learn
* tensorflow
* keras
* xgboost
* statsmodels
* seaborn
* jupyter
