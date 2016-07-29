# Laudanum2
Web post-exploitation payloads for penetration testing.  It is currently in early stages of development.

## Goals
Laudanum2 is a rewrite of the [Laudanum project](https://sourceforge.net/projects/laudanum/) with the following primary goals:

* A single shared client-side (i.e. browser) codebase that works across all major browsers and with all Laudanum2 server-side languages 
* A modular framework that can support multiple tools across various server-side languages such as .jsp, .asp, .php, and others
* A laudanum2 payload packaging script that will provide options to bundle laudanum2 in different configurations to suit various penetration testing scenarios
* A means of whitelisting access to payloads once they are deployed such that they are not available to unauthorized users

## Reference Implementation
The server-side reference implementation will be written as a Java Servlet. Java was chosen for this purpose because it can accomodate all types of functionality we can think og and it is a common target for this type of payload.

