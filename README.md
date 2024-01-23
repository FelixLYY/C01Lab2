# C01Lab2
## Table of Content
- [Objective](#objective)
- [Requirement](#requirement)
- [How to run](#how-to-run)
- [Features](#features)
### Objective
- Understand general backend development basics
- Get familiar with NoSQL
- Build a basic backend based on <a href=https://github.com/ArmandoRJr/c01w24lab2> Create Your first MERN App </a>
### Requirement 
- Please check <a href=https://github.com/ArmandoRJr/c01w24lab2#pre> here </a>
### How to run
- After cloning the repository, navigate to `backend` Directory. Open terminal in the directory and run the following command
```shell
npm run dev
```
- Run MongoDB as well by 
```shell
"C:\Program Files\MongoDB\Server\7.0\bin\mongod.exe" --dbpath=.\data\db
```
### Features
- This application served to be a note keeper and has the following additional features other than features implemented <a href=https://github.com/ArmandoRJr/c01w24lab2#pre> here </a> 
    1. Get all notes belonging to the user with `GET` request - `/getAllNotes`
    2. Delete note belonging to the user with `DELETE` request - `/deleteNote/:noteId`
    3. Update note belonging to the user with `PATCH` request - `/editNote/:noteId`
