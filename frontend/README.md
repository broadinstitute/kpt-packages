# frontend

## Description
kpt package for provisioning standalone Prometheus frontend UI for Google Managed Prometheus

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] frontend`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree frontend`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init frontend
kpt live apply frontend --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
