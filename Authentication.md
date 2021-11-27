# Authentication & Production Server
## What is JSON Web Token?

- [x]  JSON Web Token (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 



## When should you use JSON Web Tokens?
 - [x]  Here are some scenarios where JSON Web Tokens are useful:
### Authorization: This is the most common scenario for using JWT
### Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties.
## What is the JSON Web Token structure?
 - [x]  In its compact form, JSON Web Tokens consist of three parts separated by dots (.), which are:
## Header
### - The header typically consists of two parts: 
### 1. the type of the token, which is JWT,
### 2.  the signing algorithm being used, such as HMAC SHA256 or RSA.
## Payload
### - The second part of the token is the payload, which contains the claims.
### -  Claims are statements about an entity (typically, the user) and additional data. 
### - There are three types of claims: 
### 1. registered  : 
-  These are a set of predefined claims which are not mandatory but recommended, to provide a set of useful, interoperable claims. Some of them are: iss (issuer), exp (expiration time), sub (subject), aud (audience), and others.
### 2.  public : 
- these can be defined at will by those using JWTs. But to avoid collisions they should be defined in the IANA JSON Web Token Registry 
### 3.  private claims :
-  These are the custom claims created to share information between parties that agree on using them and are neither registered or public claims.

### How do JSON Web Tokens work?
- [x]  In authentication, when the user successfully logs in using their credentials, a JSON Web Token will be returned.
- [x]  Since tokens are credentials, great care must be taken to prevent security issues.
- [x]  In general, you should not keep tokens longer than required.

