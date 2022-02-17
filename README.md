# Brewery Tours with Authorisation

Your job, as a team, is to improve upon the [ReactJS](https://reactjs.org/) brewery tours exercise from earlier in the course (https://github.com/boolean-uk/boolean-uk-react-brewery-tours). There, the second extra challenge asked you to add a submitted bookings page, where all submitted bookings get saved to a database. Your task is to create the bookings database and add authentication, so that customers can only see _their_ bookings, but site admins can view _everything_. As per that extra challenge, the bookings page should replace the list and filters sections and the bookings data can be grouped by brewery.

![Brewery Tours example](./images/breweries-tour-react.gif)

(although, you may wish to amend that user interface)

## Learning Objectives

- Use agile ceremonies including stand-ups, retrospectives, sprint planning and stakeholder demos to develop software as a team
- Design and build a full-stack architecture that has a frontend application consuming data from a backend API
- Use a source code management tool to integrate work in one codebase with multiple contributors

## Project Requirements

- Must contain a well thought out entity relationship diagram and application design
- Must be a full-stack application with a [ReactJS](https://reactjs.org/) frontend consuming data from an [ElephantSQL](https://www.elephantsql.com/) database-backend that is exposed to the client frontend via an API built using [Express](https://expressjs.com/) and [Prisma](https://www.prisma.io/)
- Must not expose sensitive information (authentication)
- Must not contain hard coded URL’s (routes are fine, `http://localhost` is not)
- Commit messages must be consistent and meaningful
    1. Keep them in present tense (✅ `add, remove, update` ❌ `added, removed, updated`)
    2. Keep them short and descriptive ( `change hashing library`, `add password to user model` )
    3. [Here are some good guidelines](https://reflectoring.io/meaningful-commit-messages/) but don’t go overboard, the above two bullet points are enough

## Setup

This is _scaffold free_ project, so setup is down to you! However, since you are going to use a single repository for both client and server, it is recommended that your repository includes two top-level directories that separates the two, e.g. _./client/_ and -./server/_.