# helm-chart
helm-chart

from: https://medium.com/@mattiaperi/create-a-public-helm-chart-repository-with-github-pages-49b180dbb417

**https://team-parallax.github.io/helm-charts**

## TODO
create ci/cd to package the charts with:
```
helm lint helm-chart-sources/*
helm package helm-chart-sources/*
helm repo index --url https://team-parallax.github.io/helm-charts/ .
```

## Install repo/chart
```
helm repo add narkuma-charts https://team-parallax.github.io/helm-charts/
helm install fider-app narkuma-charts/fider
```
