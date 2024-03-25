# Enum: SexEnum



URI: [SexEnum](SexEnum)

## Permissible Values

| Value | Meaning | Description |
| --- | --- | --- |
| MALE | omop:8507 | A person who belongs to the sex that normally produces sperm |
| FEMALE | omop:8532 | A person who belongs to the sex that normally produces ova |
| UNKNOWN | None | Not known, observed, recorded; or reported as unknown by the data contributor |




## Slots

| Name | Description |
| ---  | --- |
| [sex](sex.md) | The biologic character or quality that distinguishes male and female from one... |






## Identifier and Mapping Information







### Schema Source


* from schema: https://w3id.org/nhlbidatastage/bdchm




## LinkML Source

<details>
```yaml
name: SexEnum
from_schema: https://w3id.org/nhlbidatastage/bdchm
rank: 1000
permissible_values:
  MALE:
    text: MALE
    description: A person who belongs to the sex that normally produces sperm.
    meaning: omop:8507
  FEMALE:
    text: FEMALE
    description: A person who belongs to the sex that normally produces ova.
    meaning: omop:8532
  UNKNOWN:
    text: UNKNOWN
    description: Not known, observed, recorded; or reported as unknown by the data
      contributor.

```
</details>
