# NWS Weather App

One of the better places to check the weather is by going on the National Weather Service's (NWS) website.  This avoids clickbait articles from The Weather Channel and other weather websites.  The NWS site is antiquated and not fun to look at, so lets make it more modern.

## Project Goals 
### Software Development:
- Use the NWS API to get current weather conditions (https://www.weather.gov/documentation/services-web-api)
- Find a third party API that can determine locations via text or zip codes.  It will need to convert the location to coordinates to use with the NWS API
- Ideally, this should act as a single page app and not "reload" when a user switches locations.
- Stretch Goal:  Utilizing MapBox API, the user can switch locations by clicking on the map.  This would need to be limited to the USA if using the NWS API.

### GUI Elements:
- List current weather with an icon displaying the condition
- List the 7 day forcasted weather with condition icons
-  Need to determine all possible weather conditions (Clear, Hazy, Partly Cloudy, etc.) and find free icons for them.
- If provided by the API provide the textual 7 day forcast.
- Have a map with the location
- Stretch Goal:  Have a map with the current radar

### Potential Backend Expansion:
- Code with this stretch goal in mind!
- Add hourly weather changes for selected locations to a database.  Have the ability to do CRUB
- Super stretch goal:  Use the data and implement a D3 graph.