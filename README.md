# API Gateway using Ocelot

A simple API gateway made with Ocelot 🐆🏰

There are two APIs, API1 and API2 and there is the API Gateway application, which is an ASP.Net project that uses the Ocelot dependency.

Inside the ocelot.json file there are configurations that basically says:

- "When API-Gateway application receives a request in /API1/motd reach API1 at localhost:5068/api/v1/hello endpoint, but only if the HTTP method is GET"

- "When API-Gateway application receives a request in /API2/motd reach API2 at localhost:5232/api/v1/hello endpoint, but only if the HTTP method is GET"
