## Google-Lite Clone with Tailwind CSS & NEXT.JS! (Responsive, SSR React, Pagination) -- Tutorial with Sonny Sangha

https://youtu.be/24xpTmaPOdY

## API and Context Keys are needed:

API Key, allows to use Google API - https://developers.google.com/custom-search/v1/using_rest <br />
Context Key - https://cse.google.com/cse/create/new

## EITHER

Deploy using https://vercel.com/ and use environment variables to encrypt the API and Context keys https://vercel.com/docs/environment-variables#environments

## OR
-Edit the search.js file: <br />
Comment in the import at top <br />
process.env.API_KEY -> API_KEY <br />
process.env.CONTEXT_KEY -> CONTEXT_KEY <br />

-Create a keys.js file with information below: <br />
export const API_KEY = ''; <br />
export const CONTEXT_KEY = ''; <br />
