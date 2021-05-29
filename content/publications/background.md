---
widget: slider
headless: true  # This file represents a page section.
weight: 10
# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 400px

design:
  background:
    gradient_start: LightBlue
    gradient_end: '#00A6D6'

item:
  - title: In the News
    content: 'Vulnerabilities in the World Airline Infrastructure'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    #overlay_color: '#00A6D6'  # An HTML color value.
    overlay_img: gulf.jpeg  # Image path relative to your `assets/media/` folder
    overlay_filter: 1.0  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: MIT Technology Review
    cta_url: 'https://www.technologyreview.com/2014/04/16/74662/hidden-vulnerability-discovered-in-the-worlds-airline-network/'
    cta_icon_pack: fas
    cta_icon: paper-plane
  - title:
    content: 'Measuring Arson through Emergency Calls Data'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    #overlay_color: '#00A6D6'  # An HTML color value.
    overlay_img: gulf.jpeg  # Image path relative to your `assets/media/` folder
    overlay_filter: 1.0  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: TPM - Research Stories
    cta_url: 'https://www.tudelft.nl/en/tpm/research/stories-of-science/analysing-firefighter-calls-on-new-years-eve-with-open-source-data'
    cta_icon_pack: fas
    cta_icon: paper-plane
---
