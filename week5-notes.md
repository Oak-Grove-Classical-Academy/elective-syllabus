# Week 5 Notes

## Cracker

The code is available on Github, as before,
[at this link](https://github.com/Oak-Grove-Classical-Academy/cracker). See Week 2's
 notes on how to clone it, but you can just browse it here if you wish.

## CTF

After scanning the CTF site with nmap (`nmap ctf.alltohim.io` or, to make sure you scan all the ports, `nmap -p1-65535 ctf.alltohim.io`), we found that port 777 was open.
Accessing that in the browser with `https://ctf.alltohim.io:777` gave us a new website with a download link for a binary. If you open that in any text editor and search 
for the flag wrapper `og{`, you'd find the flag. You can also use the `strings` command to just get the strings.

## Useful Reading

- [HaveIBeenPwned](https://haveibeenpwned.com/)
- [Crackstation wordlist](https://crackstation.net/)
