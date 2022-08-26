# Python template project

Opinionated project templates for Python, intended for personal use.

In this repository, there are currently two project templates:

- [`app`](./app): This is for projects that are not supposed to be published as Python packages (e.g. to PyPI). Reproducibility is the highest priority, and therefore each dependency is pinned to an exact version.
- [`package`](./package): This is for projects that are Python packages and are supposed to be installed within a Python environment alongside other packages. Maximum compatibility is the highest priority, and therefore versioning needs to be as lenient as possible.
