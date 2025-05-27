# Standard Contributor Recognition Template
# Program Version: v2025.05-governance-hardened
# Required for all onboarding participants

name: Contributor Recognition Signal
description: Submit a form-based opt-in for public credit or badge nomination
title: "[Recognition] Contributor Signal – <your GitHub handle>"
labels: [recognition-missing, opt-in]
body:
  - type: input
    id: github-handle
    attributes:
      label: GitHub Username
      description: Your GitHub handle (e.g. @yourusername)
      placeholder: "@yourusername"
    validations:
      required: true
  - type: textarea
    id: signal-description
    attributes:
      label: What did you contribute or where should we look?
      description: Provide links to PRs, issues, test results, or other GitHub metadata
    validations:
      required: true
  - type: checkboxes
    id: opt-in
    attributes:
      label: Consent
      options:
        - label: I consent to being listed in dashboards or metadata exports (opt-in)
          required: true
