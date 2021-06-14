# SOLUS MATE C++ / C VSCODE
- Objective is to create hello world app on Solus Mate using VScode as editor of choice.
- Install C++ plugin for VSCODE `https://code.visualstudio.com/docs/languages/cpp`
- Install GCC / C compiler toolchain on Solus Mate `sudo eopkg install -c system.devel` 
- Install gdb on Solus Mate `sudo eopkg install gdb`
- Install Ninja on Solus Mate `sudo eopkg install ninja`

- Open terminal in project root
Run command `make -G Ninja` to build ninja files
Run command `ninja` to build production executable file

- Debugging
In VScode simply use the shortcut CTRL + F5 to run the debugger