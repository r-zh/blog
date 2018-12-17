+++
# Hero Carousel widget.
widget = "hero_carousel"
active = true
date = 2017-10-15T00:00:00

# Order that this section will appear in.
weight = 1

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = '10000'

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "300px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Fire with Ice"
  content = "Welcome to Rui's Blog :satisfied:"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "fire_ice.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  # cta_label = "Get Academic"
  # cta_url = "https://sourcethemes.com/academic/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  title = "望天涯"
  content = "伊人不归，我便随她而去"
  align = "left"
  # Focal point (optional)

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "looking.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

[[item]]
  title = "蓦然回首"
  content = "一曲肝肠断，天涯何处觅知音"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "review.jpg"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.3  # Darken the image. Value in range 0-1.

+++
