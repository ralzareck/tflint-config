# tflint-config
A shared tflint configuration file for terraform workflows. As documented on the [setup-tflint](https://github.com/terraform-linters/setup-tflint) GitHub Action documentation:

```yaml
- uses: terraform-linters/setup-tflint@v4
- uses: terraform-linters/tflint-load-config-action@v1
  with:
    source-repo: me/tflint-config
- run: tflint -f compact
```
