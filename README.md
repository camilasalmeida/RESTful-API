
# Songs API

This document provides an overview of the routes available in the Songs API. Each route supports a specific CRUD (Create, Read, Update, Delete) operation.

## Routes

| HTTP Method | Endpoint            | CRUD Operation | Route Name | Description                                    |
|-------------|----------------------|----------------|------------|------------------------------------------------|
| GET         | /songs               | Read           | index      | Display a list of all songs.                  |
| GET         | /songs/new           | Read           | new        | Show a form to add a new song.                |
| POST        | /songs               | Create         | create     | Add a new song to the list.                   |
| GET         | /songs/:songId       | Read           | show       | Display a specific song’s details.            |
| GET         | /songs/:songId/edit  | Read           | edit       | Show a form to edit an existing song’s details.|
| PUT         | /songs/:songId       | Update         | update     | Update a specific song’s details.             |
| DELETE      | /songs/:songId       | Delete         | delete     | Delete a specific song from the list.         |
