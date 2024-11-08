# Wireshark-Phishing-Investigation

## Overview
[Brief Objective - Remove this afterwards]

In this challenge, you will be tasked to analyse the Tactics, Techniques, and Procedures (TTPs) executed by a threat group, from obtaining initial access until achieving its objective. 
Julianne, a finance employee working for Quick Logistics LLC, received an email regarding an unpaid invoice from their business partner, the attached document was malicious and compromised her workstation. The security team was able to flag the suspicious execution of the attachment.

## Objectives

	• What is the email address used to send the phishing email?

	• What is the email address of the victim?

	• What is the name of the third-party mail relay service used by the attacker?

	• What is the name of the file inside the encrypted attachment?

	• What is the password of the encrypted attachment?

	• Based on the result of the lnkparse tool, what is the encoded payload found in the Command Line Arguments field?


	• What are the domains used by the attacker for file hosting and C2? 

	• What is the name of the enumeration tool downloaded by the attacker?

	• What is the file accessed by the attacker using the downloaded sq3.exe binary? 

	• What is the software that uses the file in Q3?

	• What is the name of the exfiltrated file?

	• What type of file uses the .kdbx file extension?

	• What is the encoding used during the exfiltration attempt of the sensitive file?

	• What is the tool used for exfiltration?


	• What software is used by the attacker to host its presumed file/payload server?

	• What HTTP method is used by the C2 for the output of the commands executed by the attacker?

	• What is the protocol used during the exfiltration activity?

	• What is the password of the exfiltrated file?

	• What is the credit card number stored inside the exfiltrated file


### Skills Learned
[Bullet Points - Remove this afterwards]

 
	• LNKParse3 - a python package for forensics of a binary file with LNK extension.
 
	• Wireshark - GUI-based packet analyser.
 
	• Tshark - CLI-based Wireshark. 
 
	• jq - a lightweight and flexible command-line JSON processor.
 
  • PCAP investigations
	

### Tools Used
[Bullet Points - Remove this afterwards]

  • Thunderbird - a free and open-source cross-platform email client.

	• LNKParse3 - a python package for forensics of a binary file with LNK extension.
 
	• Wireshark - GUI-based packet analyser.
 
	• Tshark - CLI-based Wireshark. 
 
	• jq - a lightweight and flexible command-line JSON processor.
 
  • grep, sed, awk

## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*

