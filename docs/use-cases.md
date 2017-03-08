# 6. Use Cases

This document describes the method of exchange for business documents between two Access Points. Access Points use business discovery services, implemented by DCL and DCP, to determine the receiver of an electronic business document. Access Points therefore act as clients to business discovery services. The DCP and DCL business discovery services are detailed in separate implementation guides. 

The use cases listed in this section are separated in two categories: 
 1. Use cases dealing with the actual operation of sending and receiving business documents; and 
 2. Use cases dealing with configuration and registration of information to enable the operational use cases. 
 
## 6.1 Sending a Business Document (including Dynamic Discovery) 

![Usecase-Logo](/images/usecase-6.1.PNG)


## 6.2 Maintenance of Dynamic Discovery Information 
![Usecase2-Logo](/images/Usecase-6.2.PNG)


## 6.3 Use Case Descriptions 
The table below provides a list of business and system use cases that represent the functionality required to support the eDelivery solution. 

Table 2: Relevant Use Cases 

|  |  |  |  |  |
| --- |------- | --- | ------- | ------- |
**Use Case ID** |**Actors**| **Description** |**High Level Process**| **Present In** |
SUC002 | Digital Capability Publisher, Access Point, Digital Capability Locator | Register DCP Alias Address | Maintenance | Implementation guides for: Access Point, Digital Capability Publisher and Digital Capability Locator |
SUC003 | Access Point, Digital Capability Publisher | Register Capability | Maintenance | Implementation guides for: Digital Capability Publisher and Access Point |
SUC005 | Access Point, Digital Capability Publisher, Digital Capability Locator | Lookup Participant's Digital Capabilities (this includes SUC006) | Sending a business document | Implementation guides for: Access Point, Digital Capability Publisher and Digital Capability Locator |
SUC006 | Access Point, Digital Capability Locator | Lookup DCP Alias Address | Sending a business document | Implementation guides for: Access Point and Digital Capability Locator |














 







 |