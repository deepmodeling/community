# Proposal
We propose adding "Project Phases" to the community projects, which will help project leaders further clarify the project's future development goals and provide the community partners with a simple and intuitive understanding of the project. This approach can enhance the vitality of the community project's development.
## Project Phase Description
Following the project phase standards of the CNCF community, projects in the DeepModeling community will be categorized into Sandbox, Incubating, and Mature stages.
### Sandbox Phase
- Project Status:
  - Could be a proposed algorithm idea, possibly in the process of implementation.
  - The software is not yet systematically engineered and consists of a collection of simple scripts.
- Usage of Project Software:
  - Currently, there are no users; or there are users, but they are not external users. The software is used internally by oneself or within a small group familiar with the research team.
- Example:
  - JAX-FEM
### Incubating Phase
- Project Status:
  - The software is already in a preliminary usable state.
  - It has sufficient conditions to release version 1.0 to the public or already has versions 1.0 and above.
  - There are multiple developers maintaining the project.
- Usage of Project Software:
  - There are already some interested users and potential developers.
  - The number of external users is no less than 10.
- Examples:
  - ABACUS, DeepFlame, DMFF
### Mature Phase
- Project Status:
  - A software that is both stable and user-friendly.
  - The software has released at least one major version to the public.
  - Continuous addition of developers to the community, with developers from two or more different organizations.
  - It has a mature algorithm engineering process in place.
- Usage of Project Software:
  - It has a large user base, ranging from novices to experts.
  - The overall number of external users is no less than 500.
- Example:
  - DeePMD-kit
## Assessment of Project Phases
After a new project joins the community, it needs to be prioritized to determine which team it belongs to. Currently, the community projects include MD, DFT, Combustion, workflow, and FEM teams. Once it's clear which team the project belongs to, the team leader will decide which phase the project belongs to.
### New projects entering the Sandbox or Incubating Phase
If the team leader determines that the project should belong to the sandbox or incubation phase, then the project will follow the team leader's decision and enter these phases.
### New projects entering the Mature Phase
The Mature Phase is the highest project phase within the community, signifying the community's strong recognition of the project.
If a project joins the community at the mature stage, it needs to be initiated by the team leader or by someone delegated by the team leader to initiate the TOC vote. The TOC will then decide whether the project can be classified as the mature stage. The following are the criteria for determining whether it is at the mature stage. When initiating the vote, the following information should be provided to facilitate the TOC's decision-making:
- Clearly articulate the project's goals and plans, which should align with the vision of the DeepModeling community.
- Present the current engineering status of the project. Mature projects should have the following engineering processes in place:
  - Code management and version control process
  - Issue tracking and task management process
  - Code review and merge process
  - CI/CD process
  - Testing process
- Outline the composition of the current developers (developers should come from at least two or more different organizations).
- Provide an overview of the current user base (Mature projects should have 500 or more external users).
The voting rule follows the "lazy consensus" mechanism.
