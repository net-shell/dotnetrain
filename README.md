# .NET Rain

A .NET decompiler with support for XAP applications.
Allows <s>hackers</s> developers to decompile assemblies and resources in a code editor, make changes and compile the code back to the assembly.

### [DOWNLOAD](https://code.google.com/p/dotnet-rain/downloads/detail?name=beta3.zip&can=2&q=) v 0.0.3

### Features
* Decompile .NET assemblies to C# and allow editing/compiling the high-level code back to CIL
* Edit CIL instructions in method bodies
* Modify assembly structure
* Edit and extract assembly resources
* Edit the contents of a XAP by adding, removing or swapping files, or using internal editors for certain resource types.
* Integrated editors for text, hex, manifest, resource, XML and XAML.
* XAP package manager (compatible with Windows Phone and Silverlight applications) allowing to view and extract XAP contents.
* Does laundry, has mastered Italian cuisine, cleans and makes mind-blowjobs when asked kindly and treated right.

### Sorry, what?

I have plans to add a few more features and make a complete update for Windows (Phone) 10.

Since this software is not yet stable I'd like to mention Reflector as an alternative, but I think it's way too overpriced and I don't find it especially user-friendly as well.

.NET Rain is donateware. Its development pretty much depends on your feedback and support.

### DLL Deep Throat
The program tries to locate referenced assemblies but so far it does a very poor job and in many cases you'll have to manually point them. Sorry, it's open source :)

Usually you are shown the "open file" dialog after opening a DLL. In the filter box you can see a file name (SomeAssembly.dll).
This is an assembly that has been referenced in the DLL you are trying to decompile but cannot be found in the same folder as the DLL, in the XAP package or in the GAC. You have to show the program where the file is located, so it can be loaded and decompiled as well.

For Windows Phone 7.5 the path for most assemblies looks like `C:\Program Files[ (x86)]\Reference Assemblies\Microsoft\Framework\Silverlight\v4.0\Profile\WindowsPhone71`.

### Some Links
* [Old Google Code page](https://code.google.com/p/dotnet-rain/)
* [15 minutes of fame](http://www.xda-developers.com/take-apart-xap-at-your-leisure-with-net-rain/)
* [Old XDA forums thread](http://forum.xda-developers.com/showthread.php?t=1443692)
* [Active XDA forums thread](http://forum.xda-developers.com/windows-phone-8/development/xap-dll-exe-hacking-tool-disassembler-t3182752)

### Screenshits
<img src="http://i.imgur.com/dppU8Mr.png">
<img src="http://i.imgur.com/SvvdYU1.png">
<img src="http://i.imgur.com/OBAJRQQ.png">
<img src="http://i.imgur.com/CukYRDn.png">
