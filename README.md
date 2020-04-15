# CATIA-R2018x-VBScripts
I have added some of my VBScript macros from 3DExperience CATIA here.

1. Update Drawing macro
  This macro handles updating of all the views in the drawing from all sheets, update drawing heading fields from related part metadata and adding made, checked and approved by user input.
  
  
2. Rename Drawing macro
  This macro was made to enable user to add multiple drawings under same part or assembly. It allows to add a suffix for the drawing name(number).
  
3. Calculate weight for assembly or part
  This script will calculate weight for a One level Assembly or part. It will scroll down all the parts in the first level of assembly (not drilling to sub-assemblies) and get either Calculated Mass or Declared Mass. It will also add this value for a custom parameter called "Weight_PLM" for each part and finally the assembly. Comments in finnish, apologies :)
 
4. Hide planes in assembly
  This script will go through assembly first level parts and hide all sketches, planes, geometrical elements and axis systems from each part.

5. Drawing part parameters
  This script works on drawing app. It will fetch sheetmetal plate thickness, bending radius, K-factor and measurements W-,H- and L- from the parent part of the drawing. Values are written to drawing text elements. Parent part needs to be opened and top level selected manually before script works. W-,H- and L- are manually measured dimensions from part which have been named and saved to geometrical set. Comments again in finnish
