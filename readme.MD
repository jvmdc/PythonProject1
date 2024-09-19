# 31474

## Current behavior

Renovate uses version `3.12.6` when Python versioning constraint in `pyproject.toml` is set to `<=3.12`. As seen in https://github.com/jvmdc/PythonProject1/pull/3, this is not accepted by the project.

## Expected behavior

Renovate should use version `3.12.0` or lower

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/31474
