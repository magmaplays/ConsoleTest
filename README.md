# ConsoleTest

Makes a .exe file when assembled and linked correctly that outputs a message with a blue background.
Closes when you do any keyboard input (including pasting things).

Code for assembler:

`ml code.asm /link /NOLOGO /NODEFAULTLIB /SUBSYSTEM:CONSOLE /ENTRY:START kernel32.lib`
