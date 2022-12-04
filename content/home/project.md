---
widget: portfolio
headless: true
title: Research
content:
  title: Research
  filters:
    folders:
      - project
  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  default_button_index: 0
  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Data Stories
      tag: AC
    - name: Student Debt
      tag: SD
    - name: Social Safety Net
      tag: SSN
    - name: Data Visualization
      tag: DV
    - name: Working Papers
      tag: WP
    - name: Reports
      tag: REP
    - name: Peer Reviewed
      tag: PR
design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '2'
  view: masonry
  # For Showcase view, flip alternate rows?
  flip_alt_rows: false
---
