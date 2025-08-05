# linux_basics_commands
List of Linux commands essentials for Devops  

Command	Description
pwd	Show current directory path
ls	List files in a directory
cd <dir>	Change directory
mkdir <dir>	Create a new directory
touch <file>	Create a new empty file
cp <src> <dest>	Copy files or directories
mv <src> <dest>	Move or rename files
rm <file>	Delete a file
rmdir <dir>	Remove an empty directory
cat <file>	Display file content
echo "text"	Print text to terminal
man <command>	Show manual/help for a command
clear	Clear the terminal screen

Intermediate Level
    Command	                      Description
    chmod	                        Change file permissions
    chown	                        Change file owner
    grep <pattern> <file>	        Search for text in files
    find <path> -name <file>	    Find files by name
    tar -czvf <archive>.tar.gz <dir>	Compress directory
    tar -xzvf <archive>.tar.gz	  Extract archive
    df -h	                        Show disk space usage
    du -sh <dir>	                Show directory size
    ps aux	                      List running processes
    kill <PID>	                  Terminate a process
    top or htop	                  Monitor system resources
    history	                      Show command history
    alias ll='ls -la'	            Create command shortcut
 Advanced Level
    Command	                      Description
    crontab -e	                  Edit scheduled tasks (cron jobs)
    iptables	                    Configure firewall rules
    ssh user@host	                Connect to remote server
    rsync -avz <src> <dest>	      Sync files/directories
    sed 's/old/new/g' <file>	    Stream editor for text replacement
    awk '{print $1}' <file>	      Pattern scanning and processing
    netstat -tulnp	              Show network connections
    lsof -i	                      List open files and ports
    systemctl	Ma-nage             system services
    journalctl	                  View system logs
    strace <command>	            Trace system calls
    curl / wget	                  Download files from web
    docker / kubectl	            Container and Kubernetes management
