## Due to IP bans to our network, this api is currently not available

# OpenAPI - PokeHunter

Made by developers, for fellow developers

This API will allow you to scan a 200m radius without setting up a scanner, you just need to send requests to our service.

We limit requests to 8 requests per minute, this API is for personal usage only.

Calls:
 - To get currently active pokemon picked up by our scanners, use HTTP GET https://open.pokehunter.co/data
 - To initiate a scan, use HTTP POST https://open.pokehunter.co/addloc
 - To get statistics, navigate in a browser to https://open.pokehunter.co/stats
 
All scan results are shared between the open api and the app api.
