# @LinkedMink .github 

[![Validate Status](https://github.com/LinkedMink/.github/actions/workflows/validate-main.yml/badge.svg)](https://github.com/LinkedMink/.github/actions?query=workflow%3A%%22validate-main%22)

This repo contains:

- Default repo files
- Reusable GitHub Actions Workflows
  - Templates for Workflows

## Command Reference

```sh
pip install --user yamllint
python -m yamllint -c yamllint-config.yaml \
  .github/workflows/*.yml \
  workflow-templates/nodejs/*.yml
```
