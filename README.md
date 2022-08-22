# MakingMemories-Server

### What is this app?
An app for users to log their favorite memories as well as view the memories of others. Inspired by StoryWorth in virtual form.

### Technologies Utilized
- MERN STACK
  - MongoDB
  - Express
  - React
  - Node JS

### ERD
![](Images/erd.png)

### ROUTE TABLES

##### User Routes

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-in`             | `users#signin`    |
| PATCH  | `/change-password/`    | `users#changepw`  |
| DELETE | `/sign-out/`           | `users#signout`   |

#####  Memory Routes

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| GET    | `/view-all-memories` | `memories#view-all` |
| GET    | `/view-memory`        | `memories#view`    |
| POST   | `/create-memory`      | `memories#create`  |
| PATCH  | `/edit-memory/`       | `memories#edit`    |
| DELETE | `/delete-memory/`     | `memories#delete`  |

##### Comments Routes

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/create-comment`      | `comments#create` |
| PATCH  | `/edit-comment/`       | `comments#edit`   |
| DELETE | `/delete-comment/`     | `comments#delete` |

#### Making Memories Client Repo
https://github.com/arianamichele/MakingMemories-Client