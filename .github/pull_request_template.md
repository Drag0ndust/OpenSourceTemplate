name: "Pull Request"
body:
  - type: markdown
    attributes:
      value: |
      Thank you for this pull request!
  - type: textarea
    id: pr-description
    attributes:
      label: Describe the Pull-Request
      description: What is you Pull-Request adding to the project? Also include a issue number which this PR addresses, e.g. Closes #1
      placeholder: PR Description
  - type: textarea
    id: test-description
    attributes:
      label: Testing Steps
      description: Add a list of steps to show the functionality of your feature    
      placeholder: Steps to test...
  - type: textarea
    id: note-description
    attributes:
      label: Notes
      description: Anything else that should be noted about how you implemented this feature?
  - type: textarea
    id: screenshot
    attributes:
      label: Screenshot
      description: Add a screenshot of your new feature! OR show a screen recording of it in action. (On the simulator press Cmd + R to record, and the top button at the top when done). **This video should be longer than 30 seconds.**
