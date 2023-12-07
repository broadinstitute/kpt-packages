# kpt-packages
A Catalog of [Kpt](https://kpt.dev/) Packages and Blueprints 

## What is a Kpt Package?

A Kpt package is a collection of Kubernetes resources that are managed together as a unit. A package can be a single Kubernetes resource, or a collection of resources such as a Deployment, Service, and ConfigMap. A package can also be a collection of other packages.

The packages in this repo can be used alone or as part of a larger application. They can be used to create a new application, or to add functionality to an existing application.  To learn more about packages, see the [Kpt Packages Overview](https://kpt.dev/book/02-concepts/01-packages).

You can install a package by running `kpt pkg get https://github.com/broadinstitute/kpt-packages/grafana  --for-deployment` 

You can then update the package inputs to set the package parameters.  Running `kpt fn render grafana` will render the package with the updated inputs.  

