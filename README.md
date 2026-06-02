# PhysioSim Systems Website

This repository contains the source code for a simple two‑page static website.  It consolidates the
existing marketing site (`index.html`) with the proof of concept
report into a single project.  The pages are linked via the navigation bar.

## Structure

```
website/
├── index.html   # main marketing site
├── poc.html     # proof of concept report
├── README.md    # this file
```

To preview the site locally, open `index.html` in a web browser.  The “Proof of
Concept” link in the navigation bar takes you to `poc.html`.

## Netlify deployment

This project is a static site and can be deployed directly on [Netlify](https://www.netlify.com/) or
any other static hosting provider.  There is no build step required.  When
connecting to Netlify, select the `website` directory as the site root so that
`index.html` becomes the default page and `poc.html` is served alongside it.

## Customizations

- The pitch deck link has been removed from the founder section of the home
  page.
- Darker grey text on the proof of concept page has been lightened for better
  readability.
- A new “Proof of Concept” link has been added to the top navigation.