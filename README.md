# .NET Libraries Guide
  
#### Table of Contents
1. [API Flow Libraries](#api-flow)
2. [Authorization Libraries](#auth)
3. [Background Tasks Libraries](#bg-tasks)
4. [Dependency Injection (DI) Libraries](#di)
5. [Hyper Text Transfer Protocol (HTTP) Libraries](#http)
6. [Logging Libraries](#logging)
7. [Message Queues Libraries](#msg-queues)
8. [Microsoft Excel Libraries](#excel)
9. [Object-Relational Mapping (ORM) Libraries](#orm)
10. [Testing Libraries](#testing)
11. [Supplemental Resources](#supplemental)
  
<hr />
  
## 1. <a name="api-flow">**API Flow Libraries**</a>
  + [**FluentValidation:**](https://docs.fluentvalidation.net/en/latest/) Enables developers to maintain strongly defined validation rules for objects, while maintaining code self-documentation.
  + [**MediatR:**](https://www.nuget.org/packages/mediatr/) Allows objects to communicate independently (as decoupled components) via a 'mediator'.
  + [**SignalR:**](https://dotnet.microsoft.com/en-us/apps/aspnet/signalr) Promotes real-time 2-way communication for desktop, mobile, and web apps/assets.
  + [**YARP ('Yet Another Reverse Proxy'):**](https://microsoft.github.io/reverse-proxy/) Establishes reverse proxy servers.
  
<hr />
    
## 2. <a name="auth">**Authorization Libraries**</a>
  + [**Keycloak:**](https://learn.microsoft.com/en-us/dotnet/aspire/authentication/keycloak-integration?tabs=dotnet-cli) An open-source tool for access and identity management.
  + [**Microsoft.AspNetCore.Authentication.Identity:**](https://learn.microsoft.com/en-us/aspnet/core/security/authentication/identity?view=aspnetcore-9.0&tabs=visual-studio) Provides user interface components and APIs for identification purposes (e.g., role-based authorization/RBAC, multi-factor authentication, external sign-ins, password management, signing up and in users).
  + [**Microsoft.AspNetCore.Authentication.JwtBearer:**](https://learn.microsoft.com/en-us/dotnet/api/microsoft.aspnetcore.authentication.jwtbearer?view=aspnetcore-9.0) for handling secure JSON Web Token (JWT) authentication for web services and APIs. 
  + [**OpenIddict:**](https://documentation.openiddict.com/) Handles OAuth 2.0/OpenID Connect without dictating the user authorization process.
  
<hr />
  
## 3. <a name="bg-tasks">**Background Tasks Libraries**</a>
  + [**Hangfire:**](https://www.hangfire.io/) Allows for the creation, management, and performance monitoring of background processes, along with some advanced customization features.
  + [**Quartz.NET:**](https://www.quartz-scheduler.net/) An easy to use and easy to learn process scheduling system.
     
<hr />
  
## 4. <a name="di">**Dependency Injection (DI) Libraries**</a>
  + [**Autofac:**](https://autofac.org/) Provides extra dependency management features, multi-interface support, and more flexibility than the built-in DI framework of ASP.NET Core.
  + [**Microsoft.Extensions.DependencyInjection:**](https://www.nuget.org/packages/microsoft.extensions.dependencyinjection) The DI framework that is built into/bundled with ASP.NET Core.
  + [**Scrutor:**](https://github.com/khellang/Scrutor) Allows for simplification of dependency registration without requiring a new DI container (from the native ASP.NET Core technology).

<hr />
  
## 5. <a name="http">**Hyper Text Transfer Protocol (HTTP) Libraries**</a>
  + [**Polly:**](https://www.pollydocs.org/) An HTTP request transient fault handling and resilience library.
  + [**Refit:**](https://github.com/reactiveui/refit) An easy to use alternative to the HttpClient HTTP request class that does not require boilerplate code.
  + [**RestSharp:**](https://restsharp.dev/) Another easy to use alternative to HttpClient that can consume REST APIs, but does not offer as much flexibility and support as Refit.

<hr />
  
## 6. <a name="logging">**Logging Libraries**</a>
  + [**NLog:**](https://nlog-project.org/) A free, flexible, and simpler logging solution that supports multiple .NET platforms.
  + [**OpenTelemetry:**](https://opentelemetry.io/) An open-source solution for gathering, processing, and exporting telemetry data (e.g., metrics, logs, traces) from apps and infrastructure.
  + [**Serilog:**](https://serilog.net/) An easy to set up diagnostic logging library that also supports various .NET platforms. Offers structured logging.
  
<hr />
  
## 7. <a name="msg-queues">**Message Queues Libraries**</a>
  + [**MassTransit:**](https://masstransit.io/) Enables simplified message routing over several service busses, such as ActiveMQ, Azure Service Bus, and RabbitMQ.
  + [**NServiceBus:**](https://particular.net/nservicebus) Supplements message queue workflow with an abstraction layer and by guaranteeing message receipt and processing.
  + [**RabbitMQ.Client:**](https://www.rabbitmq.com/client-libraries/dotnet) Supports RabbitMQ message brokering for distributed systems.
  
<hr />
  
## 8. <a name="excel">**Microsoft Excel Libraries**</a>
  + [**ClosedXML:**](https://docs.closedxml.io/en/latest/)  A library for creating and modifying Excel files without needing Excel natively installed.
  + [**EPPlus:**](https://www.epplussoftware.com/) A library for working with different Excel objects (e.g., images, charts, tables, pivot tables) and functionalities (e.g., conditional formatting, data validation).
  + [**Excel-DNA:**](https://excel-dna.net/) Integrates .NET functionality into Excel and allows for the installation, updating, and deployment of Excel add-ins.
  
<hr />
  
## 9. <a name="orm">**Object-Relational Mapping (ORM) Libraries**</a>
  + [**Dapper:**](https://www.learndapper.com/) Allows for fast database interactions and relies on SQL for easy database integrations.
  + [**EF Core:**](https://learn.microsoft.com/en-us/ef/core/) Reduces need for boilerplate code and supports LINQ interactions with various SQL database platforms. More complex and with a heavier learning curve than Dapper.
  
<hr />
  
## 10. <a name="testing">**Testing Libraries**</a>
  + [**Bogus:**](https://github.com/bchavez/Bogus) Instantly creates fake data for testing .NET apps.
  + [**FluentAssertions:**](https://fluentassertions.com/) Used for creating simple, efficient, and self-documented unit tests.
  + [**Moq:**](https://github.com/devlooped/moq) A testing library that can simulate objects for unit testing purposes.
  + [**Testcontainers:**](https://dotnet.testcontainers.org/) Instantly generates easily discardable containers for unit testing.
  + [**Verify:**](https://github.com/VerifyTests/Verify) Serializes and stores test results, with future test results used to evaluate data integrity and if snapshots should be updated.
  + [**xUnit.net:**](https://xunit.net/?tabs=cs) A unit-testing technology for the .NET framework, including support for C#, F#, and Visual Basic.
  
<hr />
  
## 11. <a name="supplemental">Supplemental Resources</a>
  
* *[Official Microsoft .NET Page](https://dotnet.microsoft.com/en-us/)*  
* *[Official Microsoft Guide on How to Create a .NET Class Library](https://learn.microsoft.com/en-us/dotnet/core/tutorials/library-with-visual-studio)*
* *[Back-end Web Development with .NET for Beginners (Official Microsoft Video Series)](https://learn.microsoft.com/en-us/shows/back-end-web-development-with-dotnet-for-beginners/)*
