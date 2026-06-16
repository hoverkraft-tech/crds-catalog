# CRDs Catalog

<div align="center">
  <img src=".github/logo.svg" width="60px" align="center" alt="Logo for CRDs Catalog" />
</div>

---

![GitHub Verified Creator](https://img.shields.io/badge/GitHub-Verified%20Creator-4493F8?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxNiAxNiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2IiBmaWxsPSJyZ2IoNjgsIDE0NywgMjQ4KSI+CiAgPHBhdGggZD0ibTkuNTg1LjUyLjkyOS42OGMuMTUzLjExMi4zMzEuMTg2LjUxOC4yMTVsMS4xMzguMTc1YTIuNjc4IDIuNjc4IDAgMCAxIDIuMjQgMi4yNGwuMTc0IDEuMTM5Yy4wMjkuMTg3LjEwMy4zNjUuMjE1LjUxOGwuNjguOTI4YTIuNjc3IDIuNjc3IDAgMCAxIDAgMy4xN2wtLjY4LjkyOGExLjE3NCAxLjE3NCAwIDAgMC0uMjE1LjUxOGwtLjE3NSAxLjEzOGEyLjY3OCAyLjY3OCAwIDAgMS0yLjI0MSAyLjI0MWwtMS4xMzguMTc1YTEuMTcgMS4xNyAwIDAgMC0uNTE4LjIxNWwtLjkyOC42OGEyLjY3NyAyLjY3NyAwIDAgMS0zLjE3IDBsLS45MjgtLjY4YTEuMTc0IDEuMTc0IDAgMCAwLS41MTgtLjIxNUwzLjgzIDE0LjQxYTIuNjc4IDIuNjc4IDAgMCAxLTIuMjQtMi4yNGwtLjE3NS0xLjEzOGExLjE3IDEuMTcgMCAwIDAtLjIxNS0uNTE4bC0uNjgtLjkyOGEyLjY3NyAyLjY3NyAwIDAgMSAwLTMuMTdsLjY4LS45MjhjLjExMi0uMTUzLjE4Ni0uMzMxLjIxNS0uNTE4bC4xNzUtMS4xNGEyLjY3OCAyLjY3OCAwIDAgMSAyLjI0LTIuMjRsMS4xMzktLjE3NWMuMTg3LS4wMjkuMzY1LS4xMDMuNTE4LS4yMTVsLjkyOC0uNjhhMi42NzcgMi42NzcgMCAwIDEgMy4xNyAwWk03LjMwMyAxLjcyOGwtLjkyNy42OGEyLjY3IDIuNjcgMCAwIDEtMS4xOC40ODlsLTEuMTM3LjE3NGExLjE3OSAxLjE3OSAwIDAgMC0uOTg3Ljk4N2wtLjE3NCAxLjEzNmEyLjY3NyAyLjY3NyAwIDAgMS0uNDg5IDEuMThsLS42OC45MjhhMS4xOCAxLjE4IDAgMCAwIDAgMS4zOTRsLjY4LjkyN2MuMjU2LjM0OC40MjQuNzUzLjQ4OSAxLjE4bC4xNzQgMS4xMzdjLjA3OC41MDkuNDc4LjkwOS45ODcuOTg3bDEuMTM2LjE3NGEyLjY3IDIuNjcgMCAwIDEgMS4xOC40ODlsLjkyOC42OGMuNDE0LjMwNS45NzkuMzA1IDEuMzk0IDBsLjkyNy0uNjhhMi42NyAyLjY3IDAgMCAxIDEuMTgtLjQ4OWwxLjEzNy0uMTc0YTEuMTggMS4xOCAwIDAgMCAuOTg3LS45ODdsLjE3NC0xLjEzNmEyLjY3IDIuNjcgMCAwIDEgLjQ4OS0xLjE4bC42OC0uOTI4YTEuMTc2IDEuMTc2IDAgMCAwIDAtMS4zOTRsLS42OC0uOTI3YTIuNjg2IDIuNjg2IDAgMCAxLS40ODktMS4xOGwtLjE3NC0xLjEzN2ExLjE3OSAxLjE3OSAwIDAgMC0uOTg3LS45ODdsLTEuMTM2LS4xNzRhMi42NzcgMi42NzcgMCAwIDEtMS4xOC0uNDg5bC0uOTI4LS42OGExLjE3NiAxLjE3NiAwIDAgMC0xLjM5NCAwWk0xMS4yOCA2Ljc4bC0zLjc1IDMuNzVhLjc1Ljc1IDAgMCAxLTEuMDYgMEw0LjcyIDguNzhhLjc1MS43NTEgMCAwIDEgLjAxOC0xLjA0Mi43NTEuNzUxIDAgMCAxIDEuMDQyLS4wMThMNyA4Ljk0bDMuMjItMy4yMmEuNzUxLjc1MSAwIDAgMSAxLjA0Mi4wMTguNzUxLjc1MSAwIDAgMSAuMDE4IDEuMDQyWiI+PC9wYXRoPgo8L3N2Zz4K)
[![Continuous Integration](https://github.com/hoverkraft-tech/crds-catalog/actions/workflows/__main-ci.yml/badge.svg)](https://github.com/hoverkraft-tech/crds-catalog/actions/workflows/__main-ci.yml)
[![GitHub tag](https://img.shields.io/github/tag/hoverkraft-tech/crds-catalog?include_prereleases=&sort=semver&color=blue)](https://github.com/hoverkraft-tech/crds-catalog/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

Catalog of Kubernetes `CustomResourceDefinition` JSON schemas for validating custom resources with tools such as `kubeconform` or `datree`.

## Purpose

Kubernetes native schemas do not cover custom resources. This repository provides JSON schemas for selected CRDs so they can be validated in CI, locally, or in editors without access to a live cluster.

Use cases:
- validate manifests with `kubeconform`
- validate manifests with `datree`
- improve editor validation / autocompletion for CRs
- keep a local, versioned catalog of CRD schemas

This aligns with how `kubeconform` supports additional schema locations for CRDs and how CRD catalogs are commonly consumed for offline or shift-left validation. citeturn0search2turn0search4turn0search1

## Repository layout

Schemas are grouped by API group at the repository root.

Example:
- `cert-manager.io/`
- `monitoring.coreos.com/`
- `snapshot.storage.k8s.io/`

Inside each directory, schema files should follow a predictable naming convention per resource kind and API version so validation tools can resolve them consistently. This matches the common CRD catalog pattern used with `kubeconform`. citeturn0search1turn0search2

## Usage

### Kubeconform

`kubeconform` supports one or more custom schema locations for CRDs. citeturn0search2turn0search4

```bash
kubeconform \
  -schema-location default \
  -schema-location 'https://raw.githubusercontent.com/hoverkraft-tech/crds-catalog/main/{{.Group}}/{{.ResourceKind}}_{{.ResourceAPIVersion}}.json' \
  path/to/manifests.yaml
```

### Datree

`datree` can validate Kubernetes manifests locally as part of a shift-left workflow. citeturn0search0turn0search1

If you use this repository as a schema source in your workflow, keep the catalog available locally or reference the raw files directly from your validation pipeline.

## Contributing

Contributions should add or update JSON schemas for public Kubernetes CRDs.

Guidelines:
- group schemas by API group
- keep file naming consistent
- prefer generated schemas from upstream CRDs when possible
- update existing schemas when CRDs change upstream
- avoid adding unrelated tooling or generated noise

For missing CRDs, the safest approach is to extract or generate schemas from the upstream CRD definitions and commit the resulting JSON schema artifacts. This is consistent with how CRD validation catalogs are typically maintained. citeturn0search1turn0search2

## Scope

This repository is intended to be:
- simple
- consumable by automation
- easy to vendor or mirror internally

It is **not** intended to replace upstream CRD sources. Upstream projects remain the source of truth for CRD definitions.

## License

Add the project license here if/when a license file is included in the repository.
