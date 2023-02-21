name: Bug Report
description: Create a bug report!
labels:
  - Potential Bug
  - bug
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!

        Before continuing, please make sure there are no similar issues on [the issue tracker](https://github.com/Hyrical/HCF-API/issues). If there are, consider contributing your information there instead!
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: 'Also tell us what did you expect to happen? PLease provide some reproduction steps: What did you do to trigger this bug?'
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots
      description: If applicable, add screenshots to help explain your issue.
      placeholder: You can add images by clicking on the button in the bar that will appear one you click this textbox.
    validations:
      required: false
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: The stacktrace/error if any.
      render: bash
  - type: input
    id: version
    attributes:
      label: Version
      description: The version that you are currently using.
      placeholder: Version-1.0
    validations:
      required: false
  - type: textarea
    id: additional-context
    attributes:
      label: Additional context
      description: Add any other context about the problem here.
    validations:
      required: false