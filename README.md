# Steve
SOHO Search And Security Buddy

  Steve's a personal project of mine that I'm using as a part of my ongoing study and research into the field of Cybersecurity and Information Assurance. The voice assistant portion stems from a desire to want an assistant that'll do exactly what I tell it to (siri and alexa won't check my network lol), and it allows me to use python and easily implement bash. 

  Steve can do a few things as of now and I'll try to reguarly update his functionalty here. So far I've skipped out on using the PyBrain library so the AI portion of Steve is just a decision tree. 

HARDWARE:
  * Pine64-ROCK64 4GBDDR3 board
  * Alfa AWUSO36NH Wifi Adapter
  * Custom printed honeypot shaped case
  * Movo M1 USB Microphone
  * USHONK USB Mini Speaker (that I took apart and gutted)

SOFTWARE:
  * Armbian
  * Crowie
  * Glastopf
  * Snort
  * ELK
  * Wireshark
  * Nmap
  * Air-mon ng
  * Arp
  * Metasploit
 
Steve's commands:
  * Scans network to see whos on it:
    -Nmap and wireshark
      +Checks unique IP's and MAC addresses
  * Search the internet for me:
    -bash
  * Set an Alarm for me and wake me up:
    -primarily python 
  * Spin up a crowie and kippo honeypot
    -bash
      +logs are stored but accessed via another command
  * Check honeypot logs
     -bash 
      +scans textfiles using grep for relevant information
  * Upload files to Github
     -bash
       +any uploads performed by him can be found here
       
 Currently looking into making him an antivirus, not sure how to check for malware thats running without a pid or piggybacking on some other process... In addition to this I don't think it would be fairly difficult to make a simple IDS out of him either...
      
Steve's code is a mixed bag of code borrowed from outside sources, stuff made from scratch, and code I've found and made alterations to accomodate Steve. Once he's been moved from my PC to his home on the PINE64 I'll post links to the relevant sources. 

A link to an imgur album with Steve will be posted here later:
-link

