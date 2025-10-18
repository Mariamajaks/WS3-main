# WS3 Movies App

A Node.js & Express app that fetches "Star Wars" movie data from the OMDb API and displays it in a table with posters.

---

## Features

* Fetches movie data from OMDb API
* Logs results in the console
* Shows results in the browser as an HTML table
* Works locally and deployed on Render

---

## Running Locally

1. Open terminal or PowerShell in the WS3 folder.

2. Install dependencies:

```bash
npm install
```

3. Add your OMDb API key in `movies.js`:

```js
const API_KEY = "YOUR_API_KEY";
```

4. Start the server:

```bash
npm start
```

5. Open your browser and go to:

```
http://localhost:5000/
```

* Table shows: Title (Year), IMDb ID, Poster
* Console logs movie titles

---

## Live App

* [https://ws3-main.onrender.com/](https://ws3-main.onrender.com/)
* Uses `process.env.PORT` for Render deployment

---



* [ ] Console prints movie titles
* [ ] Browser displays table with Title/Year, IMDb ID, Poster
* [ ] `npm start` works locally
* [ ] GitHub repo includes `movies.js`, `package.json`, `README.md`
* [ ] Render app is live
* [ ] Optional screenshots added
