# devHead

## Description
This developer-focused social-media application allows the user to manage a list of posts. They can create new post entries, read their posts, update their pre-existing posts, and delete their posts, read other people's posts, and view a list of other users.

## Planning Story
Reviewed project prompts and narrowed it down to a social media site, blog, and picture site. After brainstorming target audiences decided to focus on building a platform for software developers where they can post their projects, questions, and frustrations. At this point the project is a social media site with plans to implement more blog-like features and ability to upload pictures at a later date.

## Important Links
- Client Repo: [view here](https://github.com/H3DRA/devhead-client)
- Deployed Client: [view here](https://h3dra.github.io/devhead-client/#/)
- Deployed API: [view here](https://ancient-wildwood-16167.herokuapp.com)

## User Stories

- As a new user I want to sign up with an email and password
- As a new user I want to be signed in after signing up
- As an existing user I want to login with email and password
- As a user I want to be able to change my password when logged in
- As a user I want to be able to sign out when signed in
- As a user I want to be able to add a post to my wall
- As a user I want to be able to update a post I own when logged in
- As a user I want to be able to delete a post I own when logged in
- As a user I want to view a list of other users and links to their walls
- As a user I want to be able to upvote or downvote posts
- As a user I want to view a main wall of posts that can be filtered by category

## Technologies Used
- ReactJS
- HTML/CSS
- Bootstrap

## ERD

![devheadERD](https://media.git.generalassemb.ly/user/35033/files/e1a56380-b173-11eb-82e3-56e54747e6f0)

## Problem-solving process and strategy
- Utlized mob programming
- Would troubleshoot problems together through discussion, trial & error, and research via Google, stackoverflow, etc.
- If the team couldn't find the answer, would seek help from instructors by submitting an issue request

## Unsolved Problems
- Add more dynamic messaging on successful CRUD actions
- Make client more mobile-friendly
- Add ability to upload pictures
- Add blog feature

## Catalog of Routes
#### Auth
|Verb   | URI Pattern   |
|---|---|
| POST  | /sign-up  |
| POST  | /sign-in  |
| DELETE  | /sign-out  |
| PATCH  | /change-password  |

#### User
|Verb   | URI Pattern   |
|---|---|
| GET  | /users  |

#### Posts
|Verb   | URI Pattern   |
|---|---|
| POST  | /posts  |
| GET  | /posts  |
| GET  | /posts/all  |
| DELETE  | /posts/:id  |
| PATCH  | /posts/:id  |
