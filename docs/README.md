# DotNetAuth

DotNetAuth is a simple and straightforward library designed to streamline authentication processes in .NET applications. 

**Note:** DotNetAuth.Client is specifically designed to implement the Authorization Code Flow of OAuth2.0 within .NET web applications. 


## Features

- Designed for extensibility and customization
- Full control over the process
- Allows developers to define specific OAuth callback endpoints
- Ability to customize the consent screen during both initial setup and/or generating authorization
- Out-of-the-box configurations for popular providers like Google, Facebook, GitHub and Microsoft
- Users can extend the library by defining custom authorization servers, allowing for flexibility and adaptability
- Alongside authentication, it also facilitates user profile retrieval from various providers, streamlining user data management

### DotNetAuth.Client vs DotNetAuth.Identity
DotNetAuth is structured in two layers: DotNetAuth.Client for authentication and DotNetAuth.Identity for user data extraction
- **DotNetAuth.Client**: Specializes in the OAuth2.0 Authorization Code Flow for .NET web applications, simplifying third-party authentication and token management.

- **DotNetAuth.Identity**: Focuses on extracting user information from various authorization servers, ensuring consistent data retrieval despite differing server APIs.
