# csharp-todo-api
Api developed following the tutorial: https://learn.microsoft.comen-us/aspnet/core/tutorials/first-web-api

## Goal  
Learn the basics of a minimal API with ASP .NET 7.0 and reinforce C# skills. Plus basic usage of Visual Studio Community 2022 IDE

### Functionalities
CRUD of Todos (just another one of billions of apps like this, and as always, great for introducing yourself to a new web technology)  
- POST: Add a new Todo  
- PUT: Update a Todo  
- DELETE: Delete a Todo  
- GET: Obtain all todos (Includes endpoints for filtering by completition and id)
- In Memory Database: All Todos are stored in-memory, hence, when server is restarted, all data is lost.

### Endpoints
- POST /todoItems

- GET /todoItems

- DELETE /todoItems/:id

- PUT /todoItems/:id

- GET /todoItems/complete

- GET /todoItems/:id
