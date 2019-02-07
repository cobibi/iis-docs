---
title: "IHttpRequest Interface | Microsoft Docs"
ms.custom: ""
ms.date: "10/07/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: f5f0c9bf-e374-a948-63bc-1b2c50555751
caps.latest.revision: 20
author: "shirhatti"
manager: "wpickett"
---
# IHttpRequest Interface
Provides an interface to an HTTP request object. You can use the methods in the `IHttpRequest` interface to retrieve and modify data in the current HTTP request.  
  
## Syntax  
  
```cpp  
class IHttpRequest  
```  
  
## Methods  
 The following table lists the methods exposed by the `IHttpRequest` interface.  
  
|Name|Description|  
|----------|-----------------|  
|[DeleteHeader](../../web-development-reference\webdev-native-api-reference/ihttprequest-deleteheader-method.md)|Deletes an HTTP header from the request.|  
|[GetClientCertificate](../../web-development-reference\webdev-native-api-reference/ihttprequest-getclientcertificate-method.md)|Retrieves the client certificate associated with the request.|  
|[GetForwardedUrl](../../web-development-reference\webdev-native-api-reference/ihttprequest-getforwardedurl-method.md)|Returns the forwarded URL.|  
|[GetHeader](../../web-development-reference\webdev-native-api-reference/ihttprequest-getheader-method.md)|Returns the value of a specified HTTP header.|  
|[GetHeaderChanges](../../web-development-reference\webdev-native-api-reference/ihttprequest-getheaderchanges-method.md)|Retrieves the changes to the server headers for the current request.|  
|[GetHttpMethod](../../web-development-reference\webdev-native-api-reference/ihttprequest-gethttpmethod-method.md)|Returns the HTTP method for the current request.|  
|[GetHttpVersion](../../web-development-reference\webdev-native-api-reference/ihttprequest-gethttpversion-method.md)|Returns the HTTP version for the request.|  
|[GetLocalAddress](../../web-development-reference\webdev-native-api-reference/ihttprequest-getlocaladdress-method.md)|Returns the address of the local interface for the current request.|  
|[GetRawHttpRequest](../../web-development-reference\webdev-native-api-reference/ihttprequest-getrawhttprequest-method.md)|Returns a structure that contains the raw HTTP request.|  
|[GetRemainingEntityBytes](../../web-development-reference\webdev-native-api-reference/ihttprequest-getremainingentitybytes-method.md)|Returns the number of remaining bytes to be read from the client.|  
|[GetRemoteAddress](../../web-development-reference\webdev-native-api-reference/ihttprequest-getremoteaddress-method.md)|Returns the remote address of the client's interface for the current request.|  
|[GetSiteId](../../web-development-reference\webdev-native-api-reference/ihttprequest-getsiteid-method.md)|Retrieves the site ID for the current HTTP request.|  
|[GetUrlChanged](../../web-development-reference\webdev-native-api-reference/ihttprequest-geturlchanged-method.md)|Determines whether the request URL has been modified.|  
|[NegotiateClientCertificate](../../web-development-reference\webdev-native-api-reference/ihttprequest-negotiateclientcertificate-method.md)|Initiates client certificate negotiation with a Web client.|  
|[ReadEntityBody](../../web-development-reference\webdev-native-api-reference/ihttprequest-readentitybody-method.md)|Returns the HTTP request entity body.|  
|[SetEntityBody](../../web-development-reference\webdev-native-api-reference/ihttprequest-insertentitybody-method.md)|Replaces the existing HTTP request body with new data.|  
|[SetHeader](../../web-development-reference\webdev-native-api-reference/ihttprequest-setheader-method.md)|Sets or appends the value of a specified HTTP request header.|  
|[SetHttpMethod](../../web-development-reference\webdev-native-api-reference/ihttprequest-sethttpmethod-method.md)|Sets the HTTP method for the request.|  
|[SetUrl](../../web-development-reference\webdev-native-api-reference/ihttprequest-seturl-method.md)|Modifies the request URL.|  
  
## Derived Classes  
  
|Name|Description|  
|----------|-----------------|  
|[IHttpRequest2](../../web-development-reference\webdev-native-api-reference/ihttprequest2-interface.md)|Provides an interface for retrieving the channel binding token (CBT) being used for request validation.|  
  
## Related Sections  
 [Web Server Core Interfaces](../../web-development-reference\webdev-native-api-reference/web-server-core-interfaces.md)  
  
 [IHttpResponse Interface](../../web-development-reference\webdev-native-api-reference/ihttpresponse-interface.md)  
  
## See Also  
 [IHttpContext Interface](../../web-development-reference\webdev-native-api-reference/ihttpcontext-interface.md)