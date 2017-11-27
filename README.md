# Spring Microservices
Code repository for [Spring Microservices](https://www.packtpub.com/application-development/spring-microservices?utm_source=github&utm_medium=repository&utm_campaign=9781786466686), published by Packt Publishing

There are no code files for chapters 1, 3, and 10. All hardware requirements are listed in the file named "Hardware and Software requirements". Any other requirements are mentioned in the book wherever necessary.

# OAuth 2.0 Samples
See /Spring-Microservices/Chapter 2/chapter2.boot-advanced
Oauth2 specs provide 5 authorizazion grants types:
- Authorization code grant
- Implicit grant
- Resource owner credentials grant
- Client credentials grant
- Refresh token grant

The sample cover the "Resource owner credentials grant" scenario.
RFC:
https://tools.ietf.org/html/rfc6749#section-4.3
https://tools.ietf.org/html/rfc6749#section-2.3.1

The project includes a file with the tests to import in ARC:
/Spring-Microservices/Chapter 2/chapter2.boot-advanced/arc-data-export-19-11-2017.json

In order to obtain the token, you need to send a POST to this URL:
http://localhost:8080/oauth/token

The Authorization header must contain the value "Basic xxx", where xxx is the base64 for client_id:client_secret (as decribed in RFC section-2.3.1).

# Related books
* [Spring Security 3.x Cookbook](https://www.packtpub.com/application-development/spring-security-3x-cookbook?utm_source=github&utm_medium=related&utm_campaign=9781782167525)
* [Learning Spring Boot](https://www.packtpub.com/application-development/learning-spring-boot?utm_source=github&utm_medium=related&utm_campaign=9781784393021)
* [Mastering Microservices with Java](https://www.packtpub.com/application-development/mastering-microservices-java?utm_source=github&utm_medium=related&utm_campaign=9781785285172) - to be published in June 2016


