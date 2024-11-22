## Back End NovelSys
Give a high-level overview of the project purpose
- Questions to consider:
    - What are the users?
      - The users are institutions to manage digital learning, educators to create and present online learning materials
    - What job does it form for them?
      - It is a web-based learning management system or LMS helps make digital education easier
    - What inspired you to make it?
      - I wanted to still aim something that would allow me to learn ASP.NET Core Web Api and C#
    - What features are the most important?
      - User Management and Course Management

## Technologies
* ASP.NET Core
* C# Language
* Mapster
* CQRD
* Mediatr

## Competencies
### JF 3.6
Can implement a RESTful API
* The project itself is a backend consisting a RESTful API which is created with ASP.NET Core Web Api
* The controllers are the API Endpoints that correspond to a specific function HTTP Methods and we use DI & Services to implement service classes to interact with the database

### JF 3.7
Can implement authentication and authorization to an API.
* To ensure there is an auth where we integrate if they are a student or teacher we use JWT and Identity and Auth built within ASP.NET Core
* The routes are protected with authorization to restrict access to the methods

### JF 3.8
Can encrypt sensitive data via hashing
* Used a hashing algorithm provided from packages such as the PasswordHasher and created an example out of it
