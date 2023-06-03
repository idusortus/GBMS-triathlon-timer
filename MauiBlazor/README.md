Orange0715!
Build and sign your app
To build your app from the command line, and sign it using your keystore, open a terminal and navigate to 
the folder for your .NET MAUI app project. Run the dotnet publish command, providing the following parameters:

Parameter	Value
-f or --framework	The target framework, which is net7.0-android.
-c or --configuration	The build configuration, which is Release.

  MauiBlazor    dotnet publish
MSBuild version 17.6.1+8ffc3fe3d for .NET
MSBUILD : error MSB1011: Specify which project or solution file to use because this folder contains more than one project or solution file.
  MauiBlazor    dotnet publish .\MauiBlazor.csproj -f net7.0-android -c Release
