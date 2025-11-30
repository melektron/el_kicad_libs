# el_kicad_libs

ELEKTRON KiCAD Libraries: Collections of symbols, footprints and 3D-models that I have created and use.


## Structure

This repository contains multiple libraries where symbols are grouped according to their purpose/type. Each folder contains a symbol and/or footprint library (with optional 3D models), depending on which is relevant for the purpose

- ```_legacy```: This folder contains old versions of the library created with old versions of kicad. These are no longer maintained and shouldn't be used. They are purely there for the sake of preserving them. 
- ```el_general```: Collection of general symbols and footprints for various electronic components I used over the years.
- ```el_industrial```: Symbols for creating plans of industrial control systems and cabinets. These have no footprints as they are not intended to be put on PCBs. They might also often contain logical representations of connections that do not directly correlate to the actual electrical connections (e.g. an HDMI connection is represented as one pin rather than it's individual signals as those are not relevant for the assembly)


## Guidelines

Whenever possible, newly added components should follow the [KiCAD Component Library style guidelines](https://klc.kicad.org/). Older components might not comply with that however.


## Attribution and Licenses

- STM32F103C8T6 Blue Pill Board footprint and symbol are based one [l3VGV/blue-pill-kicad](https://github.com/l3VGV/blue-pill-kicad)
