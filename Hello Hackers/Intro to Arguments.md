# 2. Intro to Arguments
The challenge was about using commands and arguments.
The command `echo` was introduced.

## My solve
**Flag:** `pwn.college{QZtqZ9BqxwyPE33oJNfLeGik4vK.QX4YjM1wSN4kjNzEzW}`

In the given problem the hello command was used with the argument hackers to generate the flag
```
hacker@hello~intro-to-arguments:~$ echo Hello Hackers!
Hello Hackers!
hacker@hello~intro-to-arguments:~$ hello hackers
Success! Here is your flag:
pwn.college{QZtqZ9BqxwyPE33oJNfLeGik4vK.QX4YjM1wSN4kjNzEzW}
```

## What I Learned 
I learned the use of echo command.
I learned how to add arguments to commands.
The problem was to use the `hello` command with a specific arguument that would get the flag.

## References
The problem statement provided was used as the reference
```
Let's look at echo with multiple arguments:

hacker@dojo:~$ echo Hello Hackers!
Hello Hackers!
hacker@dojo:~$

In this case, the command was echo, and Hello and Hackers! were the two arguments to echo. Simple!

In this challenge, to get the flag, you must run the
 hello command (NOT the echo command) with
 a single argument of hackers. Try it now!
```
