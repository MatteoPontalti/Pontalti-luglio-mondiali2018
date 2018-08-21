# Pontalti-luglio-mondiali2018

### To install all dependecies:

```
npm install
```

### To run the server:

```
node app.js
```

### Add team

POST raw json, example:

```
{"Name": "Brasile", "matches": [{"opponent": "Argentina", "outcome": "W" }]}
```

### Add Match

PUT raw json, example:

```
{"opponent": "Inghilterra", "outcome": "L" }
```