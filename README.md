# TERMINATE BASH SCRIPT USAGE GUID

## Description
		Terminate - Bash Based Process Killer.
This script is designed to stop process just like the "kill -9" unix command, in fact this uses it under the hood, but this tool give the user more power by just providing the name of the process and not be obliged to go and search for each p-id related to it and kill them one after the other.


## Setup
	
	git clone <this repo url>
	--
	cd terminate
	--
	cp ./terminate /usr/bin/terminate
	--
	// OPTIONAL
	which terminate

The expected output of the last command is "/usr/bin/terminate"

##### Note 
Now you can run the terminate command anywhere in your machine.



## Benefits of terminate
1. Easy to use.		
2. More user power.		
3. Modular.		
4. Time gain  compared to the unix kill command.		


## Usage
#### Using The Process Name:
 
	terminate <name_of_the_process>
	
	:stdout: killed

Exemples:
	
	terminate firefox

This will get all the processes related to firefox in your machine, and kill them.
	      so all you firefox windows will be shutdown.

#### Using String Expension:

	terminate <sub_string>*
	
	:stdout: warning message built in the terminate script, then if all it goes well, you will get the "killed" message.

Exemples:
	
	terminate fire*

This will get all the processes with a process name begining with "fire", then it will kill them.

##### Warning
Using the string expention method gives you more flexiblity and power, but it also can be very dangerous, do it at your own risk.



## License
MIT




