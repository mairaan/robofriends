# Robofriends

A responsive React single-page application that fetches user data asynchronously and renders unique robot profiles. Users can search and filter through the robot cards in real time within a dedicated scrollable container. This project was developed during the Zero To Mastery - Complete Web Developer Bootcamp.

Live demo: [https://mairaan.github.io/robofriends](https://mairaan.github.io/robofriends)

## Features

- Async Data Fetching: Loads user profiles asynchronously from the [JSONPlaceholder](https://jsonplaceholder.typicode.com/users) REST API.
- Dynamic Avatars: Generates unique, customizable robot avatars for each user via [Robohash](https://robohash.org).
- Live Search Filtering: Real-time search functionality that filters robot cards instantly as the user types.
- Scrollable Card Container: Custom scrollable viewport component to manage card overflow while keeping header and search controls fixed.
- Error Boundaries: Implements a React Error Boundary wrapping the card list to catch runtime errors gracefully and display fallback UI without crashing the entire app.
- Responsive Layout: Layout styled for clear visibility across different screen sizes.

---

## Tech stack

- React.js (Functional/Class Components, Lifecycle/Hooks, State & Props)
- JavaScript (ES6+)
- Tachyons(https://tachyons.io/) (CSS toolkit for fast, responsive styling)

* HTML5 & CSS3
* Deployment: GitHub Pages

## Project structure

```
src/
  containers/App.js          Main app: fetch users, search, layout
  components/Card.js         Single robot card
  components/CardList.js     List of cards
  components/SearchBox.js    Name search input
  components/Scroll.js       Scrollable wrapper
  components/ErrorBoundary.js Catches render errors in the card list
  robots.js                  Local sample user data (not used by the live fetch)
```
