---
Description: The domain name for the device's Home Network Provider, identifying the operator of the network.
ms.assetid: 7676e1d8-a414-401f-989c-9f60068b92d8
title: DomainName (Hotspot2) Element
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# DomainName (Hotspot2) Element

The domain name for the device's Home Network Provider, identifying the operator of the network.

``` syntax
<xs:element name="DomainName"
    minOccurs="0"
>
    <xs:simpleType>
        <xs:restriction
            base="string"
        >
            <xs:minLength
                value="1"
             />
            <xs:maxLength
                value="255"
             />
        </xs:restriction>
    </xs:simpleType>
</xs:element>
```

The element is defined by the [**Hotspot2**](wlan-profileschema-hotspot2-element.md) element.

 

 


