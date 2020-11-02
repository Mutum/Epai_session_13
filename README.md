# Epai_session_13

Here we are doing three thing :
- create regular polygon - no worries read further to know what it is
- create custom polygon - enabling sequencing properties and inserting a customer function... read further below

## Definition
A regular strictly convex polygon is a polygon that has the following characteristics:
- all interior angles are less than 180
- all sides have equal length

## Formulae

For a regular strictly convex polygon with:
- n edges (=n vertices)
- R circumradius
- interiorAngle=(n−2)⋅180n
- edgeLength,s=2⋅R⋅sin(πn)
- apothem,a=R⋅cos(πn)
- area=12⋅n⋅s⋅a
- perimeter=n⋅s

## Objective 1 -  polygon
Create a Polygon Class where initializer takes in:
- number of edges/vertices
- circumradius
that can provide these properties:
- # edges
- # vertices
- interior angle
- edge length
- apothem
- area
- perimeter
that has these functionalities:
- a proper __repr__ function
- implements equality (==) based on # vertices and circumradius (__eq__)
- implements > based on number of vertices only (__gt__)

Objective 2 - Custom Polygon :
Implement a Custom Polygon sequence type where initializer takes in:
- number of vertices for largest polygon in the sequence
- common circumradius for all polygons
that can provide these properties:
- max efficiency polygon: returns the Polygon with the highest area: perimeter ratio
that has these functionalities:
- functions as a sequence type (__getitem__)
- supports the len() function (__len__)
- has a proper representation (__repr__)

Result :
Function call file:
- Import polygon and custom polygon functionalities
 - Show most efficient polygon for edge from 3 untill 25 
 
 Additional:
 - Certain testing are done to validate code
