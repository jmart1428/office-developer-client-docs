---
title: "PidTagScheduleInfoFreeBusyAway Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- MAPI.PidTagScheduleInfoFreeBusyAway
api_type:
- COM
ms.assetid: 7b5d013a-15ac-469a-98c8-3ed1e80f6faf
description: "Contains the times for which the free status is set to OOF for Outlook 2013 or Outlook 2016."
---

# PidTagScheduleInfoFreeBusyAway Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains the times for which the free/busy status is set to OOF.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_SCHDINFO_FREEBUSY_OOF  <br/> |
|Identifier:  <br/> |0x6856  <br/> |
|Data type:  <br/> |PT_MV_BINARY  <br/> |
|Area:  <br/> |Free/Busy  <br/> |
   
## Remarks

The format, computation and constraints of this property are the same as those of **PR_SCHDINFO_FREEBUSY_TENTATIVE** ([PidTagScheduleInfoFreeBusyTentative](pidtagscheduleinfofreebusytentative-canonical-property.md)) but refer to appointments that are marked OOF on the associated calendar.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides references to related Exchange Server protocol specifications.
    
[[MS-OXOPFFB]](https://msdn.microsoft.com/library/1a527299-7211-4d27-a74c-b69bd0746320%28Office.15%29.aspx)
  
> Publishes the availability of a user or resource.
    
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

