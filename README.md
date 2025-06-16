# How-to for Named Users

1. Use this template.

2. Create a new codespace.

3. In the devcontainer's bash terminal, run:
```console
# iarlogin login --use-device-code
To sign in, use a web browser to open the page https://iar.my.site.com/iarlogin/setup/connect
and enter code 4BCDEF876 to authenticate.
Login successful
```

4. Test the compiler with
```console
# echo "int main() {}" | iccriscv -

   IAR ANSI C/C++ Compiler V3.40.1.5519/LNX for RISC-V
   Copyright 2019-2025 IAR Systems AB.
   LMS Cloud License
 
 8 bytes of CODE memory

Errors: none
```

5. Opening the workspace in a local instance of VS Code will inherit the license activation token:

![image](https://github.com/user-attachments/assets/b837a84d-10ab-41fc-a4d6-8429559d99c0)

   
