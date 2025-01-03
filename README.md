# .NET Libraries Guide (Listed by Category)
* **API Flow**
  + [**FluentValidation:**](https://docs.fluentvalidation.net/en/latest/) Enables developers to maintain strongly defined validation rules for objects, while maintaining code self-documentation.
  + [**MediatR:**](https://www.nuget.org/packages/mediatr/) Allows objects to communicate independently (as decoupled components) via a 'mediator'.
  + [**SignalR:**](https://dotnet.microsoft.com/en-us/apps/aspnet/signalr) Promotes real-time 2-way communication for desktop, mobile, and web apps/assets.
  + [**YARP ('Yet Another Reverse Proxy'):**](https://microsoft.github.io/reverse-proxy/) Establishes reverse proxy servers.
* **Authorization**
  + [**Keycloak:**](https://learn.microsoft.com/en-us/dotnet/aspire/authentication/keycloak-integration?tabs=dotnet-cli) An open-source tool for access and identity management.
  + [**Microsoft.AspNetCore.Authentication.JwtBearer:**](https://learn.microsoft.com/en-us/dotnet/api/microsoft.aspnetcore.authentication.jwtbearer?view=aspnetcore-9.0) for handling secure JSON Web Token (JWT) authentication for web services and APIs. 
  + [**OpenIddict:**](https://documentation.openiddict.com/) Handles OAuth 2.0/OpenID Connect without dictating the user authorization process.
* **Background Tasks**
  + [**Hangfire:**](https://www.hangfire.io/) Allows for the creation, management, and performance monitoring of background processes, along with some advanced customization features.
  + [**Quartz.NET:**](https://www.quartz-scheduler.net/) An easy to use and easy to learn process scheduling system.
* **Dependency Injection (DI)**
  + [**Autofac:**](https://autofac.org/) Provides extra dependency management features, multi-interface support, and more flexibility than the built-in DI framework of ASP.NET Core.
  + [**Microsoft.Extensions.DependencyInjection:**](https://www.nuget.org/packages/microsoft.extensions.dependencyinjection) The DI framework that is built into/bundled with ASP.NET Core.
  + [**Scrutor:**](https://github.com/khellang/Scrutor) Allows for simplification of dependency registration without requiring a new DI container (from the native ASP.NET Core technology).
* **Hyper Text Transfer Protocol (HTTP)**
  + **Polly:** An HTTP request transient fault handling and resilience library.
  + **Refit:** An easy to use alternative to the HttpClient HTTP request class that does not require boilerplate code.
  + **RestSharp:** Another easy to use alternative to HttpClient that can consume REST APIs, but does not offer as much flexibility and support as Refit. 
* **Logging**
  + **NLog:** A free, flexible, and simpler logging solution that supports multiple .NET platforms.
  + **Serilog:** An easy to set up diagnostic logging library that also supports various .NET platforms. Offers structured logging.
* **Message Queues**
  + **MassTransit:** Enables simplified message routing over several service busses, such as ActiveMQ, Azure Service Bus, and RabbitMQ.
  + **NServiceBus:** Supplements message queue workflow with an abstraction layer and by guaranteeing message receipt and processing.
  + **RabbitMQ.Client:** Supports RabbitMQ message brokering for distributed systems.
* **Microsoft Excel**
  + **ClosedXML:**  A library for creating and modifying Excel files without needing Excel natively installed.
  + **EPPlus:** A library for working with different Excel objects (e.g., images, charts, tables, pivot tables) and functionalities (e.g., conditional formatting, data validation).
  + **Excel-DNA:** Integrates .NET functionality into Excel and allows for the installation, updating, and deployment of Excel add-ins.
* **Object-Relational Mapping (ORM)**
  + **Dapper:** Allows for fast database interactions and relies on SQL for easy database integrations.
  + **EF Core:** Reduces need for boilerplate code and supports LINQ interactions with various SQL database platforms. More complex and with a heavier learning curve than Dapper.
* **Testing**
  + **Bogus:** Instantly creates fake data for testing .NET apps.
  + **FluentAssertions:** Used for creating simple, efficient, and self-documented unit tests.
  + **Moq:** A testing library that can simulate objects for unit testing purposes.
  + **Testcontainers:** Instantly generates easily discardable containers for unit testing.

TODO: Add section on how a library is developed.
