# 2PlaylistApi

## Code Repository
**Code:** [GitHub - Playlist API](https://github.com/melisademirbas/2PlaylistApi)

## Live Website

** Deployment : https://playlistapi-beril.azurewebsites.net/swagger/index.html  (hocam deneme yaparken çok fazla kendi adımı kullandım en son isim bulmaya çalışırken ablamın adını denedim o yüzden beril yazıyor haberiniz olsun , teşekkür ederim)


## Design
- Developed with **ASP.NET Core Web API**
- Uses **Entity Framework Core In-Memory Database**
- Configured Swagger to open directly on the root URL 
- Contains controller-based RESTful endpoints for playlists and songs.


## 
- The API runs locally (not hosted online).
- Data is temporary and resets on restart.
- No JavaScript frontend — backend only.


## Issues Encountered
- Swagger initially opened only on `/swagger/index.html` → fixed with `RoutePrefix = string.Empty`.
- “Address already in use” error fixed using `lsof -i :5291` and `kill -9 PID`.
- Adjusted HTTPS redirection for localhost environment.


## Technologies Used
- .NET 8
- ASP.NET Core Web API
- Entity Framework Core (InMemory)
- Swagger / OpenAPI
