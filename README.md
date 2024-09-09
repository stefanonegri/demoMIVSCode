# demoMIVSCode
demo of MI VS Code capabilities (AI oriented)
## Intro
1. Open VSCode and go to the Wecome page ("Open MI Welcome")
2. Show the samples projects
   - eventually create a project from the sample and show the main components
## Create an AI project
1. Create an empty project
2. Show the structure and artifact folders
3. Open AI panel
4. Edit one of the following:
### Simple header based routing
1. edit the command: " I want to create an API that will route based on a header value" and click "Generate"
2. Show the API, the sequences and the explanation
3. Modify the sequence Route1Sequence: "Rename Route1Sequence with CallPineValley"
4. Modify the sequence CallPineValley: "Modify the sequence CallPineValley adding a call mediaor to an endpoint named PineValleyEP"
### Create a weather service in minutes
see picture 1 (to be attached)
1. Create a new project
2. Open copilot and"
   - import the OAS: GeoLocationOAS.yaml and OpenWeatherOAS.yaml
   - edit the following: "Generate a service for fetching weather from a city name, refer to the attached OpenAPI Specification for more details about the geolocation endpoint and weather endpoint"
   - show the created assets
3. (optional) add caching with Redis: "please add Redis caching to store and manage weather data"
4. Add Data mapping
   - add a data mapping mediator after the weather fetching call (before the redis set call)
   - import input schema and output schema
   - (optional) use the magic button to map
   - map manually
     - modify the pressure with "dmUtils.numberToString(input.main.pressure)"

