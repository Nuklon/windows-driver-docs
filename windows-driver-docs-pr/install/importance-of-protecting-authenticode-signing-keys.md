---
title: Importance of Protecting Authenticode Signing Keys
description: Importance of Protecting Authenticode Signing Keys
keywords:
- driver signing WDK , cryptographic keys
- signing drivers WDK , cryptographic keys
- digital signatures WDK , cryptographic keys
- signatures WDK , cryptographic keys
- cryptography WDK driver signing
- keys WDK driver signing
ms.date: 09/30/2024
---

# Importance of Protecting Authenticode Signing Keys


The cryptographic keys that are at the heart of the Authenticode signing process must be well protected and treated with the same care as the publisher's most valuable assets. These keys represent an organization's identity. Any code that is signed with these keys appears to Windows as if it contains a valid digital signature that can be traced to the organization. If the keys are stolen, they could be used to fraudulently sign malicious code and possibly result in the delivery of code that contains Trojan or a virus that appears to come from a legitimate publisher.


 

 





