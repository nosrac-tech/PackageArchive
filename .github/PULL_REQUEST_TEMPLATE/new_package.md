name: "New Package"
description: Submit a new package to the PackageArchive
labels: [new package]
body:
  - type: textarea
    id: packagedesc
    attributes:
      label: Steps to reproduce
      description: |
        Provide the following information for your package to accelerate the review process. Feel free to include any other information you would like to include.
      placeholder: |
        Name:
        Description:
        Homepage:
    validations:
      required: true
  - type: checkboxes
    id: checks
    attributes:
      label: General information
      options:
        - label: I have ensured that my package builds locally on my system and behaves as expected.
          required: true
        - label: I have filled out the requested information above to the best of my ability.
          required: true
        - label: I am the owner/author/maintainer/etc. of the package being submitted.
          required: false
  - type: markdown
    attributes:
      value: |
        Thanks for contributing a new package!
        You're making Hermetic better for everyone!
