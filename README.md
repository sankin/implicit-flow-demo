# OpenID Connect: Implicit Flow Demo Client Application

[About](#about) </br>
[User Guide](#user-guide) </br>

## About
The repository contains code for a sample Spring Boot application to demonstrate the OAuth 2.0 / OpenID Connect Implicit flow using Nat Sakimura's JavaScript library.

* https://github.com/GluuFederation/openid-implicit-client
* https://nat.sakimura.org/2014/12/10/making-a-javascript-openid-connect-client/

## Prerequisites

* Maven 3.3.5
* Java 8

## User Guide

To start the application: `mvn clean spring-boot:run`

Then, open your browser and navigate to `http://localhost:9090/implicit-test.html`

To change the port number, edit `resources/application.properties`
