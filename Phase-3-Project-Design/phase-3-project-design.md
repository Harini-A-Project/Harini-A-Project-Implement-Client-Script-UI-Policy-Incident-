# Phase 3 – Project Design

## Project Title
Implement Client Script & UI Policy (Incident)

## 1. System Design

The project is designed to improve the Incident form in ServiceNow by using UI Policies and Client Scripts.

The solution will control Incident form fields dynamically based on user actions and conditions.

## 2. Main Components

The project consists of the following components:

- Incident Table
- UI Policy
- UI Policy Action
- onChange Client Script
- onSubmit Client Script
- onCellEdit Client Script

## 3. UI Policy Design

A UI Policy named "High Impact Control" is created on the Incident table.

The UI Policy is designed to control the behavior of fields when the specified conditions are satisfied.

## 4. UI Policy Action Design

A UI Policy Action is associated with the "High Impact Control" UI Policy.

The Urgency field is configured as mandatory when the UI Policy conditions are met.

## 5. Client Script Design

Client Scripts are planned to provide dynamic behavior on the Incident form.

The project includes:

- onChange Client Script – responds when a field value changes.
- onSubmit Client Script – validates information before submitting the form.
- onCellEdit Client Script – controls field behavior during list editing.

## 6. Expected Workflow

User opens or edits an Incident
        ↓
UI Policy checks the specified conditions
        ↓
UI Policy Action changes the field behavior
        ↓
Client Scripts respond to user actions
        ↓
Incident information is validated
        ↓
Incident is submitted/updated

## 7. Expected Outcome

The design provides a controlled and user-friendly Incident form where fields behave dynamically according to predefined conditions and validations.
