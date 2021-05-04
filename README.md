# shell-stable-cmd
command for stabling the shell 
it involve three cmd 

 python -c 'import pty;pty.spawn("/bin/bash")'
 
 after using it u will not able to use ctrl^c cmd 
  
  step 2 
  export TERM=xterm
  this cmd will give access to the cmd such as clear 
  
  we will background the shell using Ctrl + Z. 
  Back in our own terminal we use 
  
  stty raw -echo; fg
  
  This does two things: first, it turns off our own terminal echo (which gives us access to tab autocompletes, the arrow keys, and Ctrl + C to kill processes). 
