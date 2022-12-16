# moo

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] moo`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree moo`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init moo
kpt live apply moo --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
