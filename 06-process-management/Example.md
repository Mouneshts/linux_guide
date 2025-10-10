# Example command for Process management


Show processes :
```bash
ps -aux
```
Show a process with a line number, the first command output is sent to the second part: 
```bash
ps -aux | nl
```
Show a process with a line number with a word count, it prints the first cloumn count,
```bash
ps -aux | wc -l
```
Alternative for ps aux is,
```bash
ps -ef
```
#### Note difference b/n ps -ef & ps aux is showing memory utilization on aux

## Kill 


```bash
kill <<PID>> 
```
Before Kill check process on the terminal along with the filter like a matching pattern 
```bash
ps aux | grep java 
```

Kill -3 PID

