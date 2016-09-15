# Hello ASP.NET Core

This is just a repo for the first example of the .NET and ASP.NET *core* tutorials.

## Get .NET Core

.NET Core is Microsoft's cross-platform .NET effort and runs on Windows, Linux and OS X.

Before you can start, download .NET Core for your platform at [https://www.microsoft.com/net/core]

## Get the project up and running

After downloading and installing .NET Core in your environment you have a new command at your disposal:
`dotnet`

From the command-line you can create a new .NET Core project simply by typing `dotnet new` which should
be familiar to a lot of other backend developers in other languages.

I've already taken care of creating a new project with references to the .NET Core app framework and ASP.NET
Core NuGet packages. 

Before we can run this we need to restore those NuGet Packages as they're not bundled with the source code. This
should also be very familiar if you've worked with other package managers (e.g Gems in Ruby, Cocoapods for Swift/Obj-C).

To restore the packages run `dotnet restore` in the terminal. This will look in the **project.json** file 
to see what dependencies we've set up and try to resolve them from the official NuGet repository. 

All set? Then we can run our little Hello World application using `dotnet run`.

That's pretty much it. Now, there's a whole lot more to it, but it's cool for now.

Continue with the official docs over at [https://docs.asp.net/en/latest/getting-started.html]