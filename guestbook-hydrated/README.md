# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/kojake300/hydrator-demo
# cd into the cloned directory
git checkout 13e735aa60fac2085a14ddb17dd692e4596a7963
helm template . --name-template gb --namespace default --include-crds
```
