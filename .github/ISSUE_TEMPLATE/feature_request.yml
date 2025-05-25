name: "✨ Feature Request"
description: "Suggest a new feature or improvement for the modpack."
title: "[Feature] <short description>"
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        Help us improve the modpack by suggesting features!
        Please describe your idea as clearly and completely as possible. Thank you!

  - type: textarea
    id: feature-description
    attributes:
      label: "📝 Feature Description"
      description: "What would you like to see added or improved? Describe the feature clearly and concisely."
      placeholder: "Example: Add a minimap mod for easier navigation."
    validations:
      required: true

  - type: textarea
    id: feature-benefits
    attributes:
      label: "🎯 Purpose / Benefits"
      description: "Why do you think this feature is useful? How would it improve the modpack?"
      placeholder: "Example: A minimap helps players navigate and explore more efficiently."
    validations:
      required: true

  - type: textarea
    id: feature-implementation
    attributes:
      label: "🛠️ Possible Implementation (Optional)"
      description: "If you have an idea how this could be added (specific mods, config tweaks, etc.), describe it here."
      placeholder: "Example: Add Xaero's Minimap or Journeymap with waypoints enabled."

  - type: dropdown
    id: modpack-version
    attributes:
      label: "🧪 Modpack Version"
      description: "Which version of the modpack are you referring to?"
      options:
        - Latest
        - Previous
        - Not version-specific
      default: 0
    validations:
      required: true

  - type: textarea
    id: additional-context
    attributes:
      label: "🧩 Additional Context (Optional)"
      description: "Include any other information, links, or notes that might help us understand the request."
      placeholder: "Examples: mod links, related screenshots, comparisons with other modpacks, etc."
