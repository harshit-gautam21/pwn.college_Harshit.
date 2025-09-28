### Program and absolute paths

This challenge again requires you to execute it by invoking its absolute path. You'll want to execute the `run` file that is in the `challenge` directory that is, in turn, in the `/` directory. If you invoke the challenge correctly, it will give you the flag.

--- 
**Flag:** `pwn.college{YxcaYM1I-PZ8PlW9PNDkqIK-Xmi.QX1QTN0wSN4kjNzEzW}`

command used: `/challenge/run`
## What I Learned
Used the knowledge of absolute file paths to pass the absolute file path of the `run` file to get the flag.
## References
The problem statement was the reference used
```
Let's explore a slightly more complicated path! Except for in the previous level, challenges
in pwn.college are in the challenge directory and the challenge directory is,
 in turn, right in the root directory (/). The path to the challenge directory is,
 thus, /challenge. The name of the challenge program in this level is run, and it
lives in the /challenge directory. Thus, the path to the run challenge program is /challenge/run.

This challenge again requires you to execute it by invoking its absolute path. You'll want to execute
 the run file that is in the challenge directory that is, in turn, in the / directory. If you invoke
the challenge correctly, it will give you the flag. Good luck!
```
