# Fix exception: cannot be loaded because running scripts is disabled on this system
1. Set-ExecutionPolicy RemoteSigned

# Add path in Env
2. $env:Path += ';c:\Important Executables' 
