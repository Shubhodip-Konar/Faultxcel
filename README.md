# Faultxcel
Fault seal analysis: Reservoir Juxtaposition and SGR triangular diagram

Faultxcel is macro based excel to determine the fault associated uncertainties. The excel can be helpful iduring hydrocarbon prospect analysis.
The excel generates triangular juxtaposition and shale gauge ratio diagram. Analysis on fault geometry and across fault pressure difference can be done to reduce uncertainty associated with fault sealing. 

# Installation
The macros are written in excel 2017. No specific software required running this excel. The excel is supposed to be a standalone analysis for individual faults under consideration. The analysis results can be published multiple times on requirement.  

# Usage
The excel is self explanatory, built as a workflow. The only worksheet avaliable is write protected, with the buttuons for data input and analysis. Simple explanations are provided against the buttons for the user. As a workflow, the buttuons are greyed out and deactivated intially and only get activated upon completion of a required input. 
The button 'Print Report', activated all throughout, can be used to print high qualities of images of the analysis. The images ares stored in a separate folder, with name including the prospect name, date of print and interpreter's name, in the location of the excel file.
The button 'Clear Slate' removes any previous analysis within the excel sheet. 

# Version
The present version is v1.16 beta testing version. 

# Reported Bugs
The following bugs are reported in the present version of the macro based excel. The reported bugs are not related to technical analysis and will be solved in the following versions.

  1. Error regarding non zero value during data plotting during 'Fault Geometry' and 'AFPD' analysis.
  
      Solution: Redo the analysis. No pop-up in the consequent try.
      
  2. No default Volume of shale cutoff in the macro.
      
      Solution: The user needs to use slider bar for Vshale setting at least once.
      
  3. Temporary folders don't clear up sometime. This results in same analysis window popping out even though some parameters are changed.
  
      Solution: Manually clean system temporary folder.
 
In case if you find any bug in the present beta version please revert back with details of the same to shubhodip.konar@gmail.com. Mention 'Faultxcel Bug' in the subject head

# Next Version
The developer plans to release the next version by November 2021 with significant upgradation and bug fixing. 
