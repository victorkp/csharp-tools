## C# Tools for the Linux command line ##

It's recommended that you put this repository in your `$PATH`, for easy invoking.

### `csmake` ###
From the root directory of an existing C# project (created by Monodevelop or Visual Studio), run `csmake`. `csmake` will find your project's name from your `*.csproj` file, will find all `*.cs` files recursively, and will run `mcs` on the source files, building an executable with your project's name.

