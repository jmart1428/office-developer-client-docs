---
title: "PidLidTaskOwnership Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidLidTaskOwnership
api_type:
- COM
ms.assetid: 805dcb6c-f405-4c4d-8bca-af4bd9cd44fa
description: "Indicates the role of the current user relative to the task for Outlook 2013 or Outlook 2016."
---

# PidLidTaskOwnership Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Indicates the role of the current user relative to the task.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |dispidTaskOwnership  <br/> |
|Property set:  <br/> |PSETID_Task  <br/> |
|Long ID (LID):  <br/> |0x00008129  <br/> |
|Data type:  <br/> |PT_LONG  <br/> |
|Area:  <br/> |Task  <br/> |
   
## Remarks

This property must be one of the following values.
  
|**Value**|**Description**|
|:-----|:-----|
|0x00000000  <br/> |The task is not assigned. |
|0x00000001  <br/> |The task is the task assigner's copy of the task. |
|0x00000002  <br/> |The task is the task assignee's copy of the task. |
   
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides property set definitions and references to related Exchange Server protocol specifications.
    
[[MS-OXOTASK]](https://msdn.microsoft.com/library/55600ec0-6195-4730-8436-59c7931ef27e%28Office.15%29.aspx)
  
> Defines several objects that model the electronic equivalent of tasks, task assignments, and task updates.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

