# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/kojake300/hydrator-demo
# cd into the cloned directory
git checkout 21f7c38679fe4f13607ead41c519997dbafcf7a5
helm template . --name-template gb --namespace default --include-crds
```
