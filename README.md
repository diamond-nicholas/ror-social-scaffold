# Scaffold for social media app with Ruby on Rails
# Scaffold for social media app with Ruby on Rails

This repo presents a social media app called “Stay in touch”.

As a guest user:

- I'm able to create account/log in.

- I can see only “Sign in” and “Sign out” page.

As a logged-in user:

- I'm able to see all users list.

- I'm able to see selected user page with their user name and all posts written by them (the most recent posts on the top).

- I'm able to send a friendship invitation.

- I can see a button “Invite to friendship” next to the name of user who is not my friend yet - on both users’ list and single user page.

- I'm able to see pending friendship invitations sent to me from other users.

- I'm able to accept or reject friendships invitation.

- I'm able to create new posts (text only).

- I'm able to like/dislike posts (but I can like single post only once).

- I'm able to add comments to posts.

- I'm able to see “Timeline” page with posts (with number of likes and comments) written by me and all my friends (the most recent posts on the top).

- Timeline is the root page of the app.

- Confirmed friendships creates 2 rows in the query.

## Built With

- Ruby v2.7.2
- Ruby on Rails v6.1.3.1

## Live Demo

[Stay In Touch](https://safe-beyond-81247.herokuapp.com/)

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

Ruby: 2.6.3
Rails: 5.2.3
Postgres: >=9.5

### Setup

Instal gems with:

```
bundle install
```

Setup database with:

```
   rails db:create
   rails db:migrate
```

### Github Actions

To make sure the linters' checks using Github Actions work properly, you should follow the next steps:

1. On your recently forked repo, enable the GitHub Actions in the Actions tab.
2. Create the `feature/branch` and push.
3. Start working on your milestone as usual.
4. Open a PR from the `feature/branch` when your work is done.

### Usage

Start server with:

```
    rails server
```

Open `http://localhost:3000/` in your browser.

### Run tests

```
    rspec --format documentation
```

> Tests will be added by Microverse students. There are no tests for initial features in order to make sure that students write all tests from scratch.

### Deployment

This project was deployed to heroku and the link is provided below
(https://safe-beyond-81247.herokuapp.com/)

## Authors

**Franklin benjamin crisostomo de la rosa**

- GitHub: [@franklinben23](https://github.com/franklinben23)
- Twitter: [@frankli2302](https://twitter.com/Frankli2302)
- LinkedIn: [Franklin Benjamin](https://www.linkedin.com/in/franklinbenjamin/)

**Nicholas Diamond**

- GitHub: [@Diamond](https://github.com/diamond-nicholas)
- LinkedIn: [Diamond Nicholas](https://www.linkedin.com/in/diamond-nicholas/)
- Twitter: [@diamondnich](https://twitter.com/diamondnich)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

TBA

## 📝 License

TBA
