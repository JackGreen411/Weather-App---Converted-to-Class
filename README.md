# Weather-App - Converted to a Class Object

Bundled all the previous weather app code from lessons #99 - #109, into a class object.

The class constructor properties were the base weather API call uri, apikey & city API uri.

The inital weather invoked function has one parameter, the city. This is passed through by the input field and concatinated together with the base weather URI, it then outputs the very first occurance of data through and returns it via data[0].

The second invoked function passes the weather data through as a parameter, specifically the city ID. This is needed to fetch back the weather information with the search by city id URI.

The last invoked function, is updateUI, this then outputs the relevant data fetched from the fetch api, into the appropriate HTML elements.

A simple check of night/day within the data, allows me to use an SVG to present that aspect of weather on the front end.

Localstorage is also used to store the users last inputted city search, immediately invoking the function upon page load from the user.
