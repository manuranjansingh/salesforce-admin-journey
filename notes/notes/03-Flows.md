# Flows

## What is a Flow?

Flow is Salesforce's declarative automation tool used to automate business processes without writing code.

---

## Why Use Flows?

Flows help automate repetitive tasks such as:

- Creating records
- Updating records
- Deleting records
- Sending emails
- Assigning tasks
- Automating approvals

---

## Types of Flows

### Record-Triggered Flow

Runs automatically when a record is created, updated, or deleted.

Example:

When a Customer record is created, automatically set Status = New.

---

### Scheduled Flow

Runs at a specific date and time.

Example:

Send renewal reminders to customers every month.

---

### Screen Flow

Provides a user interface with screens and input fields.

Example:

Employee onboarding form.

---

### Autolaunched Flow

Runs in the background without user interaction.

Example:

Update related records automatically.

---

## Real-World Example

Scenario:

When a new Customer record is created:

1. Set Status = Active
2. Send Welcome Email
3. Create Follow-Up Task

All actions happen automatically through a Flow.

---

## Benefits of Flows

- No coding required
- Reduces manual effort
- Improves efficiency
- Ensures process consistency
- Supports complex automation

---

## Interview Question

### Q: Why are Flows preferred over Workflow Rules?

**Answer:**

Flows are more powerful and flexible. They can handle complex logic, multiple actions, and advanced automation scenarios, whereas Workflow Rules have limited functionality.

---

## Key Takeaway

Flow is the primary automation tool in modern Salesforce.

It allows administrators to automate business processes without writing Apex code.
