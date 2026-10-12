1. /home/saketh is what Shell printed. It is the current working directory or in simpler words wherever the Terminal is currently running - its gotta be running somewhere. Also in this case, since I see a ~$. The ~ sign means the Path is home.
2. ls -a shows all the hidden .files that are not normally not shown with a just ls command
3. drwxr-xr-x 2 saketh saketh 4096 Aug 27 10:55 Desktop. I think the first column is driver/directory.
4. It didn't work when I tried it while my pwd was coding-cafe/week02 but when I went to home and tried, it did. So in the first case it was Absolute and in the second case, from home, the path was Relative.
5. mv first moved README-backup.md into the folder week01 from coding-cafe. mv used the second time renamed README-backup.d to old-readme.md
6. 20
7. /usr/bin/python3
8. It lives in the same place.
9. Command 'pyton3' not found, did you mean:  command 'python3' from deb python3 (3.14.3-0ubuntu2)
   Try: sudo apt install <deb name>
   pyton3 is unrecognized because its not a directory that exists in the environment PATH variable
10. because .files are hidden files that only show when u list all or ls -a
11. we entered a new virtual environment independent
12. instead of accessing stuff from the global path which can be messy because different versions, packages. we can have a project-specific virtual environment to keep its stuff seperate and clean
13. single pip with version - 1st
    bunch of other stuff as well because we got requests - 2nd
14. /Library/Frameworks/Python.framework/Versions/3.14/bin/python3
15. ls -h is the human readable format i've heard and instead of big numbers for size it shows M for megabytes but in terms of listing for me it shows the same as -l
16. ctrl c terminates ctril d saves
    
    
    