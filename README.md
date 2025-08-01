## Common 
this is public repo for serving badges info and instructions for private projects

### Badges Templates for private repos
![Python](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/gxxeel/badges/main/badges/python-version-badge.json)
[![codecov](https://codecov.io/gh/gxxeel/fastapi-sqlmodel/graph/badge.svg?token=GYDPpAiexy)](https://codecov.io/gh/gxxeel/fastapi-sqlmodel)
[![Quality Gate](https://sonarcloud.io/api/project_badges/measure?gxxeel_fastapi-sqlmode&metric=alert_status)](https://sonarcloud.io/dashboard?id=gxxeel_fastapi-sqlmodel)
[![Last Commit](https://img.shields.io/github/last-commit/gxxeel/fastapi-sqlmodel/?style=for-the-badge)](https://github.com/gxxeel/fastapi-sqlmodel)
[![GitHub Actions](https://img.shields.io/github/actions/workflow/status/gxxeel/fastapi-sqlmodel/testing.yml?style=for-the-badge)](https://github.com/gxxeel/fastapi-sqlmodel/actions)

### Badges Templates for public repos
[![Read the Docs](https://img.shields.io/readthedocs/fastapi-jsonapi?style=for-the-badge)](https://fastapi-jsonapi.readthedocs.io/en/latest/)
[![📖 Docs (gh-pages)](https://github.com/mts-ai/FastAPI-JSONAPI/actions/workflows/documentation.yaml/badge.svg)](https://mts-ai.github.io/FastAPI-JSONAPI/)




## Badges setup for private repos
1. for python
- use this repo and set python-badge with version into your private repo
2. for codecov
-  register on https://app.codecov.io and connect your repo via github
- into project configuration -> badges & graphs -> use markdown and insert into your readme
- you also need CODECOV_TOKEN for actions secreats and github-workflow to run tests with codecov
3. for sonarcloud
- register at sonarcube-cloud with sonarcloud.io and connect your repo via github
- set organisation name and your project name will be "gxxeel_fastapi-sqlmodel", {your_org}_{project_repo_name}
- create SONAR_TOKEN and add it into your action secrets
- setup branch and analysys method(manual with github actions or auto (on every PR into selected branch))
- if you use manual method - add github/workflow into your project
4. 
5. 