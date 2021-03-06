## Usage

Fork or download this repo , move inside and run:

```javascript
npm install
npm start
```
Open development build on [http://localhost:3000/](http://localhost:3000/)

To deploy it:

```javascript
npm run build
npm install -g serve
serve -s build
```
Open production build on [http://localhost:5000/](http://localhost:5000/)

Or copy to a Web Server


## To-Do

- [ ] Add categories checkboxes
- [ ] Add a page with description for each news source
- [ ] Add a logo up top instead of the React Logo
- [ ] ! Maybe change flexbox for CSS Grid


# Auth0 React Login

This sample demonstrates how to add authentication to a React application with Auth0. The sample makes use of Auth0's hosted login page which provides centralized authentication. The sample uses create-react-app.

## Getting Started

If you haven't already done so, [sign up](https://auth0.com) for your free Auth0 account and create a new client in the [dashboard](https://manage.auth0.com). Find the **domain** and **client ID** from the settings area and add the URL for your application to the **Allowed Callback URLs** box. If you are using the server provided by the create-react-app, that URL is `http://localhost:3000/callback`.

Clone the repo or download it from the React quickstart page in Auth0's documentation. Install create-react-app globally and the dependencies for the app.

```bash
npm install -g create-react-app
cd 01-Login
npm install
```

> **Note:** If you are not using create-react-app but are using Babel, you need to add the `stage-0` preset.

## Set the Client ID and Domain

If you download the sample from the quickstart page, it will come pre-populated with the **client ID** and **domain** for your application. If you clone the repo directly from Github, rename the `auth0-variables.js.example` file to `auth0-variables.js` and provide the **client ID** and **domain** there. This file is located in `src/Auth/`.

## Run the Application

The development server that comes with create-react-app can be used to serve the application.

```bash
npm start
```

The application will be served at `http://localhost:3000`.

## Run the Application With Docker

In order to run the example with docker you need to have `docker` installed.

You also need to set the environment variables as explained [previously](#set-the-client-id-and-domain).

Execute in command line `sh exec.sh` to run the Docker in Linux, or `.\exec.ps1` to run the Docker in Windows.

## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a Free Auth0 Account

1. Go to [Auth0](https://auth0.com/signup) and click Sign Up.
2. Use Google, GitHub or Microsoft Account to login.

## Issue Reporting

If you have found a bug or if you have a feature request, please report them at this repository issues section. Please do not report security vulnerabilities on the public GitHub issue tracker. The [Responsible Disclosure Program](https://auth0.com/whitehat) details the procedure for disclosing security issues.

## Author

[Auth0](https://auth0.com)

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE.txt) file for more info.

<!---  LOGO   -->
<div align="center">
<p>
<img src="./logo.png" width="200"/>
</p>


<!---  SHIELDS   -->
<p>
<a href="">
  <img alt="first release" src="https://img.shields.io/badge/release-v1.0-brightgreen.svg" />
</a>
&nbsp
<a href="">
  <img alt="react is dope" src="https://img.shields.io/badge/React-is%20dope%20%E2%AD%90-00D8FF.svg" />
</a>


</p>

🔥 __React News__ is a React App showing news results from more than 70 sources. Uses data from [News API](https://newsapi.org/), it's responsive and super snappy for quick switching thanks to React Virtual DOM 🔥

<p><a href="http://news-app.surge.sh/" class="btn btn-primary btn-md">Launch App</a></p>
</div>

## Features

* ⚒️ __Simple__: Bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app) and using [React](https://facebook.github.io/react/)

* 📊 __Real-time__: Real time data obtained from the leading news resource [News API](https://newsapi.org/)

* 📱 __Responsive__: Made mobile responsive with Flexbox

* 🔥 __Live__: Deployed with [Surge](https://surge.sh/)
## Links:
* https://github.com/alemesa/news-api-react
* https://github.com/auth0-samples/auth0-react-samples