# magneticmatrix
A hall-effect / LED matrix that illustrates the nearby magnetic fields, in the hopes of using this as an illustrative tool during EE lectures.

# Notes to self 
linear hall effect sensor (analog out)
TOSHIBA TCS40DLR magnetic sensor --> not sensitive enough (aiming for < mT sensitivities)

analog interfacing circuitry?
MLX sensors have good sensitivity but need a proprietary (expensive) programmer to boost sensitivity
TI DRV5055 (were present in KiCAD) also have analog out and ~20 mT sensitivity--> good fit?

## Remaing questions
- Op amp way seems to have smallest BOM
  - But it does have hard on/off led's
  - opamp package needs to be smaller to decrease pixel spacing
- footprints need to be validated
- stuff needs to be breadboarded, checklist
  - led approach:

