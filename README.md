# sshct
this is a manage .ssh/config cli tool  
it's need egrep  Perl regular expressions method ,  
## so if macos user must run:  
```
brew  install grep  
export PATH=/usr/local/opt/grep/libexec/gnubin:$PATH  
```  
and add export to ~/.bash_profile  
  
## how to start
```
mv sshc /usr/local/bin/  
```  
add 3 line on ~/.ssh/config  
```
Host *
Compression yes
  
```  
sshc -h  
  
## start use it
