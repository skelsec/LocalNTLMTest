# LocalNTLMTest
Tool to acquire netNTLM hashes on a local machine wihtout network traffic

# Description
This script is using the Windows [SSPI API](https://msdn.microsoft.com/en-us/library/windows/desktop/aa380493(v=vs.85).aspx) 
to emulate a network logon with NTLM protocol and print out the hashes in a crackable form.
It will try to perform authentication on muiple versions of the NTLM protocol, so you can use it to test the current workstation configuration as well.  
No actual network traffic is generated.  
I'm not sure wether it will generate logs.


# Prereq
1. Only works with python >= 3.6
2. No additional packages needed

# Releases
There is a freezed exe made with pyinstaller in the [releas tab](https://github.com/skelsec/LocalNTLMTest/releases)
