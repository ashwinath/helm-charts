# Helm Charts

## Usage

First, add the repository:
    helm repo add ashwinath https://ashwinath.github.io/helm-charts/

If you had already added this repo earlier, run `helm repo update` to retrieve the latest versions of the packages. You can then run `helm search repo turing` to see the charts.

To install the \<chart-name\> chart:
    helm install <release-name> ashwinath/<chart-name>

To uninstall the chart:
    helm delete <release-name>
