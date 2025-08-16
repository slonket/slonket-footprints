# slonket-footprints

An assortment of KiCAD footprints used in Slonket's projects. All footprints have simplified landing pads and silkscreen designators removed for high-density placement - using the Interactive HTML Bom plugin within KiCAD is recommended for documenting complex designs.

This library of footprints is not intended to be comprehensive. The footprints within this library are created as needed to support other projects.

## JLCPCB Compatibility

These footprints are made with fabrication and assembly using JLCPCB in mind. Most footprints have their origin and orientation aligned with common parts in the JLCPCB assembly library. Unfortunately, different components with shared packages are not always aligned within JLCPCB's library (most commonly IC packages), so you may need to manually correct placement within your project.

## 3D Models

Most common footprints inherit 3D models from their KiCAD standard library counterparts. Custom parts that do not have models available from KiCAD will have supporting models under `/3D_models/`.