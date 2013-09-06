# FDS Properties

As NIST stopped including properties in FDS 5, this section aims to construct a
database of properties (with references from where they were taken) for
inclusion within FDS models.

The output file is a file created in [Pyrosim](www.thunderheadeng.com/pyrosim/).
If you're a Pyrosim user, you can download the FDS file and use it as a library
file to import the materials into your own FDS files. This can be done by adding
the libary from within the materials/surface section and selecting the
downloaded FDS file.

As an FDS user, you can just copy and paste the values into your FDS file.

## Properties

### Materials

#### Concrete

Taken from Holman, J.P, 1986. Heat Transfer, Sixth. ed. McGraw-Hill.

|Property      | Value          |
|--------      |------------    |
|Specific Heat | 0.88 kJ/Kg     |
|Conductivity  | 1.37 Wm^-1 K^-1|
|Density       | 2100 Kgm^-3    |

#### Glass 

Taken from Holman, J.P, 1986. Heat Transfer, Sixth. ed. McGraw-Hill.

|Property      | Value          |
|--------      |------------    |
|Specific Heat | 0.84 kJ/Kg     |
|Conductivity  | 0.78 Wm^-1 K^-1|
|Density       | 2700 Kgm^-3    |

#### Plaster - Gypsum 

Taken from Holman, J.P, 1986. Heat Transfer, Sixth. ed. McGraw-Hill.

|Property      | Value          |
|--------      |------------    |
|Specific Heat | 0.84 kJ/Kg     |
|Conductivity  | 0.48 Wm^-1 K^-1|
|Density       | 1440 Kgm^-3    |

#### Wood (Maple/Oak)

Taken from Holman, J.P, 1986. Heat Transfer, Sixth. ed. McGraw-Hill.

|Property      | Value          |
|--------      |------------    |
|Specific Heat | 2.4 kJ/Kg      |
|Conductivity  | 0.166 Wm^-1 K^-1|
|Density       | 540 Kgm^-3    |
