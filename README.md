# Gobuster-Wordlist-
a .txt containing vast common directories to be used witht the penetration testing tool "GoBuster"

####

'GoBuster" : https://github.com/OJ/gobuster

is a fast and flexible brute-forcing too written in Go 
designed for securtity professionals and penetration testers

one fo its features include:
Web Directory/File Enumeration: Discovering hidden directories and files on web servers


mods targetted in this repo:

🌐 Directory Mode (dir)

Enumerate directories and files on web servers.

Basic Usage:

gobuster dir -u https://example.com -w wordlist.txt

where -u : the actual URL of the website

where -w : the .txt consisting of lists of words to be brute forced 

- in my case, i made a .txt including many common and vastly used hidden directories


disclaimer:

Use responsibly. Don’t be the jerk who scans random websites without permission. This list is for authorized penetration testing and educational purposes only.
