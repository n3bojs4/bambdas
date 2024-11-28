rewrite user agent:
  
  ```java
  return requestResponse.request().withHeader(HttpHeader.httpHeader("User-Agent", "Mosilla FileF0x"));
  ```
add extra column searching for parameter id in json:

  ```java
  return requestResponse.request().parameterValue("id", HttpParameterType.JSON);
  ```
  
  
