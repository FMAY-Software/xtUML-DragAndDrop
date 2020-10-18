# xtuml Drag and Drop

## Description

This project enables drag and drop support for model elements in the Bridgepoint model explorer.  There are three types of drag and drop support added:

- Re-ordering of elements that have a reflexive ordering association.
- Moving an element from one parent into another (Cut/Paste).
- Copying an element from one parent into another (Copy/Paste).

## Requirements

R1.1 Enable drag and drop support in Bridgepoint Model Explorer   
R1.1.1 Valid drop conditions  
<a href="R1.1.2.1">R1.1.1.1 </a> When the element being dragged is over a sibling, enable drop if the element has a reflexive ordering association  
<a href="R1.1.2.2">R1.1.1.2 </a> When the element being dragged is over a different container that has the same type as its parent, drop shall be enabled  
R1.1.2 Handling drop  
<a href="R1.1.2.1">R1.1.2.1 </a> For the case of being dragged over a sibling the drop location shall be used to update the order of the element being dropped  
<a href="R1.1.2.2">R1.1.2.2 </a> For the case of a different container as the drop location, a move shall be performed by default.  If the copy key modifier is active at the point of drop a copy/paste shall be performed.


## Timeframe  

October 2020.    

## Demonstrations

Video demonstrating drag and drop:

<a id="Drag and Drop"></a>[Drag and Drop](https://youtu.be/1Z1rxAr0sxc)

## Pledging

This project does not make use of the <a id="Pledge Model"></a>[Pledge Model](https://fmaysoftware.wordpress.com/pledging-model/).  Rather this is a direct contribution from FMAY.  