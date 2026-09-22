# Phase 2 – Requirement Analysis

## Project Title

Implement Client Script and UI Policy (Incident)

## Introduction

The requirement analysis phase identifies the functional and technical requirements needed to implement Client Scripts and UI Policies on the Incident table in ServiceNow.

The main purpose is to improve the Incident form by dynamically controlling field behavior and ensuring accurate and consistent data entry.

## Functional Requirements

The project should satisfy the following functional requirements:

1. The system should allow the creation of UI Policies on the Incident table.
2. The system should dynamically control Incident form fields based on predefined conditions.
3. The system should make selected fields mandatory when specific conditions are satisfied.
4. The system should reverse the field behavior when the specified condition is no longer satisfied.
5. The system should allow Client Scripts to execute actions on the Incident form based on user interactions.
6. The implemented functionality should work correctly when creating or updating Incident records.
7. The implemented features should be tested to verify that they produce the expected results.

## UI Policy Requirements

The UI Policy should:

- Be created on the Incident table.
- Apply to the required Incident form condition.
- Dynamically control the required field.
- Make the Assignment Group field mandatory when the Impact is set to 1 - High.
- Use the Reverse if false option so that the mandatory behavior is removed when the condition is false.

### UI Policy Configuration

| Requirement | Value |
|---|---|
| Table | Incident [incident] |
| UI Policy Name | High Impact Control |
| Condition | Impact is 1 - High |
| Field | Assignment group |
| Mandatory | Yes |
| Reverse if false | Yes |

## Client Script Requirements

The project should include a Client Script to demonstrate client-side customization of the Incident form.

The Client Script should:

- Execute on the Incident form.
- Respond to the appropriate user action or form event.
- Perform the required client-side behavior.
- Improve the usability and accuracy of the Incident form.
- Be tested under the required conditions.

## Non-Functional Requirements

The project should meet the following non-functional requirements:

- The configuration should be simple and easy to maintain.
- The implemented functionality should respond correctly to user actions.
- The solution should improve data consistency.
- The solution should not negatively affect normal Incident form operations.
- The implementation should be tested before final submission.

## Technical Requirements

The project requires:

- ServiceNow Personal Developer Instance (PDI)
- Incident table
- ServiceNow UI Policies
- ServiceNow Client Scripts
- Internet browser
- ServiceNow Developer account

## Expected Result

The completed implementation should provide a customized Incident form where fields behave dynamically according to predefined conditions.

The UI Policy should successfully make the Assignment Group field mandatory when Impact is set to 1 - High, while the Client Script should provide the required client-side behavior.

## Testing Requirement

Each implemented feature should be tested using appropriate Incident records to confirm that the expected behavior occurs under both valid and invalid conditions.

## Conclusion

The requirements identified in this phase provide the foundation for designing, developing, and testing the Client Script and UI Policy functionality on the ServiceNow Incident table.
