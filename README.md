# rails-auth-template

Clone this project to get a quick start with Rails authentication.

I made this for myself because I have gone through [Greg Buckner's helpful instructions](https://gist.github.com/thebucknerlife/10090014) way too many times. Those are the directions I used to create this project.

Mr. Buckner provides a [boilerplate](https://github.com/thebucknerlife/auth_boilerplate) too, but I like to do things myself. His boilerplate is more well documented than this one, so check it out.

This project uses Rails 5.

# Routes

The following routes are available:

* `GET /login`
* `POST /login`
* `GET /logout`
* `GET /register`
* `POST /users`

# Helper Methods

These two methods are available:

* `current_user`
* `authorize` (use with `before_action` in controller)
