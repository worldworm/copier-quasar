<h1 align="center">📋 copier-quasar</h1>
<p align="center">
  <i><a href="https://github.com/copier-org/copier">Copier</a> template for <a href="https://github.com/quasarframework/quasar">quasar</a> projects.</i>
</p>


<!-- Place https://shields.io/ badges here -->




## Features
- [Quasar](https://github.com/quasarframework/quasar) setup
- Continuous integration (CI) pipelines for Github Actions and GitLab CI/CD
- Docker support with build and publish pipelines
- [pre-commit](https://github.com/pre-commit/pre-commit) hooks
- [ESLint](https://github.com/eslint/eslint) code linter
- [VSCode](https://github.com/microsoft/vscode) configuration


## Requirements
First install copier:<br>
([from the official installation documentation](https://copier.readthedocs.io/en/stable/#installation))
```bash
pip install copier
```


## Usage



Make sure the requirements are met, then:
```bash
copier copy --trust "https://github.com/worldworm/copier-quasar.git" /new/project/path
```

### Update
To update a template after creating a project, run:
```bash
copier update --trust -a .project/.copier-answers.quasar.yml /some/project/path
```

## Explore more Copier templates
In addition to this template, there are a number of other Copier templates available. For an overview of all available templates, visit the [Templates Showcase repository](https://github.com/worldworm/copier-showcase).

---
<p align="center">
  <i>© <a href="https://github.com/worldworm">worldworm</a> 2023</i><br>
  <i>Licensed under <a href="https://github.com/worldworm/copier-quasar/blob/main/LICENSE">MIT</a></i><br>
</p>
