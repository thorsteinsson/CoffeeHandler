CoffeeHandler
=============
CoffeeHandler is a .NET http handler for [coffeescript-dotnet](https://github.com/abolibibelot/coffeescript-dotnet) that compiles [CoffeeScript](http://jashkenas.github.com/coffee-script/) to javascript.

Add the following to the httpHandlers section of your web.config:

	<add path="*.coffee" verb="*" type="CoffeeHandler.CoffeeHandler" />

Note: This is only for development purposes and should not be used in a live environment. It should be a part of your builds to create js files for all coffee files.