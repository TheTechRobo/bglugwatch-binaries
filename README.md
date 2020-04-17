# bglugwatch-binaries
Frozen binaries for BGLUGwatch

# How to use?
Simply execute the binary file for your OS and arch.

# What are the pros?
- easier to use
- easier to distribute 
- you no need install python to use them

# Cons?
- updates slower (i don't have the time to maintain them)
- larger files
- not all platforms supported (yet!)*

# Glossary
- arch: There are four main arches: amd64 (AKA x86_64), i386 (AKA x86), arm32 (AKA arm), arm64 (AKA arm)  
The one you most likely have is amd64 (64-bit). Or i386, if your CPU is older. Or arm32 or arm64, if you are using a Raspberry Pi.
- OS: operating system. The main, broad term for the only OSes that BGLUGwatch will ever support**, is " Linux " but there are two popular flavours: Debian and Arch. The more common one for end-users is Debian (Ubuntu is based on Debian) and for advanced users, Arch Linux. 
- frozen: a single program file that includes the interpreter. Useful in interpreted languages. Basically " compiling " an interpreted language. I use [pyinstaller](https://pyinstaller.org) to freeze Python scripts and make these pre-built binaries.

`*` But you can help with this! Install pip3, run `pip3 install pyinstaller`, and run `pyinstaller --onefile --windowed bglug.py` and then PR it! Thanks! :)
`**` Because it is a **Linux** user's group.
