# Test the BookMark

## summerize
[Create a product](#create-product)
<p/>
[Create another product](#create-another-product)
<p/>
[Testing C#](#testing-C#)
<a name="testing-C#"></a> Testing C#


## detailed info

### <a name="create-product"></a> Create a product

Symbols can be used to specify conditions for compilation. You can test for the symbol with either #if or #elif. You can also use the conditional attribute to perform conditional compilation.

You can define a symbol, but you cannot assign a value to a symbol. The #define directive must appear in the file before you use any instructions that aren't also preprocessor directives.

You can also define a symbol with the /define compiler option. You can undefine a symbol with #undef.

A symbol that you define with /define or with #define does not conflict with a variable of the same name. That is, a variable name should not be passed to a preprocessor directive and a symbol can only be evaluated by a preprocessor directive.

The scope of a symbol that was created by using #define is the file in which the symbol was defined.

As the following example shows, you must put #define directives at the top of the file.

You can invoke the C# compiler by typing the name of its executable file (csc.exe) at a command prompt.

If you use the Visual Studio Command Prompt window, all the necessary environment variables are set for you. In Windows 7, you can access that window from the Start menu by opening the Microsoft Visual Studio Version\Visual Studio Tools folder. In Windows 8, the Visual Studio Command Prompt is called the Developer Command Prompt for VS2012, and you can find it by searching from the Start screen.

If you use a standard Command Prompt window, you must adjust your path before you can invoke csc.exe from any subdirectory on your computer. You also must run vsvars32.bat to set the appropriate environment variables to support command-line builds. For more information about vsvars32.bat, including instructions for how to find and run it, see How to: Set Environment Variables for the Visual Studio Command Line.

If you're working on a computer that has only the Windows Software Development Kit (SDK), you can use the C# compiler at the SDK Command Prompt, which you open from the Microsoft .NET Framework SDK menu option.

You can also use MSBuild to build C# programs programmatically. For more information, see MSBuild.

The csc.exe executable file usually is located in the Microsoft.NET\Framework\Version folder under the Windows directory. Its location might vary depending on the exact configuration of a particular computer. If more than one version of the .NET Framework is installed on your computer, you'll find multiple versions of this file. For more information about such installations, see Determining Which Version of the .NET Framework Is Installed.


### <a name="create-another-product"></a> Create another product

testing...

### <a name="testing-C#"></a> Testing C#

```c#
String name;
```

### C++
