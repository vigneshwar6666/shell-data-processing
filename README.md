# shell-data-processing cheat sheet
## CURL command
curl "" -O "data.txt" is used to return the page text and output to a file.
## Most used powershell commands
1. mkdir - To create a new directory
2. cd - To change the directory
3. ni - To create a new empty item
4. ls - To list the contents

## Git Bash commands to process the text
1. tr ' ' '\12' < returnedfile - Transform each space ' ' into a return character '\12'
2. tr ' ' '\12' < returnedfile | sort - Pipe the output to sort
3. tr ' ' '\12' < returnedfile | sort | uniq -c - Pipe the sorted output to uniq -c to count
4. tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr - Pipe the reduced output to sort with -nr flag
5. tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr > result.txt - Redirect the output to result.txt 

## Important Bash commands
1. > To redirect the contents of your directory into a file.
2. >> Two arrows to append rather than overwrite. 
3. ls -  To list the contents of the default directory. 
4. cat - To display the contents of text file.
5. Copy in Bash is not CTRL+C as in Windows, instead use CTRL+SHIFT+C.
