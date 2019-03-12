# SaC-Masterclass
To begin the exercises, the path compiler must be set which is located in ```/home/cs4/gg3/sacDev/bin/``` 
by exporting the path to the folder in the `.bashrc` file (replace this with `.bash_profile` if using remote login) using the command/:

```
echo 'export PATH=$PATH:/home/cs4/gg3/sacDev/bin' >> .bashrc
```

To activate the changes, use the command:

```
source .bashrc
```

We can make sure this has worked by running the command 

```
sac2c -V
```

If everything worked correctly, to compile any of the SaC programs you will be writing, simply use the command with `sac2c` as you may
with `gcc` or other compilers.

```
sac2c test.sac
```

Which will create an executable `a.out` which can be ran with `./a.out`.
Optionally, one may also compile to a specific output file by providing the `-o` flag and the filename to create.

```
sac2c test.sac -o test.o
```

This will create an executeable called `test.o` which is also just ran with `./test.o`.

## Exercise 1

## Exercise 2

## Exercise 3
Using the example files of the 3 and 5-point-stencil relaxations, come up with a solution 
for the briefly mentioned 7-point-stencil relaxation. 
