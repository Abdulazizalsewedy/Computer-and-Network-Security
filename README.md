# Fake microsoft login page
Any person can download the fake login page from github and upload it to a live server such as dellen or blue host to get a domain and then send the link to the target to trick the them to loging into the page and get their credetentials 

 
## Severity
Low.
Attacker can get someone's microsoft accont.

## Requirements to reproduce
computer, live server

## Steps to reproduce
1. download the code from github 
2. set up a live server you can use dellen or blue host, note, if you use blue host google might black the website since it has malicious code
3. 
4. get the target contact information like an email or phone number.note, you can use a tool called Maltego to get someone's contact information 
5. send a fake email from microsoft to the target. note, you can use a tool called SETOOLKIT to send the fake email or you can use Spoof Text Message to send fake SMS 

## Mitigation
1. don't open malicious link.
2. always check the domain address and make sure its the right one because some attackers might use the exact domin except for one latter missing compared to the real one.
