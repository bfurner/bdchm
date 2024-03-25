# Class: ResearchStudyCollection


_A holder for ResearchStudy objects_





URI: [bdchm:ResearchStudyCollection](bdchm:ResearchStudyCollection)




```mermaid
 classDiagram
    class ResearchStudyCollection
      ResearchStudyCollection : entries
        
          ResearchStudyCollection --|> ResearchStudy : entries
        
      
```




<!-- no inheritance hierarchy -->


## Slots

| Name | Cardinality and Range | Description | Inheritance |
| ---  | --- | --- | --- |
| [entries](entries.md) | 0..* <br/> [ResearchStudy](ResearchStudy.md) |  | direct |









## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nhlbidatastage/bdchm





## Mappings

| Mapping Type | Mapped Value |
| ---  | ---  |
| self | bdchm:ResearchStudyCollection |
| native | bdchm:ResearchStudyCollection |





## LinkML Source

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: ResearchStudyCollection
description: A holder for ResearchStudy objects
from_schema: https://w3id.org/nhlbidatastage/bdchm
attributes:
  entries:
    name: entries
    from_schema: https://w3id.org/nhlbidatastage/bdchm
    rank: 1000
    multivalued: true
    range: ResearchStudy
    inlined: true
tree_root: true

```
</details>

### Induced

<details>
```yaml
name: ResearchStudyCollection
description: A holder for ResearchStudy objects
from_schema: https://w3id.org/nhlbidatastage/bdchm
attributes:
  entries:
    name: entries
    from_schema: https://w3id.org/nhlbidatastage/bdchm
    rank: 1000
    multivalued: true
    alias: entries
    owner: ResearchStudyCollection
    domain_of:
    - ResearchStudyCollection
    range: ResearchStudy
    inlined: true
tree_root: true

```
</details>