# Slot: identity


_A 'business' identifier or accession number for the entity, typically as provided by an external system or authority, that are globally unique and persist across implementing systems. Also, since these identifiers are created outside the information system through a specific business process, the Identifier type has additional attributes to capture this additional metadata so the actual identifier values are qualified by the context that created those values. This additional context allows "identifier" instances to be transmitted as business data across systems while still being able to trace them back to the system of origin._



URI: [schema:identifier](http://schema.org/identifier)



<!-- no inheritance hierarchy -->




## Applicable Classes

| Name | Description | Modifies Slot |
| --- | --- | --- |
[Person](Person.md) | Demographics and other administrative information about an individual or anim... |  no  |
[Participant](Participant.md) | A Participant is the entity of interest in a research study, typically a huma... |  no  |
[ResearchStudy](ResearchStudy.md) | A process where a researcher or organization plans and then executes a series... |  no  |







## Properties

* Range: [Identifier](Identifier.md)





## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nhlbidatastage/bdchm




## LinkML Source

<details>
```yaml
name: identity
description: A 'business' identifier or accession number for the entity, typically
  as provided by an external system or authority, that are globally unique and persist
  across implementing systems. Also, since these identifiers are created outside the
  information system through a specific business process, the Identifier type has
  additional attributes to capture this additional metadata so the actual identifier
  values are qualified by the context that created those values. This additional context
  allows "identifier" instances to be transmitted as business data across systems
  while still being able to trace them back to the system of origin.
from_schema: https://w3id.org/nhlbidatastage/bdchm
rank: 1000
slot_uri: schema:identifier
alias: identity
domain_of:
- Person
- Participant
- ResearchStudy
range: Identifier

```
</details>