name: Kafka Resource Submission
description: Submit a new Apache Kafka learning resource
title: "Resource Submission: [Resource Name]"
labels: ["submission"]
body:
  - type: input
    id: name
    attributes:
      label: Name
      description: Title of the resource.
      placeholder: 'Enter the resource name here'
    validations:
      required: true

  - type: input
    id: link
    attributes:
      label: Link
      description: URL or location of the resource.
      placeholder: 'Enter the resource link here'
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: Description
      description: A brief summary of the resource.
      placeholder: 'Enter the resource description here'
    validations:
      required: true

  - type: input
    id: source
    attributes:
      label: Source
      description: The origin or creator of the resource.
      placeholder: 'Enter the resource source here'
    validations:
      required: true

  - type: dropdown
    id: skill-level
    attributes:
      label: Skill Level
      description: Select the skill level this resource is suitable for.
      options:
        - Beginner
        - Intermediate
        - Advanced
    validations:
      required: true

  - type: checkboxes
    id: resource-type
    attributes:
      label: Resource Type
      description: Choose the type(s) of resource.
      options:
        - label: Video
        - label: Documentation
        - label: Guide or Tutorial
        - label: Blog Post
        - label: Book or Article
        - label: FAQ
    validations:
      required: true

  - type: checkboxes
    id: interactivity
    attributes:
      label: Interactivity
      description: Does this resource include any interactive content?
      options:
        - label: Hands-on Exercise
        - label: Quiz or Test
        - label: Community Forum
    validations:
      required: true

  - type: dropdown
    id: language
    attributes:
      label: Language
      description: Select the programming language this resource is associated with.
      options:
        - Java
        - Python
        - .NET/C#
        - Go
        - JavaScript
        - Other
    validations:
      required: true
