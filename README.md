Standalone python 2.7.X exploit for *freeFTPd* versions < 1.0.10. 
Exploit is re-written in Python from Metasploit Ruby [here](https://www.exploit-db.com/exploits/28681).
Tested on Win XP SP3 x86 only.

[Explanatory blog post here](https://ivanitlearning.wordpress.com/2019/09/01/rewriting-a-ruby-msf-exploit-in-python/)

## Usage:

1. Edit `rhost`, `rport` and `ftpuser` in `freeFTPd.py`
2. Replace shellcode `buf`
3. Run with `python freeFTPd.py`
