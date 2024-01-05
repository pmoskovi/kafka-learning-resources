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
