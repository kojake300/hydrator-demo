# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/kojake300/hydrator-demo
# cd into the cloned directory
git checkout 6ad2492607471d5eb0fd4a985c9eb00d85795a11
helm template . --name-template gb --namespace default --include-crds
```
