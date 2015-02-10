# CMMN Stencils

The goal of this project is to provide CMMN stencils as specified in the [OMG CMMN 1.0](http://www.omg.org/spec/CMMN/1.0/) specification. These stencils can be 
used in different modelling or drawing tools in order to foster the modelling with CMMN.

## Supported elements

  - Plan Model
  - Stage
  - Discretionary stage
  - Plan Fragment
  - Task
  - Discretionary task
  - Milestone
  - Event Listener
  - Criteria: entry and exit

## Scalable Vector Graphics

The basic stencils are Scalable Vector Graphics (SVG) created using [Inkscape](https://inkscape.org). The following general ideas has been introduced:
 -   the shapes are created in a way, that a 100% zoom should be well readable on a 1600x1200px display
 -   the general line thickness is 2px, to avoid line escapes on a down-scaled printout 
 -   plan model shape may contain four stage shapes without zoom
 -   stage shape may contain nine task shapes without zoom 

 !(Default Sizing)[svg/size.png]
 
## yED Palette

[yED](http://www.yworks.com/en/products/yfiles/yed/) is a powerful open-source graph editor, which allows to create beautiful diagrams. It has pre-build palettes for simple UML 2.0 and BPMN 2.0 modelling, which are just enough to create overviews diagrams. If you are interested in creating real models (UML 2, BPMN 2.x or CMMN 1.x) consider use of modelling tools. 

In order to enrich yED with ability to draw CMMN diagrams, a simple CMMN palette has been created. For installation, download the CMMN.graphml file, open yEd, goto *Edit* > *Manage Palette...* > *Import Section...* > and pick the downloaded file.

!(yED Palette Installation Steps)[yEd/install-palette.png] 

