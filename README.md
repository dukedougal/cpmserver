# cpmserver - your opinion wanted!
A way to give any vintage Z80 machine CP/M via a cable to any modern computer such as a Raspberry Pi/Windows/Linux/OSX machine

# what do think this of this idea? post your thoughts/questions/ideas as issues for this project

October 2020

This is a brand new project, it's just an idea right now.

The idea is this:

# Overview:
* The user connects a vintage Z80 computer to a modern computer via a cable.
* The cable might be any cable - parallel/serial - anything bidirectional.
* A CP/M disk driver is written in assembly language for the Z80 machine.
* The CP/M disk driver actually makes the bidirectional port look like a floppy disk drive to CP/M.
* The server running on the PC listens to the bidirectional connection and acts as one or more floppy disk drives.
* The server would be built using the Python programming language.

# Booting up: 
* the Z80 machine, with the minimum BASIC code, should be able to start reading bytes from the bidirectional port.
* the server application is constantly looping through sending bytes to the Z80 machine - the bytes provide bootstrap code that gets the whole system started.

# Internet access via AT commands:
* It should also be possible for the server to provide access to the Internet for the Z80 machine.
* The concept of providing Internet access via AT commands is already well established by various devices such as the wifi232:
http://biosrhythm.com/?page_id=1453
and the pimodem:
http://podsix.org/articles/pimodem/

# Specific goals:
* The goal is to design a system that supports multiple types of vintage Z80 computers and multiple types of bidirectional connections.

# Current status Oct 2020:
Gathering ideas and gauging interest to see if anyone thinks it's a good idea, to see who might be interested to participate






