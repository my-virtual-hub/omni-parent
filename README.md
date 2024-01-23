# Omni Parent Project

The Omni Parent project is a Maven project that forms the core layout for all Maven projects part of Omni project. Its main role is to provide a central location for dependency and plugin version settings, among other default configurations.
In complex projects composed of multiple modules, there might be lots of dependencies repeated across several projects. This can lead to version conflicts and inconsistencies. The Omni Parent project acts as a parent 'pom' to all other project 'poms', standardizing the versions of all the shared libraries.
This enhances efficiency and eases maintenance as any version changes can be managed from a single location. Moreover, 'pom' inheritance allows each module to inherit the needed dependencies, reducing duplication and keeping consistency across modules.
In simpler terms, the Omni Parent project brings order and harmony to the development environment, allowing developers to focus on individual module development without worrying about dependency conflicts.

## Installation

1. Clone the repository
2. Execute the following command in the root directory of the project:

    ```bash
    mvn clean install
    ```

## Independent Project

This project operates independently and its progression depends on availability and community input. Contributions in the form of code, bug reports, suggestions, or even project usage are greatly appreciated and contribute significantly to the project’s development.

## Using SonarCloud and Qodana for Code Quality

[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-white.svg)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent)
[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=my-virtual-hub_omni-parent)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent)  [![Qodana](https://github.com/my-virtual-hub/omni-comm-ports-outbound/actions/workflows/qodana.yml/badge.svg?branch=main)](https://github.com/my-virtual-hub/omni-comm-ports-outbound/actions/workflows/qodana.yml)

| Quality Metrics | Code Metrics | Security Metrics |
|---|---|---|
| [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) | [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) | [![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) |
| [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=coverage)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) | [![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) | [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=bugs)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) |
| [![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) | [![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) | [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) |
| | [![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) | |
| | [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=my-virtual-hub_omni-parent&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=my-virtual-hub_omni-parent) | |

## License

Omni Communicator is Open Source software released under the [Apache 2.0 license](https://www.apache.org/licenses/LICENSE-2.0.html).

## Contact

![Marco Quicula](images/marco.png)

- Email: [marco.quicula@myirtualhub.com.br](mailto:marco.quicula@myvirtualhub.com.br)
- Website: [www.myvirtualhub.com.br](http://www.myvirtualhub.com.br)
- LinkedIn: [https://www.linkedin.com/in/marco-quicula/](https://www.linkedin.com/in/marco-quicula/)
