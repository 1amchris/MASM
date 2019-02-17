# MASM
This is a Microsoft Assembly template for Visual Studio 2017

# How to install the template
  First, download the github repository to your computer. The only file you will need is the MASM.zip file.
  Second, move the MASM.zip folder to this location on your computer (assuming you have left default all installation parameters for Visual Studio 2017) : 
    C:\\Users\\'your user goes here'\\Documents\\"Visual Studio 2017"\\"My Exported Templates"

  That's it! The installation is now completed
  
# How to use the template
  Open Visual Studio 2017 and create a new Solution (as some settings will be changed for the whole solution)
  In your solution creator window, you will find a new template named "MASM". Mine is located under 'C++'.
  Use this template (instead of other predefined templates) and name your project and your solution as you wish. Now select 'create new' and you'll be ready to code Microsoft Assembly in the main.asm file.
  
  Voila!

# How it's organised
  The file is mainly separated in two parts. Note that this is not all there is to it, but for simple programs this should work fine.
  There are two section named '.data' and '.code'.
  Under '.data' you should create any variables you desire.
  Under '.code' you should write the program you desire.
  
# Visual Studio 2017 tools
  Visual Studio is filled with helpful tools and while running your program, you may want to see the modifications made to your memory and to your registers.
  For Registers information, while running the Local Windows Debugger, select "Debug> Windows> Registers".
  Similarly, for memory information, while running the Local Windows Debugger, select "Debug> Windows> Memory", you can open up to four Windows.
