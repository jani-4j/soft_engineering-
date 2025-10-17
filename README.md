# soft_engineering-

## linux commands
mc - midnight comander 
ls - list
cd - change direction 
ls -lah list wyświetla pliki i katologi ukryte i pokazuje icgh zawartość oraz właściciela 
grep -r - wyszukaj

## WSL
## java commands
cd ~/WorkDir/soft_engineering-  go to catalog
javac alaMaKota/Main.java       compile the file (ex. *.java)
java alaMaKota.Main             run the script

## VSC
## C:\WorkDir\.vscode\launh.json 
```json
    {
  "version": "0.2.0",
  "configurations": [
    {
      "name": "(gdb) Attach",
      "type": "cppdbg",
      "request": "attach",
      "program": "enter program name, for example ${workspaceFolder}/a.exe",
      "MIMode": "gdb",
      "miDebuggerPath": "/path/to/gdb",
      "setupCommands": [
        {
          "description": "Enable pretty-printing for gdb",
          "text": "-enable-pretty-printing",
          "ignoreFailures": true
        },
        {
          "description": "Set Disassembly Flavor to Intel",
          "text": "-gdb-set disassembly-flavor intel",
          "ignoreFailures": true
        }
      ]
    },
    {
      "name": "C/C++ Runner: Debug Session",
      "type": "cppdbg",
      "request": "launch",
      "args": [],
      "stopAtEntry": false,
      "externalConsole": true,
      "cwd": "c:/WorkDir",
      "program": "c:/WorkDir/build/Debug/outDebug",
      "MIMode": "gdb",
      "miDebuggerPath": "gdb",
      "setupCommands": [
        {
          "description": "Enable pretty-printing for gdb",
          "text": "-enable-pretty-printing",
          "ignoreFailures": true
        }
      ]
    },
    {
      "type": "java",
      "name": "Debug Java Program",
      "request": "launch",
      "mainClass": "alaMaKota.Main"
    }
  ]
}

```
