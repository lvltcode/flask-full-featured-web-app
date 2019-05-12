Flask Full-Featured Web App
===
`May 2019` `lvltcode` `flaskblog`

View online at: https://flask-full-features-blog.herokuapp.com/

## Ideas (simple one)
Build a full-features blog that User can register, sign in, customize their profile (pictures, name, email, change password), post blog with pictures, text, date created etc.

I intended to use Python/Flask/HTML/CSS/SQLite first, then later connect to JS/ReactJS if need more challenges to add more decorators, interactive effects.

## User Stories
- [x] User can use their email and set a new account via Form Input
Demo:
![image alt](https://i.imgur.com/x9vM3R2.png)
- [x] Check if name or email that used when register
![image alt](https://i.imgur.com/zuA5Zg6.png)
- [x] Authentication for the register
- [x] Validate the form’s fields
Demo:
![image alt](https://i.imgur.com/1BhANe9.png)
- [x] User know when they successfully signed in
Demo:
![image alt](https://i.imgur.com/JMRofxv.png)
- [x] Check if user input wrong password or email
![image alt](https://i.imgur.com/6J5tNkn.png)
- [x] User can log in and log out and see different button after log in or log out
- [x] User have to log in to see some page like account page to change their info
![image alt](https://i.imgur.com/bLMzpzt.png)
- [x] User can update their profile, customize their avatar or change some information
- [ ] User can resize their avatar to suit with the page.
- [x] User can post, edit and delete their post
- [x] User can not update or delete other post if they are a normal user.
- [x] User can see all the post or page of posts (pagination)
- [ ] User maybe forgot their password, so they need to reset their password successfully.
- [ ] The reset email send to user's email and they can access to change new password
- [x] When client's side throw a error page, user can see the 404 page or some page that they can understand what happened.
- [x] The latest post will appear on the first page
- [x] Click on the username, get posts from that user


## Language, library tools I intend to use:
* `HTMl/CSS/Bootstrap/Font Awesome`.
* `Flask-SQLAlchemy, Flask-migrates, Blueprints, Flask-wtf, flask-bscrypt`
* `Heroku`
* `Python`
* `JS/React.js` (*not sure to implement these*)
* `SQL/Postgres`
