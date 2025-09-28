# 3. Command History
The challenge was to check the command history.

## My Solve
**Flag:** `pwn.college{UGE0kVuQBb7sJJuER0ZxJFReRDR.0lNzEzNxwSN4kjNzEzW}`

```
hacker@hello~command-history:~$ the flag is pwn.college{ElyrhFxJ0Z6FmIS0r-if2-yYBeu.0lNzEzNxwCM0EzNzEzW}^C
```
The flag was given after pressing the the `up arrow` key once.

## What I learned 
I learned how to check command history,
By pressing , the `up` and `down` keys, I can jump see the commands alredy used.

## References
The problem statement was the reference:
```
You're going to type a lot of commands, and typing everything from
scratch can be annoying. Luckily, the shell saves a history of every command you invoke.

You can scroll through those saved commands with the up/down arrow keys,
and we'll practice that in this challenge.
This challenge will inject the flag into your history.
Bring up a terminal, hit the up arrow, and grab it!
In other challenges, the history will contain the log of the commands you've run,
so if you need to run a similar command again,
you can use the arrow keys to scroll through and find it!
```
