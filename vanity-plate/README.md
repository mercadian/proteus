# Proteus Vanity Plate

The vanity plate for the Proteus is an aluminum plate that can be laser etched with any image you like.

The plate itself is an 80mm x 30mm x 0.8mm flat sheet of aluminum, anodized black on both sides.
Supported images must be at most 76mm x 26mm because the engraver needs a 2mm margin per edge to etch safely. 


## Image Specifications

To create an image for the vanity plate, use the following rules.

- The image must be one of the following formats:
  - SVG, which must fit 76x26mm at 25px/mm
  - BMP, size 1900x650

- The colors must be **binary** (completely black or completely white only). The laser cannot etch grayscale colors; it's either on or off.
  - Grayscale pixels will be converted to black or white based on which color is closer, so please ensure the image you provide only uses black and white so you know what it will look like when it comes out.

- Use **black** for **unetched** background pixels, which will remain black on the actual plate. Use **white** for **foreground** pixels that will be etched; they will be a silvery-gold color on the actual plate.
