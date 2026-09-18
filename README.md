# gagarin scoop bucket

[Scoop](https://scoop.sh) manifests for [`gg`](https://github.com/gagarin-cloud/gg),
the gagarin CLI.

```
scoop bucket add gagarin https://github.com/gagarin-cloud/scoop-bucket
scoop install gagarin/gg
```

`scoop update gg` takes the latest release.

The manifest in `bucket/` is written by the `gg` release workflow on every tag.
Don't edit it here — change `.goreleaser.yaml` in the gg repository instead.
