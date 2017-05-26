# noodletools
Noodle Tools API. 

# Download
NoodleTools will be on NuGet soon.

# Basic Usage
```csharp
NoodleTools noodleTools = new NoodleTools("username", "password");
// NoodleToolsAPI will auto log in
var project = noodleTools.GetProjects().FirstOrDefault();
project.SetThesis("Noodle Tools API is awesome!");
```
