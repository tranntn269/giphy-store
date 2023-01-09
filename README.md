# Giphy Store

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.3.

## Development server

### Technology

**Angular** for client, **JSON server** for mock api

Run `npm install` to install dependencies.
Run `npm start` for a dev server. It will run those commands:

1. "start:dev": "ng serve" to start client server
2. "prestart:api": "ts-node server/createDb.ts" to create db.json file and init database
3. "start:api": "ts-node server/server.ts" to run json server

Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Introduction

## ![A screenshot of the Giphy store]

![homepage__collection](https://user-images.githubusercontent.com/57772425/211250416-3e929a70-03d4-42be-a50e-2fcc82faa32a.PNG)

## Features

- See a list of trending GIFs in masonry layout
- Search for the GIFs by gifname, username, tag name
- Sort the results by uploaded time (asc/desc)
- See new GIFs when scrolling to the bottom
- Expand a GIF and see the details of it
- Favorite GIFs
- Retrieve their favorite GIFs
- Upload GIF
- Retrieve their uploaded GIFs

**User experience**

- Responsive in mobile, tablet, laptop(1280px), desktop(1920px)
- Scrolling, searching, fetching:
  - Generate random background when hover in a GIF
  - Show loading spinner when scrolling to bottom
  - Show loading spinner when searching result
  - Display a placeholder in mosaic layout when GIFs are still loading
  - Display empty page for no results

**Animation**

- Header scroll up and down
- Hover in heart icon to favorite GIF

**Unit Test**

- Login function in AuthService

---

## Diagram

![Diagram of the Giphy store]

![diagram](https://user-images.githubusercontent.com/57772425/211250477-1a451f18-10f6-49db-9795-7d664fafa450.jpg)

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Demo video

https://user-images.githubusercontent.com/57772425/211252497-3fcfbfee-d6b9-4c1b-a7d7-7f6e6ddd86ba.mp4


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
