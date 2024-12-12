# .NET Libraries Guide (Listed by Category)
* *API Flow*
  + **FluentValidation:** Enables developers to maintain strongly defined validation rules for objects, while maintaining code self-documentation.
  + **MediatR:** Allows objects to communicate independently (as decoupled components) via a 'mediator'.
  + **SignalR:** Promotes real-time 2-way communication for desktop, mobile, and web apps/assets.
  + **YARP ('Yet Another Reverse Proxy'):** Establishes reverse proxy servers.
* *Authorization*
  + **Keycloak:** An open-source tool for access and identity management.
  + **Microsoft.AspNetCore.Authentication.JwtBearer:** for handling secure JSON Web Token (JWT) authentication for web services and APIs. 
  + **OpenIddict:** Handles OAuth 2.0/OpenID Connect without dictating the user authorization process.
* *Background Tasks*
  + **Hangfire:** Allows for the creation, management, and performance monitoring of background processes, along with some advanced customization features.
  + **Quartz.NET:** An easy to use and easy to learn process scheduling system.
* *Dependency Injection (DI)*
  + **Autofac:** Provides extra dependency management features, multi-interface support, and more flexibility than the built-in DI framework of ASP.NET Core.
  + **Microsoft.Extensions.DependencyInjection:** The DI framework that is built into/bundled with ASP.NET Core.
  + **Scrutor:** Allows for simplification of dependency registration without requiring a new DI container (from the native ASP.NET Core technology).
* *Hyper Text Transfer Protocol (HTTP)*
  + **Polly:** An HTTP request transient fault handling and resilience library.
  + **Refit:** An easy to use alternative to the HttpClient HTTP request class that does not require boilerplate code.
  + **RestSharp:** Another easy to use alternative to HttpClient that can consume REST APIs, but does not offer as much flexibility and support as Refit. 
* *Logging*
  + **NLog:** A free, flexible, and simpler logging solution that supports multiple .NET platforms.
  + **Serilog:** An easy to set up diagnostic logging library that also supports various .NET platforms. Offers structured logging.
