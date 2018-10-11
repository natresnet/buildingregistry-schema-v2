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

    Adde six new elements for Tier I and Tier II lighting for Interior, Exterior and Garage lighting
    
