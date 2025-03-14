---
title: "PidTagAdditionalRenEntryIds Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidTagAdditionalRenEntryIds
api_type:
- HeaderDef
ms.assetid: 8c6e7ca2-1824-4cca-bf69-3c1ea52727de
description: "Contains the entry IDs of certain special folders for Outlook 2013 and Outlook 2016."
---

# PidTagAdditionalRenEntryIds Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains the entry IDs of certain special folders. 
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_ADDITIONAL_REN_ENTRYIDS  <br/> |
|Identifier:  <br/> |0x36D8  <br/> |
|Data type:  <br/> |PT_MV_BINARY  <br/> |
|Area:  <br/> |Outlook application  <br/> |
   
## Remarks

The first five entries of this multi-valued property apply to following special folders, if they exist in the store:
  
0 - conflicts folder
  
1 - sync issues folder
  
2 - local failures folder
  
3 - server failures folder
  
4 - junk email folder
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides references to related Exchange Server protocol specifications.
    
[[MS-OXOSFLD]](https://msdn.microsoft.com/library/a60e9c16-2ba8-424b-b60c-385a8a2837cb%28Office.15%29.aspx)
  
> Specifies the properties and operations for creating and locating the special folders in a mailbox.
    
[[MS-OXPHISH]](https://msdn.microsoft.com/library/ed49ab26-ba13-4d4c-8a94-98d4ceecd4b7%28Office.15%29.aspx)
  
> Identifies and marks email messages that are designed to trick recipients into divulging sensitive information (such as passwords and other personal information) to a non-trustworthy source.
    
[[MS-OXCSPAM]](https://msdn.microsoft.com/library/522f8587-4aed-4cd6-831b-40bd87862189%28Office.15%29.aspx)
  
> Enables the handling of allow/block lists and the determination of junk email messages.
    
### Header files

Mapitags.h
  
> Contains definitions of properties listed as associated properties.
    
Mapidefs.h
  
> Provides data type definitions.
    
## See also



[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)


[About the Store API](https://msdn.microsoft.com/library/aa192884.aspx)

