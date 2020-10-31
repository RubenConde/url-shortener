# Netlify Url Shortener

<p align="center">
  <img src="./assets/netlify-url-shortener.png" alt="Logo" />
</p>

Link shortener that takes advantage of Netlify redirection system. In simple terms, the file
"\_redirects" in the repository gives Netlify the indication to redirect the endings of the
repository url to the desired url.

This results in a fairly fast, free and customised redirector. The latter taking into account that
with Netlify you can:

-  Change the domain at will (as long as you have one).
-  It allows us to have the shortening that we want simply by modifying the file "\_redirects".
-  It's free :D

First of all, to personalize this project to your liking you can create a fork and _voilà_. You will
have an integrated copy of the project in your repositories.

## How ?

This repository use the npm package [netlify-shortener](https://rubn.xyz/ztWYE). It does most of the
work. Since, by means of this one, the addition of new url in the file "\_redirects" and the push to
the repository in Github is made to be able to execute the construction of the project.

For more information about the package [click here](https://rubn.xyz/ztWYE).

## Project setup

To configure this project you can follow the following steps:

1. Clone the project with:

   -  `git clone https://link-to-your-repo.com`

2. Access the project directory and install the dependencies with npm:

   -  `cd path/to/your/repo`

   -  `npm install`

3. Modify the homepage at `package.json`. This allows to **netlify-shortener** create a string with
   the base of the url and the new ID for the redirect.

```json

```
