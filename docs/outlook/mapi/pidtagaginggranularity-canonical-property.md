---
title: "PidTagAgingGranularity Canonical Property"
description: Outlines the PidTagAgingGranularity canonical property, which represents a unit of time used in determining the length of time an item remains in a folder.
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidTagAgingGranularity
api_type:
- HeaderDef
ms.assetid: b79ec87d-d97c-4e6c-899b-78ebf1b485a7
---

# PidTagAgingGranularity Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Represents the unit of time that is used in determining the length of time an item remains in a folder before the item is archived.
  
|Property|Value|
|:-----|:-----|
|Associated properties:  <br/> |PR_AGING_GRANULARITY  <br/> |
|Identifier:  <br/> |0x36EE  <br/> |
|Data type:  <br/> |PT_LONG  <br/> |
|Area:  <br/> |Miscellaneous  <br/> |
   
## Remarks

The possible values for **PR_AGING_GRANULARITY** can be one of the following. 
  
|**Name**|**Value**|**Description**|
|:-----|:-----|:-----|
|**AG_MONTHS** <br/> |0  <br/> |**PR_AGING_PERIOD** is defined in number of months. |
|**AG_WEEKS** <br/> |1  <br/> |**PR_AGING_PERIOD** is defined in number of weeks. |
|**AG_DAYS** <br/> |2  <br/> |**PR_AGING_PERIOD** is defined in number of days. |
   
The length of time that an item remains in a folder before the item is archived is determined by two properties, [PR_AGING_PERIOD](pidtagagingperiod-canonical-property.md) and **PR_AGING_GRANULARITY**. **PR_AGING_PERIOD** represents the number of time units that the item remains in the folder before it is archived. 
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides references to related Exchange Server protocol specifications.
    
[[MS-OXCFXICS]](https://msdn.microsoft.com/library/b9752f3d-d50d-44b8-9e6b-608a117c8532%28Office.15%29.aspx)
  
> Defines the basic data structures that are used in remote operations.
    
[[MS-OXOMSG]](https://msdn.microsoft.com/library/daa9120f-f325-4afb-a738-28f91049ab3c%28Office.15%29.aspx)
  
> Specifies the properties and operations that are permissible for email message objects.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
Mapitags.h
  
> Contains definitions of properties listed as alternate names.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

