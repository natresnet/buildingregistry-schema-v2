# buildingregistry-schema-v2
Updated to version 2.01 August 19, 2015

Updated to version 2.02 September 25, 2015

Update to version 2.03 October 25, 2015

The 2.03 changes are as follows:
Under Ratings/Registry two new elements have been added as follows:
    ConditionedBasementArea default=0
    UnconditionedBasementArea default=0
    
Under Ratings/HomeEnergyPerformance/HVACMechVentSystems/Systems/Type the allowed enumeration strings have been modified
    "Standard" has been deleted
    "Supply" has been added
    "Exhaust" has been added
    
Under Ratings/WarningFlags/BuildingAttributeFlags a spelling error has been corrected for the element name
    "AverageCeilingHeightValue"
    
Updated to version 2.06 August 22, 2017
    added "TestedACH50" and "CFM25_CFA" to  Ratings / HomeEnergyPerformance / Enclosure element

Update to version 2.07 November 29, 2017
    removed "TestedACH50" and "CFM25_CFA"
    added Threshold to Type with annotation under MeasuredEnclosureTightness and DuctSystems
    
Update to version 2.07 December 20, 2017
    Added new elements for Tested and Threshold envelope and duct leakage values and 
    added and revised annotations
    
Update to version 2.07 January 4, 2018
    Added enumeration for "Threshold ductless" and "Threshold ducted" duct system Types. 
    Modified documentation accordingly.
    
Update to version 2.07 January 9, 2018
    Added element for IADsave 

Version 2.08 added March 8, 2018
    "IADsave" element added to Ratings
    "propane" added to enumerations for HotWaterSystems Type
    
March 20, 2018
    Added "UEF" enumeration to HotWaterSystem EfficiencyUnits
    
August 21, 2018
    Added "Right-Energy HERS" enumeration to Ratings/Registry/Software

October 11, 2018
    Added six new elements for Tier I and Tier II lighting for Interior, Exterior and Garage lighting
    
May 1, 2019
    Added new enumerations for new EPA multifamily and single family enumerations. Updated version number to 2.11.

May 2, 2019
    Revised version 2.11 to remove PermitRequired element and dded Puerto Rico and US Virgin Islands enumeration for EPA
    
May 28, 2019
    Added Standard301Version element to Ratings>Registry as optional input field. Updated Version Number to v2.12
    
June 26, 2019
    Added optional element EPAAppID for EPA Rater Pro Application ID to be assinged by the EPA Application

August 14, 2019
    Revised version number to 2.13. Added US Virgin Islands to State enumeration list. Added TestedLeakageException element to Ratings > HomeEnergyPerformance > DuctSystems > System element
    
September 13, 2019
    Modified TestedLeakageException element to make it optional
       
January 1, 2020
    Added enumeration for "biomass" the hot water heater system Type

January 2, 2020
    Updated version numbering to include additional numbering for patches to follow Semantic X.Y.Z Versioning rules
    
September 4, 2020
    Updated to version 2.13.7 to include HVAC Comissioningdate in element HVACComissioning. Also includes changes to annotations in TestedLeakageException element.

September 11, 2020
    Updated version number from 2.13.7 to 2.14.02 to include xerces enhancements to assets

September 28, 2020
    Updated to version number 2.14.03, which makes certain Priority 2 and Priority 3 schema inputs optional.

October 30, 2020
    Small changes to annotations describing actions for PercentDuctInsideAttached and AirHandlerInside elements

November 2, 2020
    Update to version 2.14.04, which moves simple types from refs into their respective elements.
    Added new enumerations (Not Applicable) for TestmetnodRefrigerantCharge and MeteringDeviceType
    
January 29, 2021
    Update to version 2.14.06 to make BlowerfanWattDraw and BlowerfanEfficiency minOccurs = "0"
    
February 16, 2022
    Major update to version 3.0.01 to include IECC 2009 and 2018 Section 405 performance compliance reporting data.
    
March 15, 2022
    Version 3.0.01 temporarily withdrawn
    
August 18, 2022
    Version 3.0.01 deleted until revised
    
    
