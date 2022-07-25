# 0x04. Loops, conditions and parsing

## The Advantage of using #!/bin/env bash
* The advantage of #!/usr/bin/env bash is that it will use whatever bash executable appears first in the running user’s $PATH variable. If you have two version of bash installed as follows and PATH set to /home/vivek/bin:/usr/local/bin:/usr/bin:/bin:/usr/games/bin:/bin:/usr/bin, than bash4 will execute the script:
----
# Using env in the shebang of a script
* env is a shell command for Unix-like operating systems. We can use it for various purposes. For example:

* Display a list of environment variables
* Run another command in a modified environment
* Add or remove variables
* Change the value of existing variables
----
* To show current environment variables defined by your shell, run env command:
env
--------
## Table of contents
Files | Task Description
----- | -----------
[0-RSA_public_key.pub](./0-RSA_public_key.pub) | Public key for RSA key pair
[1-for_best_school](./1-for_best_school) | Bash script that displays best School 10 times
[2-while_best_school](./2-while_best_school) | Bash script that displays best School 10 times
[3-until_best_school](./3-until_best_school) | Bash script that displays best School 10 times
[4-if_9_say_hi](./4-if_9_say_hi) | Bash script that displays best School 10 times, but for the 9th iteration, displays best School and then Hi on a new line
[5-4_bad_luck_8_is_your_chance](./5-4_bad_luck_8_is_your_chance) | Bash script that loops from 1 to 10
[6-superstitious_numbers](./6-superstitious_numbers) | Bash script that displays numbers from 1 to 20
[7-clock](./7-clock) | Bash script that displays the time for 12 hours and 59 minutes
[8-for_ls](./8-for_ls) | Bash script that displays The content of the current directory, In a list format, Where only the part of the name after the first dash is displayed
[9-to_file_or_not_to_file](./9-to_file_or_not_to_file) | Bash script that gives you information about the school file
[10-fizzbuzz](./10-fizzbuzz) | Bash script that displays numbers from 1 to 100