# grafana

## Description
kpt package for provisioning Grafana on Google Managed Prometheus

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] grafana`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree grafana`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init grafana
kpt live apply grafana --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
