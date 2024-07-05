# bdchm

This is the LinkML model repository for the BioData Catalyst Harmonized Model (bdchm).

Please read the [Collaboration Guide](CONTRIBUTING.md) before contributing.

## Repository Structure

* [examples/](examples/) - example data
* [project/](project/) - project files (do not edit these)
* [src/](src/) - source files (edit these)
  * [bdchm](src/bdchm)
    * [schema](src/bdchm/schema) -- LinkML schema
      (edit this)
    * [datamodel](src/bdchm/datamodel) -- generated
      Python datamodel
* [tests/](tests/) - Python tests

## Developer Documentation

<details>

To setup a local development environment:

* clone the repository
* change directories to the model repository using `cd bdchm`
* install all of the dependencies using `poetry install`
* enter the poetry environment using `poetry shell`
* use the `make` command to generate project artefacts:
  * `make gendoc`: generates documentation
  * `make serve`: starts a local webserver to allow for browsing of documentation

</details>

## Credits

This project was made with
[linkml-project-cookiecutter](https://github.com/linkml/linkml-project-cookiecutter).
