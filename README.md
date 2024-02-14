# Bash-Scripting

Print something in Linux - 

```
VARR=Sunaina
echo $VARR
```
![image](https://github.com/Sunainacode/Bash-Scripting/assets/56354115/77a9c137-4211-46f2-9822-3f0b6ad7a2f2)

To know the bash location in Linux -

```
which bash
```
![image](https://github.com/Sunainacode/Bash-Scripting/assets/56354115/ad20213a-87d2-4db2-9666-5e4822f0f374)

Create a new Bash script -

```
touch bash.sh
```

Work  on the script =

```
vi bash.sh
```
In the script, paste the path of bash obtained above as follows in the first line of the script file -

```
#! /bin/bash
```

Try to print something using bash script - 

```
NAME="SUNAINA"
echo "My name is $NAME"
```
![image](https://github.com/Sunainacode/Bash-Scripting/assets/56354115/fdbbcd43-b260-4067-8635-e53da8e3295d)

Using arguments in bash script output -

```
echo "I firmly believe in $1 against $2 because it increases work productivity."
```
![image](https://github.com/Sunainacode/Bash-Scripting/assets/56354115/04f66cd3-4ad6-43df-8272-e717ced622ea)

Print the output of a command - 
```
echo $(whoami)
```
![image](https://github.com/Sunainacode/Bash-Scripting/assets/56354115/3a04ca3d-3150-476f-b7f5-d12e50659ac6)

Read input from user -

