# gcp-load-balancer

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] gcp-load-balancer`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree gcp-load-balancer`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```shell
kpt live init gcp-load-balancer
kpt live apply gcp-load-balancer --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
