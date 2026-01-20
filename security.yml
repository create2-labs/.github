name: 🔐 Security vulnerability
description: Report a security vulnerability responsibly
title: "[SECURITY] "
labels: ["security"]
assignees: []

body:
  - type: markdown
    attributes:
      value: |
        ⚠️ **Do not disclose sensitive security issues publicly.**

        If the issue is critical, please consider contacting us privately
        before opening this issue.

  - type: textarea
    attributes:
      label: Vulnerability description
      description: Describe the vulnerability and its impact
    validations:
      required: true

  - type: textarea
    attributes:
      label: Affected component
      description: Which part of the system is affected?
      placeholder: API / Wallet / TLS / PQC / Smart contract / Infra
    validations:
      required: true

  - type: textarea
    attributes:
      label: Reproduction steps / Proof of concept
      description: Provide steps or PoC if available
    validations:
      required: false

  - type: dropdown
    attributes:
      label: Severity (self-assessed)
      options:
        - Low
        - Medium
        - High
        - Critical
    validations:
      required: true

  - type: checkboxes
    attributes:
      label: Disclosure
      options:
        - label: I agree to responsible disclosure
          required: true

