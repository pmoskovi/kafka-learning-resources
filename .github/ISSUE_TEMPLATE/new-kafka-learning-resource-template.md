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
