# Cytkit
![Cytkit bee mascot](/Presentation%20materials/cytkit_logo_bee_thumb.png)

__Your open-source spectral cytometry sidekick__ 

## Introduction
This project was started by Samson Rogers to bring a low-cost open-source cytometer design to the cytometry community. Thanks also to Oliver Burton for contributing to the specification and Stuart Vant for electronics development. The inspiration came from the Open Cytometry Hardware workshop by David Novo at CYTO 2024 in Edinburgh, and also from the OpenFlexure Microscope project by Richard Bowman and others. Thanks to many friends and colleagues for friendly advice!

Aim: to build a highly accessible cytometry analyser:
- Useful for technology developers 
- Useful for laboratory hackers
- Useful for resource-limited labs
- Useful for all cell biologists

Through this project, I hope to: 
- Help build the open source cytometry community
- Release a simple design that is highly accessible for others to modify and build on
- Share knowledge for building cytometers and new cytometry technology

The design is currently labelled v0.3 and contains all mechanical parts, an optical model, and a bill of materials. Initial testing of the released system in conjunction with commercial photodetectors, external data acquisition and analysis, shows that the system is capable of resolving 8 peak rainbow beads. 

To complete the design, the following additions are planned:
- PCBs for forward scatter, side scatter and fluorescence, data acquisition and fluidics control
- embedded software for peak detection
- host PC software for data acquisition, simple analysis, control of the instrument, and export of cytometry data

The bill of materials including all current parts as well as an estimation of the planned electronics currently comes to about $3k. 

Please [get in touch with me](https://www.linkedin.com/in/salmanrogers/) if you are:
- interested in contributing
- interested in buying a kit
- interested in talking about anything else!

![Cytkit CAD render](/Presentation%20materials/cytkit%200.3%20transparent.png)

## License
This project is released under the CERN Open Hardware Licence Version 2 - Strongly Reciprocal [CERN-OHL-S](https://opensource.org/license/cern-ohl-s). 

That means you can study and modify this design, and manufacture and distribute products based on it, provided that you release all modifications under the same open source license. 

There is no warranty and all liabilities are disclaimed. Youu accept the design "as is."

## Specification
Cytkit is intended to be one's personal cytometry sidekick:
- Conventional format, but small
- Easy to adjust, align and maintain... no need for a service contract
- Separate sheath and waste bottles
- Volumetric sample pump for absolute concentration measurement of cell populations
- Conventional single sip-tube sample loader 
- User interface on PC connected by USB
- Can be powered by USB power pack
- Mechanical parts all 3D-printed

![Cytkit bench scene with scientist](/Presentation%20materials/cytkit%20on%20bench%20scene.png)

## Cytometry
The cytometry is based on a single laser plus an spectral array of solid-state detectors.

__Why?__

- Skilled cytometrists can currently measure ~10 fluorophores on a 488 nm laser alone
- Take advantage of low-cost reagents for the 488 nm laser
- Take advantage of available low-cost parts: SiPMs plus dispersion element rather than many expensive filters
- Such a design can be mechanically simple, allowing fully 3D printed mechanics, simple assembly, adjustment and alignment

![Cytkit cytometry spec](/Presentation%20materials/Burton%2010-colours%20on%20488.png)

## Source files
The full mechanical design has been built with FreeCAD and is provided in [CAD and optical model/Cytkit model 0.31 12may25.FCStd](/CAD%20and%20optical%20model/Cytkit%20model%200.31%2012may25.FCStd)

The optical model has been built in the FreeCAD Optical Design Workbench and is provided in [Cytkit model 0.31 12may25 optics only.FCStd](/CAD%20and%20optical%20model/Cytkit%20model%200.31%2012may25%20optics%20only.FCStd)

STL files for 3D printing (FDM) are provided in [STL files for printing](/STL%20files%20for%20printing).

The Bill of Materials is provides in [Cytkit Bill of Materials v0.3.ods](/Cytkit%20Bill%20of%20Materials%20v0.3.ods)

## To do
- Present the project at CYTO 2025 in Denver
- Write complete documentation for 3D printing, assembly, alignment and maintenance
- Provide electronics PCBs and connectors
- Provide software (embedded and host PC)
- Build a business to provide kits on demand and make this project rewarding for collaborators
