# MediaNugetPackages
Nuget packages for the Microsoft Smooth Streaming SDK:  
https://visualstudiogallery.msdn.microsoft.com/1e7d4700-7fa8-49b6-8a7b-8d8666685459

And PlayerFramework:  
https://playerframework.codeplex.com  

## Howto
### PlayerFramework:
1 Compile the playerfrawork sdk using the BuildSDKs.Win10.bat script from the playerframework project.  
2 Copy the following files to the packages folder:

#### Project Microsoft.Media.Advertising  
Copy  
Microsoft.Media.Advertising.pdb  
Microsoft.Media.Advertising.pri  
Microsoft.Media.Advertising.winmd  

from: 
playerframework\UWP.Xaml.Advertising\bin\Release  
to:  
Microsoft.Media.Advertising\lib\uap10.0

To generate the nuget package:  
nuget pack Package.nuspec
