# ASP.NET Core Docker Container Sample for DigitalOcean App Platform

This sample demonstrates how to run a Dockerized ASP.NET Core application on DigitalOcean App Platform.  Since App Platform doesn't yet support dotnet core, this sample shows how to accomplish this using Dockerfile.

This sample has been adapted from official dotnet docker sample - https://github.com/dotnet/dotnet-docker/tree/master/samples/aspnetapp

# To run this sample in DigitalOcean App Platform
Fork this repo, and then simply point App Platform to your new repo. App Platform will automatically detect that this is a Dockerfile build and will do the rest.
