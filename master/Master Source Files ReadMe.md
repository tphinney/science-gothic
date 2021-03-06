# About the Master folder

## General

tl;dr: The VFJ file is guaranteed to be the most up-to-date source. 

This folder contains font sources for the project. Sources can be VFC (FontLab VI native binary file format), VFJ (FontLab VI native JSON text format), or UFO (Universal Font Object, an open source text format). Additionally, there is a .designspace file, defining axes, masters and coordinates, which can be used with UFO or other formats.

- VFJ is the standard format for ongoing development work for the project. Normally, the latest sources will always be present in VFJ.

- VFC is being used in this project primarily for backups and individual developer work in progress. Any current tool that can open VFC can also open VFJ. So, if you want source, get the VFJ instead (although it may take longer to open).

- UFO will be added later, as part of the open source build chain.

## File Naming Conventions

- 3a or 4a refers to the number of Variable Font axes supported (3-axis or 4-axis). The difference is whether the slant (oblique) axis is present. This axis is generated mostly automatically by build scripts, with a little human tweaking. A new 4a font will normally be posted no less than once every two weeks (typically weekly).

- 18m or 36m refers to the number of masters present, 18 without slant, or 36 with slant/oblique.
