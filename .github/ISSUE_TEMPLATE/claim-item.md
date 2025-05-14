---
name: Claim item
about: Laat anderen weten dat jij dit al haalt.
title: ''
labels: wishlist
assignees: ''

---

- type: markdown
    attributes:
      value: "Tell us which item you've bought!"
  - type: input
    id: item
    attributes:
      label: "Item Name"
    validations:
      required: true
  - type: input
    id: name
    attributes:
      label: "Your Name"
    validations:
      required: true
