Iris Keyboard Case
==================

**NOTE: This repository is undergoing a bit of reorganization due to the addition of Iris Rev. 3 pieces, so some of the descriptions might not be accurate. Iris R3 mid layer single pieces are only compatible with the 1.5mm plates at the moment, design for 3mm acrylic plate is in progress.**

Here's case design files for the [Iris](https://keeb.io/products/iris-keyboard-split-ergonomic-keyboard). It's a sandwich-style case with cutouts to accomodate the USB jack and the TRRS jack.

Case pieces
-----------

- Switch layer (`iris-switch-plate.ai`)
- Bottom layer (`iris-bottom-plate.ai`)
- Middle layer (`iris-middle-layer.ai`)

### Note on middle layer compatibility 
Middle layers (both regular and tented) are compatible with the top and bottom cases with external screws only.

Screws and Standoffs
--------------------
This case was designed to use M2 screws and standoffs. The holes in the middle layers are for the standoffs, while the holes in the top and bottom layers are only wide enough for the screws. M2 screws and standoffs that fit the case can be purchased at Keebio: [M2 Screws & Standoffs](https://keeb.io/products/m2-screws-and-standoffs)

Fabrication
-----------

### Sculpteo
[Sculpteo](https://www.sculpteo.com) offers laser cutting services and is relatively easy to use.

Steps:
- Upload file
- Scale the object correctly, the dimensions of the various layers are as follows:
    - Exterior screw top/bottom plates: 153.7mm x 133.9mm
    - Middle layer (non-tented) is 153.7mm x 132.5mm
    - Middle layer (tented) is 167.2mm x 132.5mm
    - Interior screw top/bottom plates: 144.45mm x 123.0mm
- Make sure all colors are set to "Cut" and not any of the engraving choices
- Select your material and order

### Ponoko
To have the case made with Ponoko, you can't take these files as is and send them off to them. First, you'll need to download the templates for P1, P2, & P3 sheets from here, depending on what vector editor you are using:

- [Inkscape templates](https://www.ponoko.com/starter-kits/inkscape)
- [Adobe Illustrator template](https://www.ponoko.com/starter-kits/adobe-illustrator)
- [Other](https://www.ponoko.com/make-and-sell/design-it-yourself)

Next, open up the template of the sheet size you want and open up the case design files as well. Then, copy the drawings in the case design files into the template. Remove any overlapping lines to reduce the cutting cost using this guide: [Avoid doubled up lines](http://support.ponoko.com/hc/en-us/articles/220289608-Avoid-doubled-up-blue-cutting-lines-in-your-designs).

### Middle Layer Thickness
If you're having the middle layers made, from the top of the switch plate to the top of the bottom plate, the minimium distance between the two required is 12mm if the plastic on the header pins is removed. The requirement is slightly more (about 13.5mm) if you leave the plastic on. Therefore, the following middle layer thickness are needed based on the thickness of the switch layer:

- 1.5mm Stainless steel switch plate: 10.5mm
    - Usually accomplished with:
        - 2x4.5mm + 1x1.5mm layers
        - or 3x3mm + 1x1.5mm layers
        - or 4x3mm layers
- 3mm acrylic switch plate: 9mm
    - Usually accomplished with:
        - 2x4.5mm layers
        - or 3x3mm layers

STL Files for 3D printing
-------------------------
A couple of STL files have also been included for the middle layers and are both single pieces.

One version allows the Ergodox EZ legs to be used with it. In addition to the legs, you'll need M3 nuts to allow the legs screws to screw into.

License
-------
These case files are released under the MIT License.
