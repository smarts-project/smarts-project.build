# smarts-project.build
[![SMARTS CD Docker](https://github.com/smarts-project/smarts-project.build/actions/workflows/cd-docker.yml/badge.svg)](https://github.com/smarts-project/smarts-project.build/actions/workflows/cd-docker.yml)
[![SMARTS CD PyPI](https://github.com/smarts-project/smarts-project.build/actions/workflows/cd-pypi.yml/badge.svg)](https://github.com/smarts-project/smarts-project.build/actions/workflows/cd-pypi.yml)
[![readthedocs-auto-build](https://github.com/smarts-project/smarts-project.build/actions/workflows/readthedocs-auto-build.yml/badge.svg)](https://github.com/smarts-project/smarts-project.build/actions/workflows/readthedocs-auto-build.yml)

This is a simple set of utilities that manage building the SMARTS simulation platform releases.


### TODO
- Only update PyPI if package version has changed. Use caching to determine if there is a change: https://docs.github.com/en/actions/using-workflows/caching-dependencies-to-speed-up-workflows#comparing-artifacts-and-dependency-caching
- Build docker images when there is a new SMARTS version.
