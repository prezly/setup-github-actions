# Setup Github Actions environment for Prezly

Usage:

```yml
  steps:
    - name: Setup environment
      uses: prezly/setup-github-actions@v1
      with:
        node: 16      # optional, defaults to "16"
        pnpm: "8.4.0" # optional, defaults to "8.4.0"
```
