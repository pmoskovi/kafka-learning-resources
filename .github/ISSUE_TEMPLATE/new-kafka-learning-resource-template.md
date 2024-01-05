---
name: New Kafka Learning Resource Template
about: Create a new Kafka learning resource
title: New Kafka Learning Resource Submission
description: New Kafka Learning Resources
labels: ''
assignees:
  - pmoskovi
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to submit a new **Kafka Learning Resource**!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can I get in touch with you if more info is needed?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: name
    attributes:
      label: Name
      description: Name of your resource
      placeholder: Resource name
      value: ""
    validations:
      required: true


---

I'm submitting a new Kafka learning resource:

- **Name** (name of your resource)*: 
- **Link** (URL that the resource is accessible at)*: 
- **Description** (brief description of the resource)*: 
- **Source** (website that should get credit for this content): 
- **Skill Level**: [Beginner, Intermediate, Advanced] (select one): 
- **Resource Type** [Video, Documentation, Guide or Tutorial, Blog Post, Book or Article, FAQ] (select one): 
- **Interactivity** [Hands-on Exercise, Quiz or Test, Community Forum] (select one): 
- **Language** [Java, Python, .NET/C#, Go, JavaScript, Other] (select one):


body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Version
      description: What version of our software are you running?
      options:
        - 1.0.2 (Default)
        - 1.0.3 (Edge)
      default: 0
    validations:
      required: true
  - type: dropdown
    id: browsers
    attributes:
      label: What browsers are you seeing the problem on?
      multiple: true
      options:
        - Firefox
        - Chrome
        - Safari
        - Microsoft Edge
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://example.com)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
