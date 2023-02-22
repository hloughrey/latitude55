<p align="center">
    <img alt="Latitude55" src="https://res.cloudinary.com/latitude55/image/upload/v1634117961/logo-light.svg" width="210" />
</p>

Basic personal website

## Getting started

1. Install local development tools

   ```bash
   npm i
   npm run dev
   ```

2. Point index.html file at correct css file

   In `index.html` replace

   ```
   <link rel="stylesheet" href="./styles.css" />

   with

   <link rel="stylesheet" href="./src/styles.css" />
   ```

## Deployment

Before committing code make sure `index.html` has correct css link.

A commit to master will automatically deploy out to production [here](https://latitude55.dev/).
