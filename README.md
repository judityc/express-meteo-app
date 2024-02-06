#### How to start

open this project in terminal and run:

```bash
npm i
```

and then:

```bash
node app.js
```

#### Available meteo endpoints

`http://localhost:4000/places` -> this gives list of places

`http://localhost:4000/places/vilnius/forecasts/long-term` -> this gives forecasts

#### Usage With fetch

```javascript
fetch("http://localhost:4000/places").then((res) => res.json()).then((data) => setData(data))
```
