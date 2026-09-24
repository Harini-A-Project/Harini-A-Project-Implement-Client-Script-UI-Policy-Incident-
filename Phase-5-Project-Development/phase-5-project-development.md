# Phase 5 – Project Development

## Project Title

Implement Client Script & UI Policy (Incident)

## Introduction

In this phase, the planned ServiceNow features were implemented and configured on the Incident table using UI Policies, UI Policy Actions, and Client Scripts.

The development was carried out using a ServiceNow Personal Developer Instance (PDI).

## Development Environment

- Platform: ServiceNow
- Environment: Personal Developer Instance (PDI)
- Main Table: Incident [incident]

## Milestone 1 – Create UI Policy on Incident

A UI Policy named **High Impact Control** was created on the Incident table.

The policy was configured to control the behavior of Incident form fields based on the specified condition.

The UI Policy was successfully created and activated.

### Implementation

- Table: Incident [incident]
- UI Policy Name: High Impact Control
- Active: Yes
- Condition: Impact is 1 - High

### Evidence

The UI Policy configuration screenshot is included in the project repository.

---

## Milestone 2 – Create UI Policy Action – Urgency

A UI Policy Action was created under the **High Impact Control** UI Policy.

The **Urgency** field was configured according to the project requirements.

### Implementation

- UI Policy: High Impact Control
- Table: Incident [incident]
- Field: Urgency
- Mandatory: True

### Evidence

The UI Policy Action configuration screenshot is included in the project repository.

---

## Milestone 3 – Create onChange Client Script

An **onChange Client Script** was created for the Incident table.

The Client Script is designed to execute when the specified field value is changed and provide the required dynamic behavior on the Incident form.

### Implementation

- Table: Incident [incident]
- Type: onChange
- Field: Configured according to project requirements
- Client-side execution: Enabled

### Evidence

The onChange Client Script configuration screenshot is included in the project repository.

---

## Milestone 4 – Create onSubmit Client Script

An **onSubmit Client Script** was implemented on the Incident table.

The script performs the required client-side validation or action before the Incident form is submitted.

### Implementation

- Table: Incident [incident]
- Type: onSubmit
- Client-side execution: Enabled
- Validation/action: Configured according to project requirements

### Evidence

The onSubmit Client Script configuration screenshot is included in the project repository.

---

## Milestone 5 – Create onCellEdit Client Script

An **onCellEdit Client Script** was implemented for the Incident table.

The script provides the required behavior when Incident information is edited directly from a list.

### Implementation

- Table: Incident [incident]
- Type: onCellEdit
- Client-side execution: Enabled
- Required behavior: Configured according to project requirements

### Evidence

The onCellEdit Client Script configuration screenshot is included in the project repository.

---

## Milestone 6 – Final Development Activities

The remaining development activities specified in the project were completed and configured in the ServiceNow Personal Developer Instance.

All required ServiceNow configurations were implemented according to the project requirements.

### Development Outcome

The project successfully demonstrates the use of:

- UI Policies
- UI Policy Actions
- Client Scripts
- Incident form customization
- Dynamic field behavior
- Client-side validation and interaction

## Final Development Result

All development milestones were completed successfully in the ServiceNow Personal Developer Instance.

The completed implementation provides customized behavior for the Incident form and demonstrates the practical use of ServiceNow UI Policies and Client Scripts.



All development milestones were completed successfully in the ServiceNow Personal Developer Instance.

The completed implementation provides customized behavior for the Incident form and demonstrates the practical use of ServiceNow UI Policies and Client Scripts.
