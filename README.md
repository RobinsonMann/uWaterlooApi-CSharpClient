# uWaterloo API - C# Client
---

###About
A client library created in C# that allows users to quickly jump in and start using uWaterloo's OpenData API. 

###Where do I get my API key?
https://api.uwaterloo.ca/

###How do I call the correct endpoint?
Simply create a `UWaterlooApi` object and call the methods corresponding to the endpoint paths outlined in https://github.com/uWaterloo/api-documentation

####Examples

```C#
UWaterlooApi myUw = new UWaterlooApi("YOUR-API-KEY");
test.foodservices.menu(); 
```

### Acknowledgments
**University Of Waterloo**
**Jonathan Keith** -- Creator of http://json2csharp.com/
