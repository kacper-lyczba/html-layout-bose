# Bose Landing Page
This landing page was created purely using HTML and SCSS with the BEM methodology.
No JavaScript other than 'use strict' was used in order to achieve the final result.
It is a landing page of Bose, a business that sells speakers and headphones.

# Documentation
1. `index.html` contains the HTML markup for the website.
1. The `images` folder contains all of the imagery and icons used on the website.
1. The `scripts` folder contains any to-be JavaScript scripts; in this case, just a 'use strict'.
1. The `styles` folder contains SCSS elements.
  - `_fonts` loads the desired font, Inter, with sans-serif as a fallback.
  - `_utils` loads utilities from the `utils` folder.
  - `header` contains styling for the page header, where the main title is located.
  - `menu` contains styling for the sliding menu openable with a button at the right top corner of the page, where navigation links can be found.
  - `main` contains styling for the main body of the page, being catalogs, imagery, and the contact form.
  - `footer` contains styling for the footer of the page, the image at the bottom.
  - The `utils` folder contains utilities, such as
    - `_mixins`, which contains the `backgroundSetter` mixin, carrying default background image settings.
    - `_vars`, which contains variables for the rest of the styling blocks.

# [Page Demo](https://kacper-lyczba.github.io/html-layout-bose)
