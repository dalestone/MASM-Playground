# MASM-Playground

##Assembly basics
An assembly language is a low-level programming language which is specific to a particular computer architecture. It is most often abbreviated asm.

##Microsoft Macro Assembler (MASM)
The MASM is an x86 assembler that uses the intel syntax for MS-DOS and Microsoft Windows.

## MASM in Visual Studio
1. Created Visual C++ Win32 Console Application
2. In the Win32 Application Wizard make sure the following are checked: Application type: Console Application,  Additional options: Precompiled header [x], Security Development Lifecycle (SDL) checks
4. Delete uncessary files/folders such as Header Files, Resource Files, Source Files
5. Righ click project and add .asm file (you will need to create a text file and change the extension)
6. Once you have created the .asm file, for example main.asm right click project and go to Build dependencies -> Build Customizations
8. In build customiziations check masm(.targets, .props)
9. Set Configuration Properties

###Assembly Syntax highlighting in visual studio
* [AsmDude](https://github.com/HJLebbink/asm-du)
* [AsmHighlighter](https://asmhighlighter.codeplex.com/)