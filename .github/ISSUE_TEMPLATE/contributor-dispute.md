name: Contributor Metadata Dispute
description: Request a correction or removal of your public contributor metadata
title: "[Dispute] Contributor Metadata – @yourhandle"
labels: [dispute-request]
body:
  - type: input
    id: github-handle
    attributes:
      label: GitHub Handle
      placeholder: "@yourhandle"
    validations:
      required: true
  - type: textarea
    id: correction-request
    attributes:
      label: What should be corrected or removed?
      description: Explain which metadata or file is inaccurate and why
    validations:
      required: true
  - type: checkboxes
    id: consent
    attributes:
      label: Confirm
      options:
        - label: I understand this request may be manually reviewed and milestone-logged.
          required: true
