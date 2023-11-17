# atlantis

## Description

Kubernetes Deployment of  Atlantis

## Usage

### Fetch the package

`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] atlantis`
Details: <https://kpt.dev/reference/cli/pkg/get/>

### View package content

`kpt pkg tree atlantis`
Details: <https://kpt.dev/reference/cli/pkg/tree/>

### Apply the package

```shell
kpt live init atlantis
kpt live apply atlantis --reconcile-timeout=2m --output=table
```

Details: <https://kpt.dev/reference/cli/live/>
