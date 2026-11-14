While setting up my C environment, I first got an error running multiple commands in PowerShell because it did not support &&, so I ran each command on its own line.
GCC was already installed through MSYS2, and I confirmed it by running gcc --version and g++ --version from a different folder to make sure PATH was set correctly.
When I first compiled hello.c, I got an "undefined reference to WinMain" error because the file did not have a saved main function.
I fixed it by saving the file with the correct code and compiling again.
After that, gcc hello.c -o hello.exe worked and .\hello.exe printed "Hello, World!".
I also named my note file setup-node.md by mistake and renamed it with git mv.