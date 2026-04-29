---
title: "HTTP Status Codes Reference"
date: 2026-04-21
tags: []
---


The first digit of the code defines the Category:

1xx (Informational): "Hold on, I'm thinking/processing."

2xx (Success): "Everything is great. Here is your data."

3xx (Redirection): "The thing you want is somewhere else."

4xx (Client Error): "You made a mistake (bad URL, wrong password)."

5xx (Server Error): "I made a mistake (server crashed, database timed out)."
The following table provides a professional overview of the most common HTTP status codes, categorized by their functional intent and defined by formal technical standards.

| Code | Name | Category | Technical Definition |
| :--- | :--- | :--- | :--- |
| **200** | OK | Success | The request has succeeded. The information returned is dependent on the method used in the request. |
| **201** | Created | Success | The request has been fulfilled and has resulted in the successful creation of a new resource. |
| **204** | No Content | Success | The server has successfully fulfilled the request and there is no additional content to send in the response payload. |
| **301** | Moved Permanently | Redirection | The requested resource has been assigned a new permanent URI; future references should use the returned URI. |
| **304** | Not Modified | Redirection | Indicates that the resource has not been modified since the version specified by the request headers. |
| **400** | Bad Request | Client Error | The server cannot process the request due to a perceived client error, such as malformed request syntax. |
| **401** | Unauthorized | Client Error | The request has not been applied because it lacks valid authentication credentials for the target resource. |
| **403** | Forbidden | Client Error | The server understood the request but refuses to authorize it; re-authentication will not grant access. |
| **404** | Not Found | Client Error | The origin server did not find a current representation for the target resource or is unwilling to disclose its existence. |
| **405** | Method Not Allowed | Client Error | The method specified in the request is understood by the server but is not supported by the target resource. |
| **429** | Too Many Requests | Client Error | The user has transmitted an excessive number of requests in a given timeframe, exceeding rate-limiting policies. |
| **500** | Internal Server Error | Server Error | The server encountered an unexpected condition that prevented it from fulfilling the request. |
| **502** | Bad Gateway | Server Error | The server, while acting as a gateway or proxy, received an invalid response from an upstream server. |
| **503** | Service Unavailable | Server Error | The server is currently unable to handle the request due to temporary overloading or scheduled maintenance. |
| **504** | Gateway Timeout | Server Error | The server, acting as a gateway or proxy, did not receive a timely response from an upstream server. |
