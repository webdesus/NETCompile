# NETCompile
A library with functions to easily compile .NET apps/libs, also featuring compilation into memory without compiling to disk!

HOWTO:

Example:
using NETCompile;

 Compiler1.Compile("HelloWorld.exe", Compiler1.Target.EXE, Compiler1.Platform.x86, new string[] { "",""}, new string[] { "", "" }, false, @"C:\Users\ion\Desktop\helloworld.cs", Compiler1.Language.CSharp);
 
 Compiler1.Compile(filename, EXE/DLL, x86/x64, referencesPathsArray(blablabla.dll,bla.dll), ressourcesPathArray(hey.txt,test.dat), allowUnsafeCode, sourceFile, CSharp/VB);



FOR Compiler2: Download and Compile this and copy all files to C:\Roslyn\ (https://roslyn.codeplex.com/). It's the same as Compiler1 but uses Roslyn for C#6 compilation :D

Compiler2.Compile(filename, EXE/DLL, x86/x64, referencesPathsArray(blablabla.dll,bla.dll), ressourcesPathArray(hey.txt,test.dat), allowUnsafeCode, sourceFile, CSharp/VB);
