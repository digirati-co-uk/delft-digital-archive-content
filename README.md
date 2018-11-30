# Delft - Digital Archive

This repository contains the content for the Digiral Archive site. The project checking out the [deflt-static-site-generator](https://github.com/digirati-co-uk/delft-static-site-generator) project and replaces the demo content folders, before building the static site. 

The site being deployed on Netlify:

[http://delft-digital-archive.netlify.com](http://delft-digital-archive.netlify.com)

## Testing Locally

Please install [yarn](https://yarnpkg.com/lang/en/docs/install/#mac-stable) and [gatsby.js](https://www.gatsbyjs.org/docs/) **globally**. 

To install this project run:

```
yarn local:install
```

To run the project locally

```
yarn local:run
```

Than after the script compiled the site is available at:

[http://127.0.0.1:8000](http://127.0.0.1:8000)

## Content structure

| Folder | Description |
|-|-|
| content | markdown files folder structure preserved |
| collections | IIIF Collection json files|
| exhibitions | exhibition json files |
| objects | IIIF manifests for individual objects |

## Documentation 

**TODO**: Link to the documentation


