# Terminal command used & learned
Here are the list of command used during the [Beginner Boost](http://rwx.gg) **Linux Command Line** course.

## pwd
Locate where we are
```
pwd
```

## Clear
Clear the screen of the terminal
```
clear
```

## ls
```
ls
```
Display files under current path.
```
ls -la
```
List files unders current path with permissions, date creation, etc...

Some alias may exist on some system but **NOT** all of them:
```
ll
la
```

## cd
Go under a certain path of the filesystem
```
cd /valid/path/to/somewhere/
cd ..
cd ~
cd /
```

## touch
Create a new file if does not exist.
If it exist, edit the last time touched.
```
touch myfile
```

## mkdir
Create a new directory
```
mkdir my_dir
```

## which
Locate where a command executable is located under the file-system
```
which git
```
If does not exist return an error. Nice to test is a command is present or not.

