# Fake microsoft login page attack 
Anyone can create the fake microsoft login by download the payload using this link https://github.com/JoniRinta-Kahila/microsoft-login-spoofthe and then upload it to a live server such as delenn or web hosting services and then send the link to the target if you are using delenn or domain if you are using web hosting services and when the target open the link and put his credetentials to the fake microsoft login you will be able to get his credetentials and use them to login to his account

be aware that its not enough to to create fake microsoft login page in order for this attack to work, you need some social engineering to convince your target and I think this is the most important step becaue its easy to create payload but its not easy to convince someone to use your paylad so that why you need social engineering and in social engineering you need to get someone contact information because you can use them to send fake emails or SMS

 
## Severity
Medium.
<br />
Attacker can get someone's microsoft accont credetentials and use them to login to his account. and if the attacker gets access to your Microsoft account, he may be able to use your email to reset the passwords for your other accounts, like banking and online shopping.

## Requirements to reproduce
1. payload for ctreating the fake microsoft login page 
2. live server 
3. domain or short url 
4. information gathering
4. feke email or SMS 

## Steps to reproduce
1. download the payload from a github and you can do that by using this link https://github.com/JoniRinta-Kahila/microsoft-login-spoof
2. set up a live server you can use dellen or web hosting services, note, if you use web hosting services chrome might black the website since it has malicious code but if you decide to use dellen you need to download the code there and then go to file called express-password-collector after that run those commands npm install, and then npm run dev to start API
3. domain if you are using hosting services but if you are using delenn you can use short url like https://tinyurl.com/app to make the link that will go to the target less suspicious
4. get the target contact information like an email or phone number, you can use a tool called Maltego to get someone's contact information 
5. send a fake email from microsoft to the target, you can use a tool called SETOOLKIT to send the fake email or you can use spoof text message to send fake SMS 

## Mitigation
1. don't open malicious link or email.
2. always check the domain address and make sure its the right one because some attackers might use the exact domin except one latter missing compared to the real one.
