0. Write a Bash script that displays its own PID.
1. Write a Bash script that displays a list of currently running processes.
Must show all processes, for all users, including those which might not have a TTY
Display in a user-oriented format
Show process hierarchy
2. Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
You cannot use pgrep
The third line of your script must be # shellcheck disable=SC2009
3. Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word bash. You cannot use ps.
4. Write a Bash script that displays To infinity and beyond indefinitely.
In between each iteration of the loop, add a sleep 2
5. Write a Bash script that stops 4-to_infinity_and_beyond process. You must use kill.
6. Write a Bash script that stops 4-to_infinity_and_beyond process. You cannot use kill or killall.
7. Write a Bash script that displays:
To infinity and beyond indefinitely
With a sleep 2 in between each iteration
I am invincible!!! when receiving a SIGTERM signal
Make a copy of your 6-stop_me_if_you_can script, name it 67-stop_me_if_you_can, that kills the 7-highlander process instead of the 4-to_infinity_and_beyond one.
8. Write a Bash script that kills the process 7-highlander.
