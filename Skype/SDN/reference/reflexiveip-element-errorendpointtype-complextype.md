---
title: ReflexiveIP element (ErrorEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")
ms.prod: SKYPE
ms.assetid: ad668abe-8550-8a6a-3f88-e55d735a0019
---


# ReflexiveIP element (ErrorEndPointType complexType) (Skype for Business SDN Interface 2.2, Schema "D")
IP used outside of the NAT. 
 **Last modified:** October 07, 2015
  
    
    


## Element information


|||
|:-----|:-----|
|**Element type**| [ipAddressPattern](ipaddresspattern-simpletype.md)|
|**Namespace**||
|**Schema file**|SDNInterface.Schema.D.XSD |
   

## Definition


```XML


    <xs:element name="ReflexiveIP"  type="ipAddressPattern" minOccurs="0">
    
    </xs:element>
  
```


## Elements and attributes

If the schema defines specific requirements, such as **sequence**, **minOccurs**, **maxOccurs**, and **choice**, see the definition section. 
  
    
    

### Parent elements



|**Element**|**Type**|**Description**|
|:-----|:-----|:-----|
| [EndPoint](endpoint-element-errortype-complextype.md)| [ErrorEndPointType](errorendpointtype-complextype.md)|Endpoint involved in the ended SIP call. |
   

### Child elements

None. 
  
    
    

### Attributes

None. 
  
    
    
