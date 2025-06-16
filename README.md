# How-to for Named Users

1. Use this template on VS Code or create a new Codespace.
2. In the devcontainer, open a bash terminal and run:
```console
# iarlogin login --use-device-code
To sign in, use a web browser to open the page https://iar.my.site.com/iarlogin/setup/connect
and enter code 4BCDEF876 to authenticate.
Login successful
```
3. Test the compiler with
```console
# echo "int main() {}" | iccarm -

   IAR ANSI C/C++ Compiler V9.70.1.475/LNX for ARM
   Copyright 1999-2025 IAR Systems AB.
   LMS Cloud License (LMSC 1.5.0)
 
 4 bytes of CODE memory

Errors: none
```

4. If you need a project, use https://github.com/iarsystems/bx-workspaces-ci.

![image](https://github.com/user-attachments/assets/676b32f4-70ee-4270-b400-7daac1cf684d)



   
