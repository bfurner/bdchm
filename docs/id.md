# Slot: id


_The 'logical' identifier of the entity within the system of record.  The simple value of this attribute stands for an identifier of this data object within the system, it can be used as a reference from other objects within the same system (i.e. primary and foreign keys), and it should be unique per type of object. The same data object copied to a different system will likely have a different "id" in the new system since "id" values are system specific and do not represent persistent business identifiers. Business identifiers are assigned outside the information system and are captured in the "identifier" field. The "id" field is more likely to be a serially or randomly generated value that is assigned to the data object as it is created in a system._



URI: [schema:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[Entity](Entity.md) | Any resource that has its own identifier |  no  |
[Person](Person.md) | Demographics and other administrative information about an individual or anim... |  no  |
[Participant](Participant.md) | A Participant is the entity of interest in a research study, typically a huma... |  no  |
[ResearchStudy](ResearchStudy.md) | A process where a researcher or organization plans and then executes a series... |  no  |
[TimePoint](TimePoint.md) | A structured representation of a single point in time that allows direct/expl... |  no  |







## Properties

* Range: [Uriorcurie](Uriorcurie.md)

* Required: True





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nhlbidatastage/bdchm




## LinkML Source

<details>
```yaml
name: id
description: The 'logical' identifier of the entity within the system of record.  The
  simple value of this attribute stands for an identifier of this data object within
  the system, it can be used as a reference from other objects within the same system
  (i.e. primary and foreign keys), and it should be unique per type of object. The
  same data object copied to a different system will likely have a different "id"
  in the new system since "id" values are system specific and do not represent persistent
  business identifiers. Business identifiers are assigned outside the information
  system and are captured in the "identifier" field. The "id" field is more likely
  to be a serially or randomly generated value that is assigned to the data object
  as it is created in a system.
from_schema: https://w3id.org/nhlbidatastage/bdchm
rank: 1000
slot_uri: schema:identifier
identifier: true
alias: id
domain_of:
- Entity
range: uriorcurie
required: true

```
</details>