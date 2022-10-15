# writtenthoughts

## Public

Navigation

- About
- Sign in
- Sign up

Landing page

- CTA
- Features
- Footer

Login page

- Login form

Sign up page

- Sign up form

## User

Navigation

- profile
  - Sign out
  - File save journals
  - Account
    - Change password
    - Delete account
- Previous Journals

  - List of all the previous ones

Index

- writing space
- delete button
  - Are you sure you want to delete?

Style

- Minimalistic/Simple
- Typography

  - Roboto, Sans-serif
  - Merriweather, Serif
  - p: 16|17px

- Colors

  - #000000 black
  - #363946 Onyx
  - #9CD08F Granny Smith Apple (Accent)
  - #696773 Dim Gray

- Icon-pack

  - [ionicons](https://ionic.io/ionicons)

- Whitespace
  - Multiples of 16px

---

## Backend

Database

- MongoDB
  - Mongoose

Templating engine

- ejs

Server

- Express

Routes

- get('/')
- post('/delete-entry')
- post('/edit') ? you gotta autosave though TODO: figure out how to save
- post('/new')

Authentication

- csurf
- bcrypt
- nodemailer
- express-session

File download

- fs

TODO: how to save written entries on db <br>
TODO: how to encrypt entries on db

## Deploy

Heroku

- Github Pro
