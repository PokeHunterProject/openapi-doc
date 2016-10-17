# OpenAPI - PokeHunter

This API will allow you to access data from our scans, the whole API is limited to 16 requests per minute.

Calls:
 - To get current scanned pokemon, HTTP GET https://open.pokehunter.co/data?swLat=(value)&swLng=(value)&neLat=(value)&neLng=(value)
 - To get our spawn data, HTTP GET https://open.pokehunter.co/spawns?swLat=(value)&swLng=(value)&neLat=(value)&neLng=(value)

Stats:
 - To get scanner statistics, navigate to https://open.pokehunter.co/stats
 
If an api update for Pokemon Go occurs, the scanned pokemon call will stop working.
