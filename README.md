# Docker hub Automated CircleCI Deployments

[![CircleCI](https://circleci.com/gh/CIRCLECI-GWP/python-app-dockerhub.svg?style=svg)](https://circleci.com/gh/CIRCLECI-GWP/python-app-dockerhub)

<p align="center"><img src="https://avatars3.githubusercontent.com/u/59034516"></p>

A Python API project setup for the purpose of demonstrating how to deploy a built image to Docker hub using CircleCI.

## Setting up the project

### Clone the repository:

run the following command on your terminal to clone the repository:

```bash
git clone https://github.com/CIRCLECI-GWP/python-app-dockerhub.git

cd python-app-dockerhub
```

### install the dependencies

Install the dependencies using the following command:

```bash
pip3 install -r requirements.txt
```

## Running tests

```bash
pytest
```

## Details

This repo is built following a tutorial published on CircleCI blog under the CircleCI Guest Writer Program.

- Blog post: [Dockerizing a Python App and Automating Deployments to Docker Hub][blog]
- Author's GitHub profile: [Waweru Mwaura][author]

### About CircleCI Guest Writer Program

Reviewers: [Ron Powell][ron], [Stanley Ndagi][stan], [Amos Omondi][amos]

[blog]: https://circleci.com/blog/dockerize-a-python-app-with-automated-dockerhub-deployments-using-circleci/
[author]: https://github.com/mwaz
[gwp-program]: https://circle.ci/3ahQxfu
[ron]: https://github.com/ronpowelljr
[stan]: https://github.com/NdagiStanley
[amos]: https://github.com/amos-o
