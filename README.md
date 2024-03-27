# Twitter Clone: A Ruby on Rails Showcase

Welcome to my Twitter-inspired web application, crafted using Ruby on Rails! This project, inspired by Michael Hartl's Ruby on Rails Tutorial, showcases key functionalities of a social media platform.

## Technologies Used
- Ruby on Rails
- HTML/CSS
- JavaScript
- SQL

## Project Overview
This Twitter clone aims to replicate the core features of the popular social media platform. Key functionalities include:

- **Posting Tweets:** Users can post their thoughts and updates for their followers to see.
- **Following Users:** Users can follow other users to stay updated on their activities.
- **Dynamic Feed:** The app provides a dynamic feed of tweets from users that the current user follows.

## Key Accomplishments
- Implemented CRUD operations for managing tweets and user relationships.
- Designed an intuitive user interface for seamless navigation and interaction.
- Optimized database interactions to ensure efficient data retrieval and storage.
- Followed industry-standard practices for code organization, testing, and deployment.

Explore the codebase to see how these features were implemented and gain insights into Ruby on Rails development best practices.

## Application Screenshots

I've created an Imgur album containing screenshots showcasing the functionality of the application. Due to hosting costs, the live site is currently offline, but I can easily turn it back on at any time. Please visit the [Imgur album](https://imgur.com/a/fWrr4cw) to view the screenshots.


# Ruby on Rails Sample Application Setup

This is the sample application for the [*Ruby on Rails Tutorial: Learn Web Development with Rails*](https://www.railstutorial.org/) by [Michael Hartl](https://www.michaelhartl.com/).

## License

All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/) is available jointly under the MIT License and the Beerware License. See [LICENSE.md](LICENSE.md) for details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ gem install bundler -v 2.3.14
$ bundle _2.3.14_ config set --local without 'production'
$ bundle _2.3.14_ install
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).
