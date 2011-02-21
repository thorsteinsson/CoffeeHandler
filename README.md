CoffeeHandler
=============
CoffeeHandler is a .NET http handler for [coffeescript-dotnet](https://github.com/abolibibelot/coffeescript-dotnet) that compiles [CoffeeScript](http://jashkenas.github.com/coffee-script/) to javascript.

Add the following to the httpHandlers section of your web.config:
<add path="*.coffee" verb="*" type="CoffeeHandler.CoffeeHandler" />