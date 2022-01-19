# gatorgradle-action

This GitHub Action runs GatorGradle.

## Usage

Basic workflow to run GatorGradle on every push:

```yaml
name: Grade
on: [push]
jobs:
  grade:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository
        uses: actions/checkout@v2
      - name: Run GatorGradle
        uses: GatorEducator/gatorgradle-action@v1
```
