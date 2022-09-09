# minecraft

## Description
kpt package for minecraft deployment

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] minecraft`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree minecraft`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init minecraft
kpt live apply minecraft --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
