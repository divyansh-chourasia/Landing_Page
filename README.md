# Landing page

A one-page site named Divyansh, plus two extra routes. A running copy is at https://landing-page-divyansh.netlify.app/.

The bar sticks to the top. Home, About, and Brands are hash links on `/`: `#home`, `#about`, and `#brands`. Contact goes to `/contact`. Services goes to `/services`. On a narrow screen the word Divyansh drops out of the bar and the links center.

Home opens with the name and the line "Solution to all your problems". The next block is a picture beside a short paragraph about a tech company and children. "Who we are?" is placeholder text. Brands is four icons, Google, Amazon, YouTube, and Instagram, each with its name. The icons are labels only.

Contact is a form with name, email, and message. All three are required. Submit stays on the page. Services is a carousel of two slides, labeled Full Stack and Front-End. It advances every second, loops, and hides the arrows, thumbs, and status.

The footer repeats the name, prints "@all right reserved", and links Follow Us to YouTube, Instagram, and GitHub.

Styles live in `src/styles/` as SCSS. `mediaquery.scss` changes the home sections and the contact card under 820px, and again under 700px.

## Run

From this folder:

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000).

`npm test` starts the test watcher. `npm run build` writes the production build. `npm run eject` copies the build config into the project, and that copy cannot be undone.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app). The references from that README:

- [Running tests](https://facebook.github.io/create-react-app/docs/running-tests)
- [Deployment](https://facebook.github.io/create-react-app/docs/deployment)
- [Getting started](https://facebook.github.io/create-react-app/docs/getting-started)
- [React](https://reactjs.org/)
- [Code splitting](https://facebook.github.io/create-react-app/docs/code-splitting)
- [Analyzing the bundle size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)
- [Making a progressive web app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)
- [Advanced configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)
- [npm run build fails to minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
