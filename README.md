# spring-petclinic-helmfile

## asdf configuration

This repo uses `asdf` to configure the versions of `helm` & `helmfile`, you'll need to make sure you have
the correct `asdf` plugins installed.

```
asdf plugin add helm
asdf plugin-add helmfile https://github.com/feniix/asdf-helmfile.git
```

Validate your install with:

```
asdf current
```

If you don't already have the helm-diff plugin installed, you'll need to add it with:

```
helm plugin install https://github.com/databus23/helm-diff
```
