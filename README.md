# AdminLTE.NETCore
Implementation of AdminLTE Layout with ASP.NET Core MVC

For the source of the layout look at here, there is great support there:
https://github.com/almasaeed2010/AdminLTE

The goals of this project are:
- Contribute to open source
- Learn more about .NET Core integration with client side plugins
- Learn how GitHub works
- Collaborate with other developers

Project scopre:
- Use AdminLTE layout to show usage of a custom layout in .NET Core.
- Present the layout options as partial views for a more responsive user experience.

2017-01-19
This release is incorporating the version 2.3.11 of the AdminLTE Layout.
Full implementation into .NET Core is not complete.

Todo List:
- Figure out how to execute js after loading a partial view. (done)
- Clear previous "active" flag from 'treeview-menu' item (done)
- Implement the rest of the controllers and actions for pages (done)
- Refactor code to clean up redundancies in Razor views (done)
- Figure out script loading/unload after partial views to avoid conflicts. (scratch this)
- Load all scripts and css in layout (partially done)
  > Need to load the datatables
  
- Fine tune the implementation.
