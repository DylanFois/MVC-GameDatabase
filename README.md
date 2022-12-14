# MVC-GameDatabase

## Description
A web app designed to host a database of games, currently has game name and description, but more will be added. Also uses login and registration to ensure only authorised users can add, edit or delete games.

Uses MVC design pattern with ASP.NET Core

## File Structure
```bash
# [Main Directory](./Game Database App/Game Database App)
./Game Database App/Game Database App/
├── Areas 
├── Controllers 
├── Data 
├── Models 
├── Properties 
├── Views
├── bin
├── obj
├── wwwroot
├── Program.cs

./Game Database App/Game Database App/Models
├── ErrorViewModel.cs
├── Game.cs # Game model

./Game Database App/Game Database App/Views
├── Games # Contains main index and search

./Game Database App/Game Database App/Controllers
├── GamesController.cs # Controls game page
├── HomeController.cs # Controls main homepage
```

[`[back-to-top]`](#table-of-contents)
