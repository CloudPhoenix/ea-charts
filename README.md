## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add ea-charts https://cloudphoenix.github.io/ea-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
ea-charts` to see the charts.

To install the <chart-name> chart:

    helm install my-<chart-name> ea-charts/<chart-name>

To uninstall the chart:

    helm uninstall my-<chart-name>
