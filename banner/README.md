# The profile banner

`banner.html` is the source of `profile/assets/banner-dark.jpg` and `banner-light.jpg`: one page
of 1280 × 400 px, with `?dark` or `?light` in its address. The robot pictures are Robot Studio's
sample robot (Hexapod H1) taken in the app — dark theme with "Shaded with edges", light theme with
"Realistic" — with the window's own controls hidden.

To make the banners again (for example when Robot Studio is released and the "Release soon" chip
changes): open `banner.html?dark` and `banner.html?light` in a Chromium-based browser at exactly
1280 × 400 and a device scale of 1.5, capture the page (1920 × 600), save it as JPEG (quality ~88)
over the two files in `profile/assets/`.
