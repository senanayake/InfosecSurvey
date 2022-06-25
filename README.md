# InfosecSurvey

This is a survey of information security resources that I have collated     

## Useful links

### 
Stride threat modelling - 

Spoofing - 
Tampering
Repudiation
Infomation Disclosure – Only show the information necessary
Denial of Service
Elevation of Privelege


Azure API management 
https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts




OSINT ( Open Source Intelligence )

OSINT Phone number information recon
https://github.com/sundowndev/phoneinfoga

Tools to build phishing attacks
https://www.youtube.com/watch?v=u9dBGWVwMMA




https://inteltechniques.com/book1.html

https://www.hackers-arise.com/osint
https://www.hackers-arise.com/osint-course

Juice shop capture the flag.
https://pwning.owasp-juice.shop/part1/ctf.html


Lock picks 
https://hackerwarehouse.com/lock-picks/


Nahemsec 
https://www.youtube.com/watch?v=9vaEwycet90


Certificate authorities
https://certificate.transparency.dev/howctworks/

Driftwood: Know if private keys are sensitive
https://trufflesecurity.com/blog/driftwood


https://www.hackerone.com/
https://www.yeswehack.com/
https://www.bugcrowd.com/products/attack-surface-management/

Bug Bounty 
https://www.intigriti.com/



Docker HAcking
https://www.hacker101.com/sessions/docker_hacking


Certificate search for ameriprise.

https://crt.sh/?q=%25.ameriprise.com

https://crt.sh/?O=ameriprise
Can be output in json

Send requests via python

https://www.python-httpx.org/

Channels 
https://www.youtube.com/liveoverflow

STOK
https://www.youtube.com/channel/UCQN2DsjnYH60SFBIA6IkNwg

https://www.youtube.com/c/FarahHawa
https://www.youtube.com/channel/UC0ArlFuFYMpEewyRBzdLHiw

AssetNote - 
Attack exposure
https://assetnote.io/

https://www.pentesterlab.com/exercises

11 strategies of a world class SOC
https://www.mitre.org/sites/default/files/publications/11-strategies-of-a-world-class-cybersecurity-operations-center.pdf





Stanford advanced cybersecurity program
https://online.stanford.edu/programs/advanced-cybersecurity-program

CISSP
https://www.udemy.com/topic/cissp/


OWASP Cheat sheet
https://cheatsheetseries.owasp.org/cheatsheets/Threat_Modeling_Cheat_Sheet.html

Threat dragon.
https://owasp.org/www-project-threat-dragon/


Currently looking into 

Password cracking
https://tryhackme.com/room/johntheripper0
Encryption
https://tryhackme.com/room/encryptioncrypto101


Lists used during security assessments:
https://github.com/danielmiessler/SecLists

Open source java static analysis
https://spotbugs.github.io/



AI Fuzzing  – mining for Zero days.
https://threatpost.com/using-fuzzing-to-mine-for-zero-days/139683/

AI Attack graph
https://attackiq.com/2022/02/24/preparing-for-russian-state-sponsored-cyberthreats-to-u-s-and-allied-critical-infrastructure/


Solving cybersecurity as an economic problem
https://www.youtube.com/watch?v=g78yngpg9b0

Stanford web security notes
https://web.stanford.edu/class/cs253/

How website work:
https://tryhackme.com/room/howwebsiteswork



Availabilty
Gremlin - chaos engineering : https://www.gremlin.com/

Why are FAANG interviews hard
https://www.youtube.com/watch?v=ePF1BjGWQ5Y

Develop APIs on Microsoft.  https://docs.microsoft.com/en-us/learn/browse/


https://azure.microsoft.com/en-us/services/api-management/




Firing Range 
Deliberate vulnerability examples
http://www.security-scanner-firing-range.com/



Recon tools:

https://www.youtube.com/watch?v=YT5Zl2jW3wg


https://docs.google.com/presentation/d/1xgvEScGZ_ukNY0rmfKz1JN0sn-CgZY_rTp2B_SZvijk/edit#slide=id.g4052c4692d_0_0


Rengine
https://yogeshojha.github.io/rengine/#quick-installation
https://github.com/yogeshojha/rengine

PRetty recon
https://prettyrecon.com/#features

Recon-ng
https://www.kali.org/tools/recon-ng/

REconFTW
https://github.com/six2dez/reconftw

OSINT Instagram
https://github.com/NextKool/Osintgram

https://github.com/aboul3la/Sublist3r


https://github.com/Dhayalan96/enumall



Pattern Languages

What would a pattern language for secure development look like?
https://en.wikipedia.org/wiki/Pattern_language


TLA+ Prooving things

https://lamport.azurewebsites.net/video/videos.html



[Link OWASP Code review guide](https://owasp.org/www-project-code-review-guide/assets/OWASP_Code_Review_Guide_v2.pdf)

 It is vitally important that our approach to testing software for security issues is based on the principles of engineering and science. We need a consistent, repeatable and defined approach to testing web applications. A world without some minimal standards in terms of engineering and technology is a world in chaos.

 The initial responsibility for application security must fall on the shoulders of the developers because they write the code. It shouldn’t be a surprise that developers aren’t producing secure code if they’re not testing for it or consider the types of bugs which introduce vulnerability.
[Link The OWASP Testing project ](https://owasp.org/www-project-web-security-testing-guide/stable/)


# Code Injection
[Code Injection](https://en.wikipedia.org/wiki/Code_injection) is a category of system exploitation where code is input into the system to produce unintended system results. The "unintended system result" is only unintended in the mind of the system designer. For the attacker, this is an opportunity to bend the system to their will in order to achieve their objectives.
For a code injection vulnerability to occur, the following must be true:
* there must be a way for the attacker to introduce the code into the system with it being blocked.
* the code must travel through the system to an execution environment where it executed by an interpreter.

Defensive mindset.
* The system design should highlight every execution site in the system and the format(s) of code understood by that execution site.
* If the execution site isn't needed, then turn it off. Consider a simpler technology if the execution site can't be turned off.
* Map all the possible flows through the system from input site to execution site.
* Implement code blocking approaches and design+implementation choices to stop an injected code making it 

There are different forms of code injection that are particular to the system design. 


# XSS - Cross site scripting.
