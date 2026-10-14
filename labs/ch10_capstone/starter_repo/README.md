# Customer Orders ETL Starter

Small synthetic ETL repo for the Git101 capstone.

### Customer Email Validation Rule

#### Purpose

- Customer email addresses should be normalized before they are used for matching or deduplication in the ETL pipeline.

#### Validation Rules

- Trim leading and trailing whitespace from each email address.

- Convert the email address to lowercase before matching.

- Treat missing or blank email values as invalid for customer matching.

- Do not silently replace an invalid email with a fabricated value.

- Record or report invalid records according to the pipeline's error-handling rules.