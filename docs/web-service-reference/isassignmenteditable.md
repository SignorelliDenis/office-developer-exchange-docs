---
title: "IsAssignmentEditable"
 
 
manager: sethgros
ms.date: 9/17/2015
ms.audience: Developer
ms.topic: reference
 
localization_priority: Normal
api_name:
- IsAssignmentEditable
api_type:
- schema
ms.assetid: 0ddf9181-f65e-4ad6-ad69-7b074ea0f2e7
description: "The IsAssignmentEditable element represents the task type."
---

# IsAssignmentEditable

The **IsAssignmentEditable** element represents the task type. 
  
```
<IsAssignmentEditable/>
```

 **integer**
## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
#### Attributes

None.
  
#### Child elements

None.
  
#### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[Task](task.md) <br/> |Represents a task in the Exchange store.  <br/> |
   
## Text value

This property is read-only. The following table lists the possible values.
  
|**Value**|**Description**|
|:-----|:-----|
|0  <br/> |The default for all task items.  <br/> |
|1  <br/> |A task request.  <br/> |
|2  <br/> |A task acceptance from a recipient of a task request.  <br/> |
|3  <br/> |A task declination from a recipient of a task request.  <br/> |
|4  <br/> |An update to a previous task request.  <br/> |
|5  <br/> |Not used.  <br/> |
   
## Remarks

The schema that describes this element is located in the EWS virtual directory of the computer that is running MicrosoftExchange Server 2007 that has the Client Access server role installed.
  
## Element information

|||
|:-----|:-----|
|Namespace  <br/> |http://schemas.microsoft.com/exchange/services/2006/types  <br/> |
|Schema Name  <br/> |Types schema  <br/> |
|Validation File  <br/> |Types.xsd  <br/> |
|Can be Empty  <br/> |False  <br/> |
   
## See also

#### Concepts

[EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)
