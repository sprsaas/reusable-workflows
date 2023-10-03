<!-- BEGIN_DOCS -->
<div align="center">

<a name="readme-top"></a>

<img alt="gif-header" src="https://github.com/sprsaas/.github/blob/main/.github/assets/gif-header.gif" width="225"/>

<h2>Reusable Workflows</h2>

[![Semantic Release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)]()
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)]()

---

<img alt="gif-about" src="https://github.com/sprsaas/.github/blob/main/.github/assets/gif-about.gif" width="225"/>

<p>This repository contains multiple reusable github actions</p>

<p>
  <a href="#-getting-started-">Getting Started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-templates-">Templates</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-links-">Links</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-versioning-">Versioning</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-troubleshooting-">Troubleshooting</a>
</p>

</div>

## ➤ Getting Started <a name="#-getting-started"></a>

### Setup

To configure your system for the development of this project, follow the steps below:

- Install [asdf](https://asdf-vm.com/) to manage runtime dependencies.
- Install runtime dependencies.

```bash
cut -d' ' -f1 .tool-versions | xargs -I{} sh -c 'asdf plugin add "$1"' -- {} && asdf install
```

- Run task from the root of the repository to see available commands. We use task in place of make for this project. See [Taskfile.yml](Taskfile.yml) for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ➤ Templates <a name="#-templates"></a>

This is the list of templates we have implemented:

- [Reusable docker build](./github/workflows/reusable-docker-build.yml)
- [Reusable quality](./github/workflows/reusable-quality.yml)

### Variables

These are the variables we use in the templates:

- COMPOSER_AUTH
- PR_LINT_GITHUB_TOKEN
- SCALEWAY_REGISTRY_USER
- SCALEWAY_REGISTRY_PASSWORD
- SEMANTIC_RELEASE_TOKEN

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ➤ Links <a name="-links"></a>

- [GitHub Actions Documentation](https://docs.github.com/en/actions)
  - [Reusable workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows)
- [GitHub Actions Key Concepts](.github/docs/KEY_CONCEPTS.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ➤ Versioning <a name="#-versioning"></a>

To check the change history, please access the [**CHANGELOG.md**](CHANGELOG.md) file.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ➤ Troubleshooting <a name="#-troubleshooting"></a>

If you have any problems, [open an issue in this project](https://github.com/sprsaas/.github/issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## ➤ Show your support <a name="-show-your-support"></a>

<div align="center">

Give me a ⭐️ if this project helped you!

<img alt="gif-footer" src="https://github.com/sprsaas/.github/blob/main/.github/assets/gif-footer.gif" width="225"/>

Made with 💜 by [sprsaas team](https://github.com/sprsaas) 👋 inspired on [readme-md-generator](https://github.com/kefranabg/readme-md-generator)

</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<!-- END_DOCS -->
