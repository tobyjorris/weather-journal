# Weather-Journal App Project

This is a demo project that uses the OpenWeatherMap API to allow users to enter a date, location, and their feelings to output a dynamic 'journal entry'. The call to OpenWeatherMap is made from the client side, and uses a chain of promises to get the weather data, convert Kelvin to Fahrenheit, send the data to the server (where it's being held in a mock variable), return the data back from the server, and then use that returned data to update the UI. This is all done in a single thread, mocking a live database/server environment.

## Environment Variables

To correctly install your own environment variable, follow these steps:

- create a `.env` file in the root directory
- create this entry:

``` javascript
weatherAPIKey=<yourkey> 
```

