Standalone python 2.7.X exploit for *freeFTPd* versions < 1.0.10. Exploit is re-written in Python from Metasploit Ruby [here](https://www.exploit-db.com/exploits/28681).
Tested on Win XP SP3 x86 only.

## Usage:

1. Edit `rhost`, `rport` and `ftpuser` in `freeFTPd.py`
2. Replace shellcode.
3. Run with `python freeFTPd.py`.
