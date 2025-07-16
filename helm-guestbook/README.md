
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/jiaxwu/argocd-example-apps
# cd into the cloned directory
git checkout 170786e163bdf22ac045b22aa2d2bf3501e9ee0a
helm template . --name-template development-helm-guestbook --include-crds
```