# testpackage1

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] testpackage1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree testpackage1`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init testpackage1
kpt live apply testpackage1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
