# soft_engineering-

## linux commands
mc - midnight comander 
ls - list
cd - change direction 
ls -lah list wyświetla pliki i katologi ukryte i pokazuje icgh zawartość oraz właściciela 
grep -r - wyszukaj
mkdir <catalog> - mowy katalog
touch <file> - nowy plik
nano <file> - edytor

## WSL
# java commands
cd ~/WorkDir/soft_engineering-  go to catalog
javac alaMaKota/Main.java       compile the file (ex. *.java)
java alaMaKota.Main             run the script

--
### in project
javac src/main/java/edu/io/Main.java
java -cp src/main/java edu.io.Main


## VSC
# C:\WorkDir\.vscode\launh.json 
```json
    {
     "type": "java",
     "name": "Debug Januszek",
     "request": "launch",
     "mainClass": "token.kacper.Januszek"
    }
    
    {
      "type": "java",
      "name": "Debug Java Program",
      "request": "launch",
      "mainClass": "token.one"
    }    
```
## catalog structure

```
└── token
    ├── kacper
    │   ├── Januszek.class
    │   └── Januszek.java
    ├── one.class
    └── one.java
```