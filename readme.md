# mantis-helm-chart

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

    helm repo add weinmann-emt https://weinmann-emt.github.io/mantis-chart/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.

To install the `mantis` chart:

    helm install mantis weinmann-emt/mantis

To uninstall the chart:

    helm delete mantis

## Contributing

Contributions welcome, send PRs.
