---
title: "Public API Example Cloud"
type: docs
url: /public-api-example-cloud/
weight: 90
---

## **Overview**
This section introduces Aspose.Video for Cloud specific Resources & Operations.
#### **Base URI**
```java

https://api.aspose.cloud/v1.1/video

```

In the rest of documentation base URI presented as '~' character.
#### **Input and Output Format**
Aspose.Video cloud supports request body data and response data formatted as JSON or XML. Default format is JSON.
#### **Errors**
Aspose.Video for Cloud API performs communication errors by using HTTP Status Codes with details passed in JSON or XML objects.

The main patterns are:
2xx - The request was received and accepted.
4xx - Error occured while processing the request. Invalid parameter or missing file can cause this error.
5xx - The request was received and accepted, but an error occurred in the Aspose.Video for Cloud service while processing it.
###### **HTTP Status Codes**

|**Code**|**Description**|
| :- | :- |
|200|The request has succeeded.|
|201|The request has been fulfilled and resulted in a new resource being created.|
|204|The request has been fulfilled and resource(s) were removed.|
|400|Failed to handle the request due to invalid parameter or missing resource.|
|401|Authorization failed.|
|404|Requested resource was not found.|
|405|Requested method is not allowed.|
|500|Internal serverver error occured while processing the request.|
###### **Example Error Response**
```java

Status: 404 Not Found

```

```java

{

  "error": {

    "code": "FileNotFound",

    "message": "Can't find file with given name 'sample.avi' and folder 'My videos'."

  }

}

```
**

--



