name: Pull Request Template
description: Explain the PR
body:
  - type: textarea
    id: summary
    attributes:
      label: Briefly summarize your PR
      description: Please provide a brief summary of what your PR attempts to achive. Include a reference to the issue this PR addresses.
      placeholder: This PR fixes #<issue_number>.
    validations:
      required: true
  
  - type: textarea
    id: detailed
    attributes:
      label: Describe in depth
      description: Describe your solution in more depth. Why is this needed? How does it work? Does it solve a problem that affects multiple users or is this an edge case for your setup?
    validations:
      required: true

  - type: textarea
    id: images
    attributes:
      label: Screenshots
      description: Does your PR include any changes to the web client? Include screenshots or a video of the change and what it looked like before.