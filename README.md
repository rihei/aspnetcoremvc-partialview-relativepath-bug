# aspnetcoremvc-partialview-relativepath-bug
When a partial view is referenced in ASP.NET Core MVC 2.0.1 by a relative path (../) and without the .cshtml specified in the path, changes to the partial view's .cshtml file require a build to take effect.

The situation has improved from ASP.NET Core MVC 1.0.1 so that relative paths with .cshtml ending now work - however, relative path with no ".cshtml" still requires a new build for the changes to take effect.

This is material for https://github.com/aspnet/Mvc/issues/5574
