# React Router Demo w/Contacts

## Getting Started

Run `npm install` to install all dependencies. This already includes `react-router-dom`.

You will need to create a `db.json` file in the root of the project. This will allow `json-server` to serve this data as a fake back-end server with full CRUD capabilities.

Paste [this data](https://gist.github.com/manavm1990/b910fcf25e0db4b31ea1759dac80793b) into `db.json`.

Then, you'll do: `npm run json-server` to start the fake RESTful API server. It's been set with a `delay` of `1000`ms, so you can see the loading state of the app.

Then, you'll do: `npm start` to start the React app. Make sure to do that from a separate terminal window.
