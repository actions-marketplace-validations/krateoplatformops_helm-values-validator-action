# Krateo helm values validator action

This action checks if all the properties in the values.yaml are used and if some files in templates folder has missing value.

## Inputs

### `chart-folder`

The folder of the helm chart. Default `"./chart"`.

### `stop-if-find-orphans`

Stop the action if found some orphan. Default `"true"`.

### `stop-on-error`

Stop the action in case of error. Default `"true"`.

## Example usage

```yaml
uses: krateoplatformops/helm-values-validator-action@v1.0.2
```

```yaml
uses: krateoplatformops/helm-values-validator-action@v1.0.2
with:
  chart-folder: './chart'
```
