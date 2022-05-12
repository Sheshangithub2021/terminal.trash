# terminal.trash
While learning cli - ( command line interface or TERMINAL ) 
we delete the files while using terminal but it cant easy recovery deleted files
its not big problem in gui - ( graphical user interface ) because there is trash or recycle bin 
So in created a simple script for storing the deleted files 
Name of the folder is .garbage_collector
it will create  hidden folder automatically while runing script  in the home directory 
whenever you deleting files using this srm script the files will store in .garbage_collector folder in your home dir
after you download the script run the below command - (if its not in executable mode) 
              chmod +x srm
after this you go to root user after . Copy the srm script and paste it in  /bin directory 
when ever using srm command to delete file it will store the deleted file in .garbage_collector 
            Eg:~srm $file or dir name
whenever you using sudo to create file or dir / also to use prefix sudo to srm 
            Eg:~ sudo srm $file or dir 
            
            
