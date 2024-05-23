---

title: My page
type: landing

sections:
  - block: collection
    id: project
    content:
      title: Projects
      subtitle: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - project
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: showcase
      # Choose single or dual column layout
      columns: '1'
      # spacing:
      #   padding: [0, 10000, 1000, 10000]
---
<!-- # An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 65

title: Project
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
  - name: All
    tag: "*"
  - name: Spatial Social Networks
    tag: Spatial Social Networks
  - name: Urban Analytics
    tag: Urban Analytics
  - name: Digital Civics and Critical Data
    tag: Digital Civics and Critical Data

design:
  # Choose how many columns the section has. Valid values: '1' or '2'.
  columns: '1'

  # For Showcase view, flip alternate rows?
  flip_alt_rows: false

# Toggle between the various page layout types.
#   1 = List
#   2 = Compact
#   3 = Card
#   5 = Showcase
view: 5
--- -->
