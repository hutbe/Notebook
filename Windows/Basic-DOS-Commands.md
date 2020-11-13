#### `cd`: go through dicrectories
`cd /d d:\` switch to disk D
#### `dir`: list dicrectories information
`dir /s`: list all files include sub directories
#### `tree` list directories info on a tree, does not include files
`tree /f` list dirs and files
#### `ren` change file's name
`ren file_name.txt new_file_name.txt` change the file to the name of new_file_name.txt

#### Create new files
* Using command `copy con file_name.txt`, ending input `Control+Z`:

	Run command `copy con file_name.txt`, then input your information, it doesn't care ''or "". The indicator of end is Control+Z

* Using command `echo conten > file_name.txt`:
	
	`echo apple:3 > note.txt` Create a new file with appel:3
	
	`echo milk:2 >> note.txt` Append milk:2 to the file
	

#### `type`: print out the contents of a file
#### `more`: print the contents with separated screen
#### `del`: delete files
#### `rd`: delete directories
`rd dir_name`: if the folder dir_name is empty
`rd /s dir_name`: Recursiveyly delete dir of dir_name
`rd /p dir_name`: Don't needs confirm before delete

#### `color`: change console's background color, `color -h`for more information

#### `net user administrator /active:yes` active admin account
`net user administrator /active:no`
