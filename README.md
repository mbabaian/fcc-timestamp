# fcc-timestamp
## From [freeCodeCamp's Basejump: Timestamp Microservice](https://www.freecodecamp.org/challenges/timestamp-microservice)

### User Stories
- I can pass a string as a parameter, and it will check to see whether that string contains either a unix timestamp or a natural language date (example: January 1, 2016).

- If it does, it returns both the Unix timestamp and the natural language form of that date.

- If it does not contain a date or Unix timestamp, it returns null for those properties.

### Usage
Input
```
https://versed-knee.glitch.me/1450137600
https://versed-knee.glitch.me/December%2015,%202015
```

Output
```
{ "unix": "1450137600", "natural": "December 15, 2015" }
```

[Live version](https://versed-knee.glitch.me)
