# Data Directory

Place the dataset file used in the analysis in this directory.

Required columns:

- `tweet`: tweet text
- `type`: target class

Original classes expected by the notebook:

- `age`
- `ethnicity`
- `gender`
- `not_cyberbullying`
- `other_cyberbullying`
- `religion`

The notebook searches this directory for a CSV file and validates that the required columns are present.
