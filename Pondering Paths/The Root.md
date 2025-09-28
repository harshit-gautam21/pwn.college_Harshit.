### The root

Start the challenge, launch a terminal, invoke the `pwn` program using its absolute path, and Capture that Flag

--- 

**Flag:** `pwn.college{kUDQXx0n57N5B7f0avuwuoGFv1S.QX4cTO0wSN4kjNzEzW}`

command used: `/pwn`
## What I learned
The file system in linux starts with `/` under that thera are many directories,files,
programs and flags
The root directory is represented by `/`
I learned that the one which start with the root directory
is reffered as absolute path

## Reference
The problem statement was the reference used
```
Alright, so the filesystem starts at /. Under that, there are a whole mess of
other directories, configuration files, programs, and, most importantly, flags.
In this level, we've added a program right in /, called pwn, that will give you
 the flag. All you need to do for this level is to invoke this program!

You can invoke a program by providing its path on the command line. In this case, you'll
be giving the exact path, starting from /, so the path would be /pwn. This style of path, one
that starts with the root directory, is referred to as an "absolute path".

Start the challenge, launch a terminal, invoke the pwn program using
its absolute path, and Capture that Flag! Good luck!
```
