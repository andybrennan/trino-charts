
Trino Community Kubernetes Helm Charts
===========

Fast distributed SQL query engine for big data analytics that helps you explore your data universe

This version includes [kempso's secretMounts branch](https://github.com/kempspo/charts/tree/secretMounts), also in [PR46](https://github.com/trinodb/charts/pull/46).

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add trino https://andybrennan.github.io/trino-charts/
```

You can then run `helm search repo trino` to see the charts.

Then you can install chart using:

```console
helm install my-trino trino/trino --version 0.8.1
```

## Documentation

You can find documentation about the chart [here](./charts/trino/README.md).
