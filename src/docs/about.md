# BDCHM Model Overview

This is a high-level class diagram of the core entities present in the BioData Catalyst Harmonized Model (BDCHM).

```mermaid
classDiagram
    Participant "1..*" --> "1" Person : associated_person
    ResearchStudy "1..*" <-- "1" Participant : member_of_research_study
    ResearchStudy "0..1" <-- "1" ResearchStudy : part_of
    Visit "0..*" --> "1" Participant : related_participant
    QuestionnaireResponse "0..*" --> "1" Visit : has_visit
    QuestionnaireResponseItem "1..*" <-- "1" QuestionnaireResponse : items
    QuestionnaireResponseValue "1" <-- "1" QuestionnaireResponseItem : response_value
    QuestionnaireResponseValue <|-- QuestionnaireResponseValueDecimal
    QuestionnaireResponseValue <|-- QuestionnaireResponseValueBoolean
    QuestionnaireResponseValue <|-- QuestionnaireResponseValueString
    QuestionnaireItem "0..1" <-- "1" QuestionnaireResponseItem : has_questionnaire_item
    Questionnaire "1" --> "1..*" QuestionnaireItem : items
    QuestionnaireItem "1" --> "0..1" QuestionnaireItem : part_of
    Person : id
    Person : identity
    Person : species
    Person : breed
    Person : sex
    Person : race
    Person : ethnicity
    Person : year_of_birth
    Person : vital_status
    Person : age_at_death
    Person : cause_of_death
    Participant : id
    Participant : identity
    Participant : description
    Participant : age_at_enrollment
    Participant : index_timepoint
    Participant : originating_site
    Participant : study_arm
    ResearchStudy : id
    ResearchStudy : identity
    ResearchStudy : name
    ResearchStudy : name_shortened
    ResearchStudy : description
    ResearchStudy : description_shortened
    ResearchStudy : sponsor
    ResearchStudy : date_started
    ResearchStudy : date_ended
    ResearchStudy : url
    ResearchStudy : research_project_type
    ResearchStudy : associated_timepoint
    ResearchStudy : principal_investigator
    ResearchStudy : principal_investigator
    Visit : id
    Visit : age_at_visit_start
    Visit : age_at_visit_end
    Visit : visit_category
    Visit : visit_provenance
    Questionnaire : id
    Questionnaire : identity  
    Questionnaire : name
    Questionnaire : title
    Questionnaire : description
    Questionnaire : url
    QuestionnaireItem : id
    QuestionnaireItem : identity
    QuestionnaireItem : text
    QuestionnaireItem : code
    QuestionnaireResponse : id
    QuestionnaireResponse : age_at_response
    QuestionnaireResponseItem : id
    QuestionnaireResponseItem : text
    QuestionnaireResponseValue : type
    QuestionnaireResponseValue : name
    QuestionnaireResponseValueDecimal : value
    QuestionnaireResponseValueBoolean : value
    QuestionnaireResponseValueString : value
        
      
```
