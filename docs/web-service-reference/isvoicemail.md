---
title: "IsVoicemail" 
manager: sethgros
ms.date: 09/17/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- IsVoicemail
api_type:
- schema
ms.assetid: 96d81d6e-4b75-43ad-b151-2dd4fd57db94
description: "The IsVoicemail element indicates whether incoming messages must be voice mail messages in order for the condition or exception to apply."
---

# IsVoicemail

The **IsVoicemail** element indicates whether incoming messages must be voice mail messages in order for the condition or exception to apply. 
  
```XML
<IsVoicemail>true | false</IsVoicemail>
```

**Boolean**

## Attributes and elements

The following sections describe attributes, child elements, and parent elements.
  
### Attributes

None.
  
### Child elements

None.
  
### Parent elements

|**Element**|**Description**|
|:-----|:-----|
|[Conditions](conditions.md) <br/> |Represents the conditions that, when fulfilled, will trigger the rule actions for a rule.  <br/> |
|[Exceptions](exceptions.md) <br/> |Represents the exceptions that represent all the available rule exception conditions for an Inbox rule.  <br/> |
   
## Text value

A text value of **true** indicates that the message must be a voice mail message in order for the condition or exception to apply. A value of **false** indicates that the message must not be a voice mail message in order for the condition or exception to apply. 
  
## Remarks

The schema that describes this element is located in the IIS virtual directory that hosts Exchange Web Services.
  
## Element information

|Item|Value|
|:-----|:-----|
|Namespace  <br/> |https://schemas.microsoft.com/exchange/services/2006/messages  <br/> |
|Schema Name  <br/> |Messages schema  <br/> |
|Validation File  <br/> |Messages.xsd  <br/> |
|Can be Empty  <br/> |True  <br/> |
   
## See also

- [EWS XML elements in Exchange](ews-xml-elements-in-exchange.md)
