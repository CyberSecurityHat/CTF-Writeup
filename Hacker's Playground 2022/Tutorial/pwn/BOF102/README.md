# BOF102

Stack Canary : Disable <br>
PIE : Disable <br>

Need to
- address of system function
  - #objdump -d -j .plt bof102 | grep system
- /bin/sh Address of the buffer where the string can be entered or the contents can be modified
  - #objdump -M intel -D bof102
