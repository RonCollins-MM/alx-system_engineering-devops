A description of the action of each script is given below in the format:

"Command" : Description of action

"./0-current_working_directory" : Prints the absolute path name of the current working directory

"./1-listit" : Displays the content list of the current directory

"./2-bring_me_home" : Changes current directory to home

"./3-listfiles" : Displays directory content in long format

"./4-listmorefiles" : Display content directories including hidden files in long format

"./5-listfilesdigitonly" : Displays the current directory content
			   In long format
			   With User and Group IDs displayed numerically
			   Including hidden files

"./6-firstdirectory" : Creates a directory named 'my_first_directory' in /tmp/

"./7-movethatfie" : Moves a file named 'betty' from /tmp/ to directory created above

"./8-firstdelete" : Deletes the file created by above command

"./9-firstdirdelete" : Deletes directory created by command 6. Assumes it is empty

"./10-back" : Move back to previous directory