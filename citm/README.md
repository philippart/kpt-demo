# citm

## Description
citm description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] citm`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree citm`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init citm
kpt live apply citm --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
