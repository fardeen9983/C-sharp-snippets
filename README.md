# C-sharp-snippets
Getting started with learning C# fundmentals by creating C# Console application based on .NET core framework

C# files have ' cs ' extension. 

Program.cs is the main entry point for our console app. Adding any other C# program with a main method will throw an error on project execution as there will be two different entry points
Hence it is advised to always keep one Main method or specify the desired entry point in the ' .csproj ' file:

To do add the following tag in Project/Project-Group :
> < StartupObject> C_sharp_snippets.Getting_started.Variables </ StartupObject>

Remember that if the namespace and program path contain ' - ', it has to be replaced with ' _ '.
___
## Data Types

 Data Type | Size (bytes) |
 :---------: | :----: |
 char      | 1 |
 short     | 2 |
 int | 4 
 long | 8 
 float | 4
 double | 8
 decimal | 16

 Many of these data types have their signed and unsigned variations as well.
