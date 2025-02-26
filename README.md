# Group_Project
Group Project for INSY - 695 Adv Topics in IS 1 ( ML in Production)
# **Data Dictionary for Austin Animal Center Outcomes Dataset**

| Column Name         | Description                                                  | API Field Name      | Data Type           |
|---------------------|--------------------------------------------------------------|---------------------|---------------------|
| **Animal ID**       | Unique identifier for each animal                            | `animal_id`         | Text                |
| **Name**            | Name of the animal (if available)                             | `name`              | Text                |
| **DateTime**        | Date and time of the outcome event                            | `datetime`          | Floating Timestamp  |
| **MonthYear**       | Month and year of the outcome event                           | `monthyear`         | Floating Timestamp  |
| **Date of Birth**   | Date of birth of the animal                                   | `date_of_birth`     | Floating Timestamp  |
| **Outcome Type**    | General category of outcome (e.g., Adoption, Transfer, Euthanasia) | `outcome_type` | Text                |
| **Outcome Subtype** | Specific subtype of outcome (e.g., Offsite, Foster)            | `outcome_subtype`   | Text                |
| **Animal Type**     | Type of animal (e.g., Dog, Cat)                               | `animal_type`       | Text                |
| **Sex upon Outcome**| Sex and reproductive status upon outcome (e.g., Neutered Male) | `sex_upon_outcome`  | Text                |
| **Age upon Outcome**| Age of the animal at the time of outcome                      | `age_upon_outcome`  | Text                |
| **Breed**           | Breed of the animal                                            | `breed`             | Text                |
| **Color**           | Color description of the animal                               | `color`             | Text                |
