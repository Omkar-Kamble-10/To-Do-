# Manual Todo List App Testing Project

## Overview

This project documents a comprehensive **manual testing process for a Todo List application** based on the tutorial "Manual Testing for Complete Beginners" on Udemy. It covers the design and execution of **test scenarios**, identification and reporting of defects using Trello templates, and best practices for manual software testing. The objective is to ensure the Todo List app meets its functional requirements, displays consistent and accessible behavior, and maintains data integrity across platforms.

## How to Use This Repository

- **Test Scenarios:** Find detailed step-by-step test scenarios to validate different functionalities and edge cases of the Todo List app.
- **Defect Reporting:** Use the provided defect report template to ensure standardized and clear bug documentation for reproducibility and developer response.
- **Summary Reports:** Guidelines to print/export summary reports from Trello for project status updates.

## Project Setup

- **Testing Board:** Trello is used for defect tracking with customizable templates for rapid and uniform defect creation.
- **Platforms Covered:** Testing was performed on web browsers (Chrome, Firefox, Edge, Safari), Android/iOS phones and tablets.

## Defect Report Template

Create a Trello card using the following structure for each defect:

| Field             | Description                                                      |
|-------------------|------------------------------------------------------------------|
| Title             | Short, descriptive summary of defect                             |
| Steps to Reproduce | Numbered steps to trigger the issue                              |
| Expected Result   | The correct, expected application behavior                       |
| Actual Result     | The observed, incorrect behavior                                 |
| Environment       | Browser/device/OS details where defect was found                 |
| Priority          | Critical / High / Medium / Low (red, green, yellow labels)       |
| Attachment        | Screenshot or relevant files highlighting the defect             |


## Test Scenarios Checklist

- Create a new task with alphanumeric text.
- Create multiple tasks with valid and special character text.
- Attempt task creation with only whitespace.
- Verify spaces in task titles are retained and visible.
- Test exceeding maximum character limit.
- Attempt empty task creation.
- Check auto-saving behavior (if applicable).
- Test duplicate task names.
- Rapid bulk task creation and deletion.
- Unicode character, emoji, non-Latin character input.
- Malicious input (e.g., SQL injection)—ensure treated as plain text.
- View filters (All, Active, Completed) and counter accuracy.
- Placeholder text validation for empty lists.
- Task persistence after page refresh.
- Accessibility (color contrast, screen reader labels).
- Edit and update task names/status, including empty and whitespace updates.
- Verify keyboard shortcuts and interactions (Enter to add).
- Confirm order of edited tasks remains consistent.
- Deletion (single/multiple/all tasks), confirmation behavior.
- Exploratory scenarios (mobile/tablet layouts, bulk actions).

## Test Coverage & Best Practices

- Ensure **100% coverage** by executing each scenario at least once.
- Use *exploratory testing* after scenario completion for additional defect discovery.
- Run tests across multiple browsers, devices, and screen sizes for cross-platform reliability.
- Utilize accessibility tools to find issues like color contrast and missing labels.
- Export defect lists and summary via Trello’s print/PDF or JSON export feature.

## Useful Links

- [Udemy Course: Manual Testing for Complete Beginners](https://www.udemy.com/course/manual-testing-for-complete-beginners/)
- [Trello](https://trello.com/)
- [Accessibility Testing Tools](https://about.udemy.com/accessibility-statement?locale=en-us)

## Author

Tarek Roshdy (LinkedIn/YouTube: @tarekroshdy-softwaretester)

## License

Open checklist and template—adapt and share as needed for educational and professional use.

## Contributing

Contributions are welcome: submit new defect formats, improved templates, or additional scenarios via pull requests.

## Disclaimer

This README and associated test artifacts are for educational reference, based on manual testing best practices and live project execution as featured in the linked Udemy course.


