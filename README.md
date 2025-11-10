# Home Exercise
This is a backend exercise using Python to integrate with two API calls. The goal is to build a small, robust terminal application that fetches and aggregates paginated weather data while handling auth, retries, and edge cases.

## High-level description
You are given an HTTP API endpoint:
`POST https://gw4favkunc.execute-api.il-central-1.amazonaws.com/auth`
which returns a short-lived token and metadata about the dataset you must process.
follow the instructions in the response to fetch data.

Your task is to write a Python program (a single script or small module) that:
- Calls /auth to obtain:
- An access token (valid for ~60 seconds),
- A request_id (identifying the dataset/city),
- The data_url
- Uses this information to reliably fetch all pages from data API.
- Computes the average temperature for that city.
- Prints the final result in a clear form (up to 3 digits after the comma), e.g.:
```
City: venice
Average temperature: 20.175
```

## Hints / Tips
- You can feel free to use any AI to generate the solution
- The data API is built in way to respond with error sometime - you should handle that

## Getting Started
- Clone or download the repository - do not fork!
- You can edit any file in `./src`.
- When ready submit your result in one of the following methods:
  - Create a new repository under your own account and send us link
  - Email us a zip file with the source code

## Requirements
- The code must compile with no errors.
- The resoponse should contain both the city name and the avarage temperate

## Questions?

Don't hestitate to reach out to us if you have any q's :)
