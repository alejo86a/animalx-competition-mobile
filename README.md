# competencia-animalx

Ionic (AngularJS + Cordova) mobile app for tracking and displaying results of an "AnimalX" competition (an obstacle/agility-style animal competition, based on the Firebase integration and results UI).

## Tech stack

- Ionic 1 / AngularJS
- Firebase & AngularFire (real-time data)
- Cordova plugins (whitelist, console, statusbar, device, splashscreen, keyboard)
- Gulp + Sass for the build pipeline
- Bower for front-end dependency management

## Running it

```bash
npm install
bower install
ionic serve
```

(Requires the [Ionic CLI](https://ionicframework.com/) installed globally: `npm install -g ionic cordova`.)

## Context

This is a personal/practice project exploring Ionic + Firebase for a live competition results app. There is a companion repository, `competencia-animalx-web`, which is a simpler web-only (browser) version of the same results dashboard built with plain AngularJS and a static JSON file instead of Firebase.
