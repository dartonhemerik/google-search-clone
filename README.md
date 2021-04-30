## Google-Lite Clone with Tailwind CSS & NEXT.JS! (Responsive, SSR React, Pagination) -- Tutorial with Sonny Sangha

https://youtu.be/24xpTmaPOdY

## API and Context Keys are needed.

API Key, allows to use Google API - https://developers.google.com/custom-search/v1/using_rest
Context Key - https://cse.google.com/cse/create/new

## EITHER

deploy using https://vercel.com/ and use environment variables to encrypt the API and Context keys https://vercel.com/docs/environment-variables#environments

## OR

edit the search.js file:
process.env.API_KEY -> API_KEY
process.env.CONTEXT_KEY -> CONTEXT_KEY

AND create a keys.js file with information below:
export const API_KEY = '';
export const CONTEXT_KEY = '';
