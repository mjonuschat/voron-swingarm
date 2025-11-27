
# VORON 2020 SwingArm

A hinged metal arm for 3D printers, simplifying cable management with durability and easy maintenance in mind.

Based on the open-source PRUSA SwingArm, this short, hinged metal arm guides a sleeved cable bundle (or a USB/CAN cable). The arm’s length and movement are chosen to minimize strain on the cables. Mounting or replacing the cables is a breeze – you simply remove a couple of velcro fasteners or zip ties and that’s it. It’s lightweight, space-efficient, and doesn’t cause any additional resistance. 

The changes to the Prusa design are minimal and were done to allow mounting the SwingArm to a 2020 aluminum extrusion and address manufacturing requirements from SendCutSend.

![SwingArm Motion Demo](/Images/swingarm.gif)

## BOM

### SwingArm

| Part                 | Amount | Source                                               |
| ---------------------|--------|------------------------------------------------------|
| Sheet Metal Mount    |      1 | SendCutSend                                          |
| Sheet Metal SwingArm |      1 | SendCutSend                                          |
| 3x30mm Dowel Pin     |      1 | [McMaster-Carr](https://www.mcmaster.com/91595a134/) |
| M3 Nylon Washer      |      2 | [McMaster-Carr](https://www.mcmaster.com/95610A130/) |
| Starlock Washer      |      2 | [McMaster-Carr](https://www.mcmaster.com/92133A104/) |

**SendCutSend Production Settings**

- Method: Sheet Cutting 
- Material: 5052 H3 Aluminum, 2mm thickness (0.080")
- Services: Bending (2 Bends). Ignore the "Deformed Geometry" warning on the arm.
- Finishing: Powder Coating, Matte Black

### Mounting Hardware

| Part                 | Amount | Notes                                                |
| ---------------------|--------|------------------------------------------------------|
| M3x8mm BHCS          |      2 |                                                      |
| M3 Roll-In Nut       |      2 |                                                      |
| Extrusion Protector  |      1 | Print with standard Voron settings                   |

## Assembly

Insert the washer between the metal surfaces of the arm and the mount. Install the dowel pin and lock it in place with the Starlock washers.

![Assembly Drawing](/Images/assembly.png)

## Installation

1. Insert the two roll-in T-Nuts into  the top rear horizontal extrusion
2. Use the M3x8 BHCS screws to attach the SwingArm to the extrusion using the roll-in nuts. The usage of the extrusion protector is optional but recommended.
 
## Acknowledgements

 - [Prusa SwingArm](https://www.printables.com/model/1168002-prusa-swingarm-open-source-release)

## License

[LGPL 3.0](https://choosealicense.com/licenses/lgpl-3.0/)

