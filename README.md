# ConsoleTest

Makes a .exe file when assembled and linked correctly that outputs a message with a colourful background. (and makes funny noises)
Closes when you do any keyboard input (including pasting things).

Code for assembler:

`ml ConsoleTest.asm /link /NOLOGO /NODEFAULTLIB /SUBSYSTEM:CONSOLE /ENTRY:START kernel32.lib Advapi32.lib`
