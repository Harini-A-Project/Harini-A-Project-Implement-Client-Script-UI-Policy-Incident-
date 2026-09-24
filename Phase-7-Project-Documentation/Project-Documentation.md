# Phase 7 – Project Documentation

## Project Title
Implement Client Script and UI Policy on Incident

## 1. Project Overview

This project demonstrates the use of ServiceNow Client Scripts and UI Policies to control and validate fields in the Incident form.

The project was developed using a ServiceNow Personal Developer Instance (PDI).

## 2. Objective

The main objective of this project is to improve Incident form management by applying UI Policies and Client Scripts.

The configuration helps control field behavior, make fields mandatory when required, and validate incident information before submission.

## 3. Technologies Used

- ServiceNow
- ServiceNow Personal Developer Instance (PDI)
- UI Policies
- UI Policy Actions
- Client Scripts
- Incident Table

## 4. Project Implementation

The project was implemented through the following milestones:

### Milestone 1 – Create UI Policy on Incident

A UI Policy named "High Impact Control" was created on the Incident table.

The policy is used to control the behavior of Incident form fields based on specified conditions.

### Milestone 2 – Create UI Policy Action – Urgency

A UI Policy Action was configured for the Urgency field.

The action controls the field behavior when the conditions of the UI Policy are satisfied.

### Milestone 3 – Create onChange Client Script

An onChange Client Script was created to perform actions when the value of a selected Incident field changes.

### Milestone 4 – Create onSubmit Client Script

An onSubmit Client Script was created to validate the Incident form before submission.

The script checks whether the Assigned To field is populated for high-impact incidents.

### Milestone 5 – Create onCellEdit Client Script

An onCellEdit Client Script was configured to control and validate changes made directly from list views.

### Milestone 6 – Testing the Configuration

All configured UI Policies, UI Policy Actions, and Client Scripts were tested to verify that they work as expected.

## 5. Key Benefits

- Improves Incident form validation.
- Helps maintain accurate Incident information.
- Reduces incorrect or incomplete submissions.
- Automates field behavior.
- Improves consistency in Incident management.

## 6. Conclusion

The project successfully demonstrates how ServiceNow UI Policies, UI Policy Actions, and Client Scripts can be used together to control and validate Incident records.

The implemented configuration improves the usability and accuracy of the Incident management process.
