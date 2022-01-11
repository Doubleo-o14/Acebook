# AceBook

A Facebook clone for a Engineering Project from Makers Academy Bootcamp using Ruby on Rails framework.

We were a team of 6 junior developers and the sole team who had a fully functioning application in [production](https://warm-cliffs-29833.herokuapp.com/) which we were able to demo live on demo day (https://warm-cliffs-29833.herokuapp.com/)

All requirements (see user stories) were built.  
Following an agile process we had:

- daily stand ups
- daily work merged to main
- pair programming
- knowledge sharing daily
- shared goals and vision for the project and the team
- retros
- [Trello board](https://trello.com/b/ynM7GF5J/pizza-acebook-board), for our backlog and daily work
- planning and refinement sessions

## User stories

```
As a user
I want to be able to securely sign up
So that I can start using AceBook

As a user
I want to be able to securely sign in
So that I can access my details and use the application

As a user
I want to securely sign out
So that I can exit the application

As a user
I want to be able to create a text post
So that I can share content on AceBook

As a user
I want to be able to create a post with images
So that I can create more engaging content

As a user
I want to be able to add a comment to a post
So that I can interact with the post author and other users

As a user
I want to be able to like a post
So that I can show my appreciation for the content

As a user
I want to be able to like a comment
So that I can engage with the content

As a user
I want to able to edit my details
So that I can keep my account details up to date

As a user
I want to add photo albums to my profile
So that I can share more image content

As a user
I want to see a small photo next to my username
So that it appears on posts and comments and other interactions within the application

As a user
I want to be able to easily navigate within the application features
So that I can have a more fluid experience

(...)

```

## Quickstart

First, clone this repository. Then:

```bash
> bundle install
> bin/rails db:create
> bin/rails db:migrate

> bundle exec rspec # Run the tests to ensure it works
> bin/rails server # Start the server at localhost:3000
```

## Troubleshooting

If you don't have Node.js installed yet, you might run into this error when running rspec:

```
ExecJS::RuntimeUnavailable:
  Could not find a JavaScript runtime. See https://github.com/rails/execjs for a list of available runtimes.
```

Rails requires a Javascript runtime to work. The easiest way is to install Node by running `brew install node` - and then run `bundle exec rspec` again

[Trello board](https://trello.com/b/ynM7GF5J/pizza-acebook-board)
