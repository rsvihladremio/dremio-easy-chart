# dremio-easy-chart

Easy helm chart to setup a toy dremio. great for notebooks

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add dremio-easy https://rsvihladremio.github.io/dremio-easy-chart/

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
dremio-easy` to see the charts.

To install the dremio-easy chart:

    helm install my-dremio-easy dremio-easy/dremio-easy

To uninstall the chart:

    helm delete my-dremio-easy
