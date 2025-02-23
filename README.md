# Fablab U Chile Face Shield
Spanish version [here](/LEEME.md) | Versión en español [acá](/LEEME.md)

## Table of contents

- [Resume](#resume)
  * [Security and effectiveness validation](#security-and-effectiveness-validation)
- [Versions](#versions)
    + [LAST VERSION -> v6](#last-version----v6)
    + [v5 (can be stacked)](#v5--can-be-stacked-)
    + [v4](#v4)
    + [v3](#v3)
    + [v2](#v2)
    + [v1](#v1)
- [Parts](#parts)
  * [3D Printed Headband](#3d-printed-headband)
    + [Printer Settings](#printer-settings)
  * [Commercial Parts](#commercial-parts)
    + [Clear plastic sheet](#clear-plastic-sheet)
    + [Rubber band](#rubber-band)
- [Assembly](#assembly)
- [Sterilization and safety recommendations](#sterilization-and-safety-recommendations)
- [Join the community](#join-the-community)
- [License](#license)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


## Resume

Based on the [Prusa Face Shield](https://www.prusaprinters.org/prints/25857-protective-face-shield-rc3) initiative, we design our own face shield in order to eliminate any further work on the comercial parts, and to match with the local availability of them,  decreasing the chance of contamination during the fabrication stage and for direct assembly. The face shield is meant to be used complementary with a N95 mask or similiar.

**Warning**: only V6.0 is a certificate medical device.

### Security and effectiveness validation

Recently, we subjected the V6.0 of the FaceShield to laboratory tests ([LICTEX USACH](https://www.linkedin.com/company/lictex-udesantiago/?originalSubdomain=cl)) to validate the performance of the Facial Shield (*)(**). The tests carried out were:
 1. Protection of standard point protected areas
 2. Protection against drops and liquid splashes
 3. Evaluation of lateral protection
 4. Evaluation of the Visual Field.

 (*) These tests are verified by the Chilean Institute of Public Health ([ISP](http://www.ispch.cl/)).
The Face Shield successfully passed all tests.

  (**) According to the standard of Facial Shields market in Chile, a fifth test is required, that of fogging. As we know, in Chile there are no laboratories that can carry out this test.

## Versions

#### LAST VERSION -> v6

The new version has several modifications in order to ensure protection over other factors:
* We increased the distances between the side flaps to use a legal size (~330 mm) translucent sheet. This modification gives more protection to the sides of the face.
* We added a cover in top of the shield to protect the face from particles that may attack from above.
* The cover increase the stiffness of the faceshield so we give more comfort by separating the side bars from the front part, also making it compliant for different head's sizes.


![imagen](images/v6_1.png)
![imagen](images/v6_2.png)
![imagen](images/v6_3.png)
![imagen](images/v6_4.png)

#### v5 (can be stacked)

The new version improves the comfortability in the usage, with wide open, almost paralel side bands, with a stronger structure to prevent breaking under strong undesirable forces. We also aded some minor improvements for stack printing.

  <img src="/images/v5.jpg" alt="v5"
	title="v5" width="600" />

  <img src="/images/v5_stack.jpg" alt="v5_stack"
	title="v5_stack" width="600" />

#### v4

<img src="/images/v4.jpg" alt="v4"
	title="v4" width="600" />

#### v3

<img src="/images/v3.jpg" alt="v3"
	title="v3" width="600" />

#### v2

<img src="/images/v2.JPG" alt="v2"
	title="v2" width="600" />

#### v1

<img src="/images/v1.png" alt="v1"
	title="v1" width="600" />

## Parts

The device consists of three components:
* 3D printed headband
* Clear plastic sheet (*)
* Rubber band

```
* letter size (215.9 x 279mm) v1 to v5, portrait oriented, or
  legal size (215.9 x 330.2mm) v6, landscape oriented for side protection
```

### 3D Printed Headband

**YOU CAN GET THE FILES** at [PrusaPrinters](https://www.prusaprinters.org/prints/30347-fablab-u-de-chile-faceshield), [Thingiverse](https://www.thingiverse.com/thing:4250678)(STL) or [Grabcad](https://grabcad.com/library/covid-face-shield-2) (STL, STEP and F3D). Please check the version list, remember *this is a work in progress*.

Version | File Name                     | Release date
------- | ---------------------------   | ------------
V6.0    | face_shield_fabuchile_v6.stl	| 27-07
V5.0    | face_shield_fabuchile_v5.stl  | 22-04
V4.0    | faceshield_fablab_uch_v4.stl  | 06-04
V3.0	  | faceshield_fablab_uch_v3.stl	| 02-04
V2.0    | faceshield_fablab_uch_v2.stl  | 31-03
V1.0    | FaceShield_FabLab_UCH.stl     | 30-03

We recommend to print the headband in PLA, as is easier to print, no hot bed needed, compostable, has a low carbon footprint and it is tough enough. You can use a stronger filament if you want, like ABS or PETG, as long it is compatible with the sanitation measures that will be used on it.

The headband consist in two strips joint togheter in the ends. The inner strip goes around the head and the outer strip holds the clear sheet with some slip fits, far from the face to allow some room for glasses or goggles, also to avoid some fogging in the sheet due to breathing. The ends of the headband have a hook and holes to mount the rubber band, or another subjection device.

#### Printer Settings

V5 deployment on Cura, be sure the frontal slip fit and the rear hooks are upwards.
<img src="/images/v5_cura.png" alt="v5"
	title="v5" width="800" />

We used some Ender 3 and Ender 5 3D printers to make the prototype and Cura as slicer, using the following parameters:

- Material: PLA
- Extruder Temp: 200°C
- Bed Temp: 60°C
- Layer Height: 0.3 mm
- Number of Shells: 3
- Infill density: 0% - 10% (many walls so this can be 0%)
- Speed: 60 mm/s infill, 30 mm/s walls.

You can also print two or more headbands stacked up, depending on the reliability of your printer. We have tested the stacked printings with 0.2mm separation in Z between each headband.

<img src="/images/v5_4stacked_cura.png" alt="v5stacked"
	title="v5stacked" width="800" />

The only problem you may have with the printed part are the slip fits for supporting the clear sheet. It's optimized for 0.4 mm nozzle.
<img src="/images/cura2.png" alt="difficult part"
	title="step 1" width="500" />

### Commercial parts
the commercial parts needed for the full assembly of the face shield are
* a transparent plastic or mica sheet
* an elastic band

#### Transparent plastic sheet

The sheet is a cellulose acetate clear sheet, letter size (216X279 mm) or legal size (216x330 mm) vertical oriented for version 1 to 5) or legal size (216x330mm) horizontal oriented for v6, 0.2 mm thick. You can get some in almost any library or school supply store. It is possible to use a clear sheet of other material if it is available in the same size and if it is compatible with the available sanitation methods. You can also use the plastic of a 2-L bottle, if there is no other material available.

#### Elastic band

You can use any rubber band as long you feel comfortable with it, we used the most popular around here, [the money rubber band](https://www.aliexpress.com/i/32900926065.html).+

<img src="/images/rubberbands.jpg" alt="rubber band"
	title="step 1" width="500" />

## Assembly

After printing and sanitation of the parts, introduce the sheet in the fits of the headband in the outer strip as the picture below shows. Then, hook the rubber band in the headband ends. Ensure that the sheet is firm by pulling it gently. This is fundamental as otherwhise the user will be in danger of infection.

1. Put one corner of the sheet into one lateral fit

<img src="/images/1.JPG" alt="step 1"
	title="step 1" width="400" />

2. Put the middle of the sheet in the frontal fit

<img src="/images/2.JPG" alt="step 2"
	title="step 2" width="400" />

3. Put the other corner of the sheet into the other lateral fit

<img src="/images/3.JPG" alt="step 3"
	title="step 3" width="400" />

4. Hook the ruber band in the headband ends

<img src="/images/4.JPG" alt="step 4"
	title="step 4" width="400" />

<img src="/images/5.JPG" alt="step 5"
	title="step 5" width="400" />

## Sterilization and safety recommendations

During all the proccess, the components must be handled as if you were infected with Covid-19 virus, in a clean environment using clean gloves and mask to avoid cross contamination, and quickly stored in a plastic bag as soon it cools down after printing. [Recent studies](https://www.nejm.org/doi/full/10.1056/NEJMc2004973?query=featured_home) had revealed that the virus can last until 90 hours in plastic surfaces, so the headbands must be stored **three or four days** before delivery, unless the proper hygiene and sanitation protocols are being taken.

You can get updated information about sanitization of 3D printed faceshields in [this](https://help.prusa3d.com/en/article/prusa-face-shield-disinfection_125457#_ga=2.252887433.1803747422.1587586218-241505996.1587586218) article.

<!-- For sterilization at home, the [recommendations](https://www.minsal.cl/wp-content/uploads/2020/03/PROTOCOLO-DE-LIMPIEZA-Y-DESINFECCIÓN-DE-AMBIENTES-COVID-19.pdf) of ECDC are cleaning with 0,1% sodium hypoclorite (dilution 1:50 if household bleach at an initial concentration of 5% is used, 20mL in a 1L of water). *This is currently being verified by professionals*. -->

You can find more information about this proyect in [this brochure](/docs/LaminaFaceShield.pdf) or in the [AFES website](https://afeschile.cl).

<!-- You can take a look on [this list](https://www.epa.gov/pesticide-registration/list-n-disinfectants-use-against-sars-cov-2) for products that meet EPA’s criteria for use against SARS-CoV-2. -->

## Join the community

We encourage you to get involved and to make your part in this Covic-19 crisis. You can print the model, get the commercial parts, assemble the mask and share with those most in need.

If you think you can make an improvement of our face shield you can find the Fusion 360 cad, or STEP files [here][last-version]. Please **be serious** and test the functionality of your printed parts before you start producing and sharing them.

You can contact us in [facebook](https://www.facebook.com/fablabudechile/), [instagram](www.instagram.com/fablabudechile) or check our [webpage](www.fablab.uchile.cl).

[last-version]: https://github.com/FabLabUChile/fabuchile-face-shield/tree/master/cad/v6

## License

[![CC BY SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by-sa].

[![CC BY SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: https://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY%20SA%204.0-lightgrey.svg
