# Phase 6 – Project Testing

## Project Title
Implement Client Script & UI Policy – Incident

## Testing Overview

The completed ServiceNow project was tested to verify that the configured UI Policy, UI Policy Action, and Client Scripts work correctly on the Incident table.

## Test Cases

### Test Case 1 – UI Policy on Incident
- Opened the Incident form.
- Verified that the UI Policy is triggered based on the configured condition.
- Checked that the required field behavior works correctly.
- Result: Passed.

### Test Case 2 – UI Policy Action – Urgency
- Tested the configured UI Policy Action for the Urgency field.
- Verified that the field behavior changes according to the defined condition.
- Result: Passed.

### Test Case 3 – onChange Client Script
- Changed the specified field value on the Incident form.
- Verified that the Client Script executes when the field value changes.
- Result: Passed.

### Test Case 4 – onSubmit Client Script
- Entered the required Incident details and attempted to submit the form.
- Verified that the validation works before the record is saved.
- Result: Passed.

### Test Case 5 – onCellEdit Client Script
- Edited the Incident field directly from the list view.
- Verified that the configured Client Script behavior is triggered.
- Result: Passed.

### Test Case 6 – Overall Configuration
- Tested the complete Incident configuration after implementing all milestones.
- Verified that the UI Policy, UI Policy Action, and Client Scripts work together as expected.
- Result: Passed.

## Final Testing Result

All implemented configurations were tested successfully. The Incident form and list view behaved according to the configured requirements.

## Conclusion

The project configuration was successfully tested in the ServiceNow Personal Developer Instance. All major functionalities were verified and the expected results were obtained.
