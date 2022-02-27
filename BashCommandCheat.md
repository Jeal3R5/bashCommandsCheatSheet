# Bash Commands Cheat Sheet  

1.  **ls**   
    * List directory contents (_aka: folder_)
    * _Common Options:_
        * -a (**all**)
        * -l (**list**)  
    
2. **echo**  
   * Prints text to the terminal 
   * Typically used in shell scripts and batch files to output status text to the screen or computer file
   * Useful for showing values of environmental variables
   * Tell shell how to behave as a user works at command line or in scripts  
   * _Syntax:_  
        * echo [options][strings]
    * _Common Options:_  
        * -e
        * -n  
              

3. **touch**  
   * Creates new file 
   * Changes timestamp on files and/or directories  
   * Create as many files as you want in a single command
   * _Syntax:_  
        * touch [options] file_name(s)
    * _Common Options:_
        * -a
        * -m
        * -r (**recursive**)
        * -d

4. **mkdir**
    * Create a directory (_aka: folder_)
    * Can create any number o fdirectories at the same time
    * _Syntax:_
        * mkdir [options] directory_name(s)
    * _Common Options:_
        * -m
        * -p
        * -v

5. **grep**
    * Search text for patterns specified by the user
    * To find a specific string or pattern
    * _Syntax:_
        * grep [option(s)] patter [file(s)]
    * _Common Options:_
        * -i
        * -c
        * -n

6. **man**
    * Is your manual
    * Useful when need to figure out what a command does
    * _Syntax:_
        * man [option(s)] keyword(s)
    * _Common Options:_
        * -w
        * -f 
        * -b

7. **pwd**
    * Print Working Directory
    * Used to print which directory you are currently in
    * _Syntax:_
        * pwd [option(s)]
    * _Common Options:_
        * None typically used

8. **cd**
    * Change directory
    * _Syntax:_ 
        * cd [option(s)] directory
    * _Common Options:_ 
        * None typically used  


9. **mv**
    * To move files
    * To rename directories
    * Allows you to do batch file renaming 
    * _Syntax:_
        * mv [option(s)] argument(s)
    * _Common Options:_
        * -i
        * -b  

10. **rmdir**
    * Removes directory
    * Two ways to remove directory
        * **rm:** will remove directories and files regardless if they contain data or not
        * **rmdir** will only delete empty directories
    * _Syntax:_
        * rmdir [option(s)] directory_names
    * _Common Options:_
        * -p  

11. **locate**
    * Locates a specific file or directory
    * Can do broad or narrow scope searches
        * broad if you don't know exactly what your looking for 
        * narrow by using wildcards or regular expressions
    * _Syntax_:
        * locate [option(s)] file_name(s)
    * _Common Options:_
        * -q
        * -n
        * -i  

12. **less**
    * Allows you to view files w/o opening an editor
    * No chance of you accidentally changing the file
    * _Syntax:_
        * less file_name
    * _Common Options:_
        * -e
        * -f
        * -n  

13. **compgen**
    * To reference all available commands, aliases, and functions
    * _Syntax_
        * compgen [option(s)]
    * _Common Options:_
        * -a
        * -c
        * -d  

14. **cat**
    * 3 Main Functions:
        * Display file
        * Combining copies of files
        * Creating new files
    * _Syntax:_
        * cat [option(s)][file_name(s)] [-] [file_name(s)]
    * _Common Options:_
        * -n  

15. **head**
    * Displays the **first** ten lines of a file
    * Could be used when you need to analyze logs or text files that are often changed
    * _Syntax:_
        * head [option(s)] file(s)
    * _Common Options:_
        * -n  

16. **tail**
    * Displays the **last** 10 lines of a file
    * Used when you need to analyze often changing logs or text files
    *  _Syntax:_
        * tail [option(s)] file_name(s)
    * _Common Options:_
        * -n  

17. **exit**
    * Exit out of  a directory
    * Closes a terminal window
    * Ends execution of a shell script
    * Logs you out of an SSH remote access session
    * _Syntax:_
        * exit
    * _Common Options:_
        * n/a  

18. **history**
    * Quickly identify past commands used
    * _Syntax:_
        * history
    * _Common Options:_
        * -c
        * -d  

19. **clear**
    * Clear all previous commands and output fomr consoles and terminal windows
    * Keeps terminal clean and removes clutter
    * _Syntax:_
        * clear
    * _Common Options:_
        * n/a  

20. **cp**
    * Copy files and directories
    * Use when need to back up files
    * _Syntax:_
        * cp [option(s)] current_name new_name
    * _Common Options:_
        * -r
        * -i
        * -b  
        
21. **kill**
    * Allows you to terminate a process from the command line  
        * By providing the PID (process ID) of the process to kill  
        * To find PID:
            * use the ps command accompanied by options -aux
    * _Syntax:_
        * kill [signal or option(s)] PID(s)
    * _Common Options:_
        * -p  

