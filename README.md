# Movie House (ASP.NET MVC)

A movie website built with ASP.NET MVC 5 and SQL Server. Team project by Rachita Dewanjee and
Jannatul Ferdous.

## Features
- Home page with a movie slideshow and movie listings
- Movie details pages and movie show listings
- Search for movies
- Reviews
- User sign-up, login, logout and profile, with viewing history and user choices
- Admin page for managing movies, including uploading movie images
- About and contact pages

## Tech
C#, ASP.NET MVC 5.2 (.NET Framework 4.5), Razor views, SQL Server (ADO.NET), Bootstrap, jQuery.

Main database tables: `Movies`, `MovieGenre`, `User`, `UserChoice`, `ViewHistory`.

## Run
1. Open `MovieMvc.sln` in Visual Studio.
2. Create a SQL Server database named `MovieHouse` with the tables above.
3. Check the `DBConnection` connection string in `MovieMvc/Web.config` (it uses `localhost` and
   Windows authentication).
4. Press F5 to run the site.
