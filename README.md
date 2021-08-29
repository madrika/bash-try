# dws-dev-006-bash
TRY:

With  this  code,  you  can  repeat  a  command  with  a number  of iterations  and  at  intervals.


# TRY-1

The  entries  in  this  program  must  be  imported  in  this  way:
Options:
-i num, Time  interval  between  commands  repetition.
-n num, Number  of iterations  a  command.


## Sample-TRY-1
$scriptName [-i interval] [-n number] command
try -i 3 -n 5 mkfifo MHPD
try -i 5 -n 7 ping 8.8.8.8
Run  for  each  instruction  other  than  this  Help:
Synopsis
    $scriptName [-i interval] [-n number] command


    -i interval
	   The time interval between checks if the process is not performed.
        

    -n number
	   Number of  repetitions for command completion.
        
Sample:
	
	try -i 3 -n 5 mkfifo MHPD
	try -i 5 -n 7 ping 8.8.8.8
	
## note:
@dwsclass dws-dev-006-bash
