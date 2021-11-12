**General informations**

[![Python Version](https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8-blue.svg)](https://pypi.org/project/{{ cookiecutter.project_name }}/) [![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![Code Style: Black](https://img.shields.io/badge/code%20style-black-black.svg)](https://github.com/ambv/black)
[![SemVer](https://img.shields.io/badge/semver-2.0.0-green)](https://semver.org/)

----------------------------------------------------------
| Software repository | Latest release                                                                                                                             | Total downloads                                                                                                                    |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| Pypi                | [![PyPI version](https://badge.fury.io/py/{{ cookiecutter.project_name }}.svg)](https://pypi.org/project/{{ cookiecutter.project_name }}/) | [![Downloads](https://pepy.tech/badge/{{ cookiecutter.project_name }})](https://pepy.tech/project/{{ cookiecutter.project_name }}) |

**Code health**

----------------------------------------------------------
| Branch                                | Tests                                                                                                                                                                                                                                    | Coverage                                                                                                                                                                                                                                                                                               | Links                                                                                                                                                                                                                                                                                                                                                 | Documentation                                                                                                                                                                 | Deployment                                                                                                                                                                                                                                                                                                                                      | Activity                                                                                                                                                                                                                                                                     |
| ------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `{{ cookiecutter.main_branch_name }}` | [![test]({{ cookiecutter.github_project_path }}/workflows/test/badge.svg?branch={{ cookiecutter.main_branch_name }})]({{ cookiecutter.github_project_path }}/actions?query=workflow%3Atest+branch%3A{{ cookiecutter.main_branch_name }}) | [![codecov](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/branch/{{ cookiecutter.main_branch_name }}/graph/badge.svg)](https://codecov.io/gh/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/branch/{{ cookiecutter.main_branch_name }}) | [![links](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/workflows/check-links/badge.svg?branch={{ cookiecutter.main_branch_name }})](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/actions?query=workflow%3Acheck-links+branch%3A{{ cookiecutter.main_branch_name }}) | [![Documentation](https://readthedocs.org/projects/{{ cookiecutter.project_name }}/badge/?version=stable)](https://{{ cookiecutter.project_name }}.readthedocs.io/en/stable/) | [![publish](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/workflows/publish/badge.svg?branch={{ cookiecutter.main_branch_name }})](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/actions?query=branch%3A{{ cookiecutter.main_branch_name }}+workflow%3Apublish) | [![commit](https://img.shields.io/github/commits-since/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/0.1.0)](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/compare/0.1.0...{{ cookiecutter.main_branch_name }}) |

# What is {{ cookiecutter.project_name }}?


# How do I install {{ cookiecutter.project_name }}?


``{{ cookiecutter.project_name }}`` is available on PyPI, so you can install it with ``pip``:

```console
pip install {{ cookiecutter.project_name }}
```

If you want to use the most up to date version of the package which is under development and not released yet, you can install the package from github:

```console
pip install --upgrade git+https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}.git
```


# Getting started

The documentation contains:

- [A  "hello world" example]()

# Release and roadmap

The [release history](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/blob/{{ cookiecutter.main_branch_name }}/CHANGELOG.md) centralizes packages improvements across time. The main features coming in next releases are [listed on github milestones](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/milestones). Feel free to upvote/downvote and discuss prioritization in associated issues.

# Disclaimer

This package is still in active development. We use [SemVer](https://semver.org/) principles to version our releases. Until we reach `1.0.0` milestone, breaking changes will lead to `<minor>` version number increment, while releases which do not introduce breaking changes in the API will lead to `<patch>` version number increment.

If you want to see how to migrate from one version of `{{ cookiecutter.project_name }}` to another, see the [migration guide](../docs/migration_guide.md).

# Can I contribute?

We'd be happy to receive help to maintain and improve the package. Any PR will be considered (from typo in the docs to core features add-on) Please check the [contributing guidelines](https://github.com/{{ cookiecutter.github_username }}/{{ cookiecutter.project_name }}/blob/{{ cookiecutter.main_branch_name }}/CONTRIBUTING.md).

# Main contributors

The following people actively maintain, enhance and discuss design to make this package as good as possible:

- [{{ cookiecutter.full_name }}](https://github.com/{{ cookiecutter.github_username }})
