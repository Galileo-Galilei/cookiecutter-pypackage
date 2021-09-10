## Introduction

This is my personal template for creating python packages. This is heavily inspired from [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage). The main additional features are:
- Move the CI to github actions to avoid depending on a third party tool
- Add pre-commit to enforce code linting and formatting
- Add broken link checker in documentation
- Add codecov integration
-  Have an opinionated development workflow: 
   -  the "create-release-candidate" manual button in the "Actions" section opens a PR with version bumps
   -  Click the "publish" manual workflow to trigger PyPI deployment
- Enforce SemVer

## How to use it

Install ``cookiecutter`` in a conda environment and run it to create the project locally:

```bash
conda create -n cc_env python=3.7 -y
conda activate cc_env
pip install cookiecutter
cookiecutter gh:Galileo-Galilei/cookiecutter-pypackage
```

Push to github:

```bash
git init
git add .
git commit -am ":tada: Creating the project structure"
git push -u origin main
```

Then you have to set up the following external connections: 
- Go to [Codecov](https://app.codecov.io/gh) and import your project. You will get a ``CODECOV_TOKEN`` to add to your github secrets.
- Go to [Snyk](https://app.snyk.io/) and import your project.
- Go to [Read the Docs](https://readthedocs.org/accounts/login/) and import your project.
- In your Github repository, go to ``Settings`` > ``Secrets`` and add the following keys:
  - CODECOV_TOKEN
  - PYPI_PASSWORD
  - SNYK_TOKEN
- In your Github repository, go to ``Settings`` > ``Webhooks`` and add the following keys:
  - Read the Docs
  - Snyk