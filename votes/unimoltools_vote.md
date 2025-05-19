# A Vote for New Project: unimol_tools

## Proposal

We propose to separate the [unimol_tools package](https://github.com/deepmodeling/Uni-Mol/tree/main/unimol_tools) from the current [Uni-Mol repository](https://github.com/deepmodeling/Uni-Mol) and establish it as an independent project under the DeepModeling organization.

### Motivation for Separation:

* **Functional Independence**:

  `unimol_tools` includes utility functions and tools that are not tightly coupled with the core Uni-Mol framework and can be reused in other contexts.

* **Maintainability**:

  Maintaining `unimol_tools` separately will allow for more focused development, streamlined issue tracking, and better modular design.

* **Dependency Management**:

  Separate versioning and dependency handling will provide greater flexibility for Uni-Mol and downstream projects that rely on `unimol_tools`.

* **Community Growth**:

  Hosting `unimol_tools` as an independent repository may attract new contributors and users who are specifically interested in molecular tools and utilities.

### Transition Plan:

* Create a new repository: `deepmodeling/unimol_tools`
* Migrate the existing code along with its complete Git history
* Set up CI/CD pipelines for testing and packaging
* Update documentation and dependency references
* Ensure alignment with DeepModeling governance policies and maintain close collaboration with the Uni-Mol core development team

## Deadline

The vote will be open for at least 6 days unless there is an objection.

## Scope

TOC MEMBERS

## Result

Approved by:
wanghan-iapcm
