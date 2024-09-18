---
name: Add New Resources
about: Use this template to submit a new resource for first-generation students.
title: ''
labels: ''
assignees: ''

---

name: Add New Resource
description: Use this template to submit a new resource for first-generation students
title: "[NEW RESOURCE] "
labels: ["new resource"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to submit a new resource! Please fill out the information below.
  - type: input
    id: resource-name
    attributes:
      label: Resource Name
      description: What is the name of the resource?
      placeholder: e.g., FirstGen Scholarship Program
    validations:
      required: true
  - type: input
    id: resource-type
    attributes:
      label: Resource Type
      description: What type of resource is this? (e.g., Scholarship, Mentorship, Academic Support)
      placeholder: e.g., Scholarship
    validations:
      required: true
  - type: input
    id: location
    attributes:
      label: Location
      description: Where is this resource available? (e.g., Nationwide, Online, Specific University)
      placeholder: e.g., Nationwide
    validations:
      required: true
  - type: input
    id: link
    attributes:
      label: Resource Link
      description: Provide the URL for more information about this resource
      placeholder: https://example.com/resource
    validations:
      required: true
  - type: textarea
    id: additional-info
    attributes:
      label: Additional Information
      description: Provide any additional details about this resource
      placeholder: This resource offers...
    validations:
      required: false
