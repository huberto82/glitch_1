# Manage Node.js projects and npm packages using package.json

## Part 1 of Free Code Camp Backend Challenges

A timestamp microservice similar to [this](https://timestamp-ms.herokuapp.com/).
User story:
- I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016)
- If it does, it returns both the Unix timestamp and the natural language form of that date.
- If it does not contain a date or Unix timestamp, it returns null for those properties.
## Example usage:
```js
https://timestamp-ms.herokuapp.com/December%2015,%202015<br>
https://timestamp-ms.herokuapp.com/1450137600
```
## Example output:
```js
{ "unix": 1450137600, "natural": "December 15, 2015" }
```
Try this at [Glitch](https://glitch-1.glitch.me/)

Made by (ee$
