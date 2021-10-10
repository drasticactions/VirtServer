# VirtServer

A simple wrapper for LibVirt with an ASP.NET Core Server on .NET 6.

This is intended to either be run on the server running LibVirt, or on one that can handle all of the connection types it has to offer (So, not Windows.) It's a way to access LibVirt's domains on different devices without having to bind the whole library.