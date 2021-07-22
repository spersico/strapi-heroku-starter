# Strapi Starter Blog

Strapi starter for creating a blog with Strapi.

This starter contains the content types and configuration to get you up and running with a simple blog.

## Features

  - 2 Collection types: Article, Category
  - 2 Created articles
  - 2 Created categories
  - Read permissions set to `true` for article and category


## Deploying to Heroku

To deploy the Strapi instance you'll need:

- [An Heroku account](https://signup.heroku.com/) for free
- [A Cloudinary account for saving images](https://cloudinary.com/users/register/free) for free

Once you have created these accounts you can deploy your instance by clicking on this button.

> Tip 💡: You can copy this repo first with the template button, and **then** click on the deploy link, in **your** clone's uploaded readme.md. 

> It will make things easier later, to sync your repo and the copy that Heroku mantains. 

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

*For private repos, take a look at [this](https://devcenter.heroku.com/articles/heroku-button#private-github-repos)*

## Getting started

Clone the repository and install dependencies:

```bash
git clone https://github.com/spersico/strapi-heroku-starter.git strapi
cd strapi
```

Then run the Strapi server:

```bash
npm install
npm run develop
```

The Strapi server is running here => [http://localhost:1337](http://localhost:1337)
