# Hosting an SPA in a sub-path of an ASP.NET Core application

This repos contains a quick demo of the modifications that should be applied to the default *ASP.NET with Angular* startup template,
in order to move the Angular app so it can only be accessed from a sub path, instead of the applications root. In this example, 
the angular app will be accessible at https://localhost:44324/spa instead of https://44324. To complete the demo, I've added a Razor Page 
to act as a home page for the app's root URL.

While this project uses ASP.NET 5, I expect the modifications to be the same for ASP.NET Core 2.1 or above.

## Where to find the changes
The first commit of this repo contains the unmodified ASP.NET 5 startup template.

The second commit contains all the modifications required to move the SPA in a subpath.

And so, you can follow the changes [in this diff](https://github.com/Shtong/aspnet-spa-subfolder/commit/3fc7d72870f5b00bd98be7b4ae5ddb7a63492a8b) for a recap of what should be done.
