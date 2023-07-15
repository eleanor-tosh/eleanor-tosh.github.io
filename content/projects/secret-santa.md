---
date: 2023-01-01
title: Secret Santa
subtitle: An app to help you organize your secret santa event.
tags: [react, javascript, UUID, dev academy, TDD, group project]
image: /uploads/secret-santa.png
---
This is part of the final project for my group at Dev Academy. The goal was to make an app that you can co-ordinate participant in a workplace/family/club etc secret santa event.

The admin creates an event which generates a link. This link can then be shared with participants. The participants can then sign-up to be part of the secret santa, generating a UUID so that they have a page to return to. On their page the participants can suggest presents that they might like to receive (or things they do not want) until the secret santa parings are drawn by the admin. Once the admin does the draw, the event changes so that all participant UUID's now display the person who they need to buy a present for along with their wish list.

A large part of this project was also to test as many aspects as the app as possible. As a group we completed 70 passing tests for a final test coverage of 90%.

Much of this project was completed by practicing pair-programming and Agile methodology.&nbsp;

![Sea](/uploads/createevent.png){: width="1843" height="1356"}

With this project their are some changes and extensions that I would like to do beyond the work that my group did. This includes adding a game that involves that participants uploading a photo of their Christmas tree. After the draw, the participants get to guess which tree belongs to each party guest.

The group project used a boilerplate provided by Dev Academy and the following tech:

React, Vite, Redux, Express, Knex, PostgreSQL, SQLite3, React Testing Library, Vitest, nock and supertest.

Visit the fork of the [GitHub repository](https://github.com/eleanor-tosh/secret-santa-project) to view some of the code or visit the final presentation [video](https://www.youtube.com/watch?v=ubjFYWcS_Ew&amp;ab_channel=DevAcademyAotearoa).