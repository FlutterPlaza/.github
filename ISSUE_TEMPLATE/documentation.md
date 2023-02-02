name: Docs Bug 🐞 report
description: Report mistakes and/or bugs in FlutterPlaza Docs.
title: "[Docs Bug 🐞 report]: "
labels: "🐞 docs bug"

  - 
body:
  - type: markdown
    attributes:
      value: |
        Thank you for reporting mistakes and/or bugs 🐞 in FlutterPlaza Docs 📑. We appreciate your contribution! 🙂
        
        Before filing this `Docs Bug` report, please make sure to check if someone already filed this bug report under open issues [Open Issues](https://github.com/FlutterPlaza/.github/issues).
  - type: textarea
    id: describe-bug
    attributes:
      label: Describe the bug you found in FlutterPlaza Docs.
      description: Is there a bug in one of our code snippets? Did we explain a concept incorrectly? Please share a clear and concise description of what the bug or mistake is.
      placeholder: "I would like to file an FlutterPlaza Docs Bug 🐞 report about..."
    validations:
      required: true
  - type: textarea
    id: reproduce-bug
    attributes:
      label: Attach any resources that can help us understand the issue.
      description: Send us screenshots, direct quotes of the text that has issues, a link to the GitHub repository with project that has issues, etc. Help us reproduce this Docs issue.
      placeholder: "Please find attached a screenshot of the text with issues..."
    validations:
      required: true
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://github.com/FlutterPlaza/.github/blob/main/CODE_OF_CONDUCT.md)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
