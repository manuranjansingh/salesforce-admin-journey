# Validation Rules

## What is a Validation Rule?

A Validation Rule ensures data meets specific business requirements before a record can be saved.

## Why Use Validation Rules?

To prevent users from entering invalid or incomplete data.

## Example

Scenario:

Status = Active

Email = Blank

Result:

Record should not be saved.

Validation Error:

"Email is mandatory for Active customers."

## Formula Example

```text
AND(
ISPICKVAL(Status__c,"Active"),
ISBLANK(Email__c)
)
```

## Interview Question

Q: What happens when a Validation Rule is triggered?

A: Salesforce prevents the record from being saved and displays an error message.

## Key Takeaway

Validation Rules improve data quality by enforcing business rules.
