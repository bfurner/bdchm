# BioData Catalyst Harmonized Model (bdchm)

This is the harmonized data model for use in the BioData Catalyst project.

URI: https://w3id.org/nhlbidatastage/bdchm

Name: bdchm



## Classes

| Class | Description |
| --- | --- |
| [Entity](Entity.md) | Any resource that has its own identifier |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Participant](Participant.md) | A Participant is the entity of interest in a research study, typically a human being or an animal, but can also be a device, group of humans or animals, or a tissue sample. Human research subjects are usually not traceable to a particular person to protect the subject’s privacy. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Person](Person.md) | Demographics and other administrative information about an individual or animal receiving care or other health-related services. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ResearchStudy](ResearchStudy.md) | A process where a researcher or organization plans and then executes a series of steps intended to increase the field of healthcare-related knowledge. This includes studies of safety, efficacy, comparative effectiveness and other information about medications, devices, therapies and other interventional and investigative techniques. A ResearchStudy involves the gathering of information about human or animal subjects. |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[TimePoint](TimePoint.md) | A structured representation of a single point in time that allows direct/explicit declaration as a dateTime, specification in terms of offset from a defined index, or description of an event type as a proxy for the time point when it occurred. |
| [Identifier](Identifier.md) | An Identifier is associated with a unique object or entity within a given system.   |
| [ResearchStudyCollection](ResearchStudyCollection.md) | A holder for ResearchStudy objects |
| [TimePeriod](TimePeriod.md) | A period of time between a start and end time point. |



## Slots

| Slot | Description |
| --- | --- |
| [age_at_death](age_at_death.md) | The age of an individual at the time of death, expressed in days since birth |
| [age_at_enrollment](age_at_enrollment.md) | The age in days when the Participant enrolled on the ResearchStudy |
| [associated_person](associated_person.md) | A reference to the Person that is associated with this record |
| [associated_timepoints](associated_timepoints.md) | A collection of timepoint observations that are relevant to research projects... |
| [breed](breed.md) | A label given to a group of animals homogeneous in appearance and other chara... |
| [cause_of_death](cause_of_death.md) | Coded value indicating the circumstance or condition that results in the deat... |
| [date_ended](date_ended.md) | The date when the research project ended |
| [date_started](date_started.md) | The date when the research project began |
| [date_time](date_time.md) | An explicitly specified timepoint described in terms of a date and optionally... |
| [description](description.md) | A free text field to capture additional info/explanation about the research s... |
| [description_shortened](description_shortened.md) | An abbreviated description of a research program, project, or study |
| [entries](entries.md) |  |
| [ethnicity](ethnicity.md) | An individual's self-described social and cultural grouping, specifically whe... |
| [event_type](event_type.md) | An event that occurred at the point in time specified by this TimePoint |
| [id](id.md) | The 'logical' identifier of the entity within the system of record |
| [identity](identity.md) | A 'business' identifier or accession number for the entity, typically as prov... |
| [index_time_point](index_time_point.md) | Another TimePoint from which this point is offset |
| [index_timepoint](index_timepoint.md) | The text term used to describe the reference or anchor date used for date obf... |
| [member_of_research_study](member_of_research_study.md) | A reference to the Study(s) of which this Participant is a member |
| [name](name.md) | An unabridged name of a research program, project, or study |
| [name_shortened](name_shortened.md) | An abbreviated name of a research program, project, or study |
| [offset_from_index](offset_from_index.md) | A quantity of time that, together with the index date or event, can be used t... |
| [originating_site](originating_site.md) | The Organization through which a subject was enrolled on a ResearchStudy |
| [part_of](part_of.md) | A reference to a parent ResearchStudy (e |
| [period_end](period_end.md) | When a period of time ended |
| [period_start](period_start.md) | When a period of time started |
| [primary_diagnosis_condition](primary_diagnosis_condition.md) | This attribute represents the disease that qualified the subject for inclusio... |
| [primary_diagnosis_site](primary_diagnosis_site.md) | The text term used to describe the primary site of disease, as categorized by... |
| [principal_investigator](principal_investigator.md) | The investigator or investigators leading a project |
| [race](race.md) | An arbitrary classification of a taxonomic group that is a division of a spec... |
| [research_project_type](research_project_type.md) | The 'type' of ResearchStudy represented (e |
| [sex](sex.md) | The biologic character or quality that distinguishes male and female from one... |
| [species](species.md) | The scientific binomial name for the species of the Person (e |
| [sponsor](sponsor.md) | An entity that is responsible for the initiation, management, and/or financin... |
| [system](system.md) | The system or namespace that defines the identifier |
| [url](url.md) | A URL address for a resource that provides information about a research progr... |
| [value](value.md) | The value of the identifier, as defined by the system |
| [vital_status](vital_status.md) | Coded value indicating the state or condition of being living or deceased; al... |
| [year_of_birth](year_of_birth.md) | Numeric value to represent the calendar year in which an individual was born |
| [year_of_death](year_of_death.md) | Numeric value to represent the calendar year in which an individual died |


## Enumerations

| Enumeration | Description |
| --- | --- |
| [SexEnum](SexEnum.md) |  |


## Types

| Type | Description |
| --- | --- |
| [Boolean](Boolean.md) | A binary (true or false) value |
| [Curie](Curie.md) | a compact URI |
| [Date](Date.md) | a date (year, month and day) in an idealized calendar |
| [DateOrDatetime](DateOrDatetime.md) | Either a date or a datetime |
| [Datetime](Datetime.md) | The combination of a date and time |
| [Decimal](Decimal.md) | A real number with arbitrary precision that conforms to the xsd:decimal speci... |
| [Double](Double.md) | A real number that conforms to the xsd:double specification |
| [Float](Float.md) | A real number that conforms to the xsd:float specification |
| [Integer](Integer.md) | An integer |
| [Ncname](Ncname.md) | Prefix part of CURIE |
| [Nodeidentifier](Nodeidentifier.md) | A URI, CURIE or BNODE that represents a node in a model |
| [Objectidentifier](Objectidentifier.md) | A URI or CURIE that represents an object in the model |
| [String](String.md) | A character string |
| [Time](Time.md) | A time object represents a (local) time of day, independent of any particular... |
| [Uri](Uri.md) | a complete URI |
| [Uriorcurie](Uriorcurie.md) | a URI or a CURIE |


## Subsets

| Subset | Description |
| --- | --- |
