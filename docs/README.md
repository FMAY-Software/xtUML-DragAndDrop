# xtuml Drag and Drop

## Description

This project enables drag and drop support for model elements in the Bridgepoint model explorer.  There are three types of drag and drop support added:

- Re-ordering of elements that have a reflexive ordering association.
- Moving an element from one parent into another (Cut/Paste).
- Copying an element from one parent into another (Copy/Paste).

## Requirements

R1.1 Enable drag and drop support in Bridgepoint Model Explorer   
R1.1.1 Valid drop conditions  
R1.1.1.1 When the element being dragged is over a sibling, enable drop if the element has a reflexive ordering association  
R1.1.1.2 When the element being dragged is over a different container that has the same type as its parent, drop shall be enabled  
R1.1.2 Handling drop  
R1.1.2.1 For the case of being dragged over a sibling the drop location shall be used to update the order of the element being dropped  
R1.1.2.2 For the case of a different container as the drop location, a move shall be performed by default.  If the copy key modifier is active at the point of drop a copy/paste shall be performed.


## Timeframe  

October 2020.    

## Deliverables

<a id="Project Builds"></a>[Project Builds](http://fmay-software.s3-website.us-east-2.amazonaws.com)

## Demonstrations

Video demonstrating drag and drop:

<a id="Drag and Drop"></a>[Drag and Drop](https://youtu.be/Xd5AvVafGyk)

## Engineering Notes

<a id="Drag and Drop Implementation Note"></A>[Drag and Drop Implementation](https://github.com/FMAY-Software/bridgepoint/blob/73ea6c3a22a245d66408fb46070ca1130aab1fff/doc-bridgepoint/notes/fmay_Drag_and_Drop/DragAndDrop.int.adoc)

## Pledging

This project does not make use of the <a id="Pledge Model"></a>[Pledge Model](https://fmaysoftware.wordpress.com/pledging-model/).  Rather this is a direct contribution from FMAY.  
