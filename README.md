# Google Summer of Code 2022

![ViewCount](https://views.whatilearened.today/views/github/its-sushant/GSoC-23.svg)
![GitHub](https://img.shields.io/github/followers/its-sushant?style=social)
![GSoC @ FOSSology](/static/gsocHeader.png)

<div align = "center"><h2>Adding CycloneDX Report Generation to FOSSology</h2></div>

## PROJECT OVERVIEW

[FOSSology]((https://www.fossology.org/)) is a well-known open-source license
scanning toolkit used to analyze and manage the licenses associated with
software components in a codebase. Previously, FOSSology generated license
compliance reports in [SPDX (Software Package Data Exchange)](https://spdx.dev/)
format. However, there was a need to extend its capabilities by adding support
for generating reports in [CycloneDX](https://cyclonedx.org/) format.

CycloneDX is an emerging industry standard for representing software bill of
materials (SBOM) information, which includes details about software components,
their dependencies, and associated licenses. The goal of this project was to
enhance FOSSology's functionality by implementing a custom agent capable of
generating CycloneDX reports, thereby enabling users to obtain SBOM information
in a widely recognized and interoperable format.

The successful completion of this project not only added a new feature to
FOSSology but also demonstrated the contributor's expertise in open-source
development, license compliance, and software engineering. The newly added
CycloneDX report generation capability enhances FOSSology's usefulness to the
software development community, facilitating better license management and
compliance efforts.

<h2>CONTRIBUTIONS <img src="https://media.giphy.com/media/dxn6fRlTIShoeBr69N/giphy.gif" width="15"></h2>


## MAJOR PULL REQUESTS

- [Feat(model): Add agent for logistic regression model](https://github.com/fossology/atarashi/pull/100)
- [Feat(model): Add linearsvc agent](https://github.com/fossology/atarashi/pull/102)
- [Feat(agent): Add okapibm25 agent](https://github.com/fossology/atarashi/pull/101)
- [Feat(package): Add model packages](https://github.com/fossology/Minerva-Dataset-Generation/pull/5)

## 👨🏻‍🏫 DELIVERABLES

|      Tasks       |                    Status                     |                                                              Links                                                               |
| :--------------: | :-------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: |
|  CycloneDX agent  |  Successfully implemented agent   | [Agent](https://github.com/fossology/fossology/tree/master/src/cyclonedx) |
| Linearsvc agent  |  Both training and testing of model is done   | [Agent](https://github.com/fossology/atarashi/pull/102), [Model](https://github.com/fossology/Minerva-Dataset-Generation/pull/5) |
| Okapi-BM25 agent |        Implementation of agent is done        |                                     [Agent](https://github.com/fossology/atarashi/pull/101)                                      |
|  Doc2vec Model   | Training of model is done and testing is left |                                   [Notebook](https://www.kaggle.com/code/sushanttkr07/doc2vec)                                   |
|    Bert Model    | Training of model is done and testing is left |                    [Notebook](https://www.kaggle.com/code/sushanttkr07/bertmodel1?scriptVersionId=105132896)                     |

## REACH OUT TO ME!

- [LinkedIn](https://www.linkedin.com/in/its-sushant/)
- [GitHub](https://github.com/its-sushant)
- [Email](sushantmishra02102002@gmail.com)

[![](https://img.shields.io/badge/Made%20With%20❤️%20By-Sushant-red)](https://github.com/its-sushant)
