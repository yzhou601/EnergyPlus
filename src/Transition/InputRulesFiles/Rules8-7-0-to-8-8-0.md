Input Changes
=============

This file documents the structural changes on the input of EnergyPlus that could affect interfaces, etc. 
This was previously an Excel workbook that made for very difficult version control, especially during busy times around code freezes.


# Object Change: `Output:Surfaces:List`

The only change is for field F1, which is A1.  Logic to apply:

if key = 'DecayCurvesfromZoneComponentLoads', change to = 'DecayCurvesFromComponentLoadsSummary'
