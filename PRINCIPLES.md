# BDCHM Development Principles
## Sources
In this guide we draw from:
* The O3 guidelines: [Open code, open data, and open infrastructure to promote the longevity of curated scientific resources] (https://osf.io/vuzt3/)
* The [OBOOK](https://oboacademy.github.io/obook), and in particular [How to be an Open Science Engineer - maximising impact for a better world](https://oboacademy.github.io/obook/howto/open-science-engineer/)
* The TISLab collaboration guide (link TBD)
* [LinkML Collaborative Data Model Development Guide](https://linkml.io/linkml/howtos/collaborative-development.html)
* Schema.org [How We Work](https://schema.org/docs/howwework.html)
* NCATS Biomedical Data Translator Guidelines

## Version Control Your Schema
(adapted from [O3 guidelines](https://osf.io/vuzt3/))
Version control for BDCHM is managed in GitHub. Version control systems, like git, track changes in files and enable multiple users to collaborate. They are widely used for maintaining code, but can (and should) also be used to maintain and manage data, metadata, ontologies, schemas, and other semantic artifacts.
Some projects may opt to manage their data alongside the schema in the same repo. BDC manages versioning of data and the data schema separately. These guidelines are meant only for version control of the data schema, BDCHM.
BDCHM is developed incrementally and published as a numbered release. Updates included in each release are described on a releases page. The content of each release is based on public discussions on the Github site and during DMC Standards Team meetings. All changes to the project have been through unanimous agreement of the DMC Standards Team, strongly informed by the opinions, contributions, and discussions in the wider community.
BDCHM users are encouraged to use the latest release; however, previous releases of BDCHM will be available with some backward compatibility. See the “Versioning and Dependencies” section below for more details. 

## Permissively License Your Code and Data
(adapted from [O3 guidelines](https://osf.io/vuzt3/))
BDCHM has an MIT license. Using recognizable, permissive licenses encourages contribution and ensures content longevity. Non-permissive licenses or custom terms can hinder reuse and engagement. Permissive licensing doesn’t typically lead to a lack of credit for the original resource.

## Use Technical Workflows (Automation) and Social Workflows
(adapted from [O3 guidelines](https://osf.io/vuzt3/))
Automating quality control, generation of artifacts, releases, and deployment helps in maintaining and contributing to projects. This includes using continuous integration for quality checks, automating the generation of data views, and packaging data and code for easy deployment.
Implementing social workflows through tools like GitHub enhances community engagement. Transparent discussion forums, giving credit to contributors, and using issue trackers and discussion boards are crucial for maintaining a dynamic and active contributor base.
BDCHM was created using the [LinkML Cookiecutter](https://github.com/linkml/linkml-project-cookiecutter) project template that includes a number of automation features using GitHub actions. Best practices for contributing to BDCHM via GitHub can be found in the Contribution Guidelines.

## Establish Project Governance
(adapted from [O3 guidelines](https://osf.io/vuzt3/) and TISLab guide)
Clear governance defines roles, responsibilities, and behavior expectations in a project. Establishing codes of conduct, standard operating procedures, and guidelines for administration and contribution roles is vital. Governance should evolve over time to meet the project’s needs.
BDCHM governance can be found in the Code of Conduct and the Collaboration Handbook.

## Attract and Engage Contributors
Detailed contribution guidelines and offering various ways to contribute increases engagement and recruitment. Projects should be accessible and welcoming to new contributors to ensure longevity and development. Contribution guidelines for BDCHM can be found on GitHub.
