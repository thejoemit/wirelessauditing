# Wireless Auditing
A collection of customed automated wireless auditing scripts.

This repo was made to automate the collection and recovery of WPA2-PSK EAPOL handshakes broadcast over the 2.4Ghz Wi-Fi channels using various methods. 

The functions use and require the aircrack-ng suite of tools, and is to be used for educational purpose and pursuets.

These scripts are tested in a wireless lab and have proven effective when launched from debian based distros.

To set up your own wireless lab you will require a linux machine running debian linux, 2 wnics (1 capable of monitoring),
1 wireless ap and you should be able to set it up in such a way that 1 wic connects to the ap while the other captures the EAPOL.

# Legal Disclaimer
In no script nor function have there been made attempts to gain what is known "unauthorized" use to any computer/account/PSK system through any means. Access would be considered made when an association or authentication request to the system was successfully interpreted by the system as a authorized attempt granting the unauthorized party access.

In terms of computer access, a excerpt from Canadian Law - Criminal Code:

"Unauthorized use of computer
    342.1 (1) Everyone is guilty of an indictable offence and liable to imprisonment for a term of not more than 10 years, or is guilty of an offence punishable on summary conviction who, fraudulently and without colour of right,
        (a) obtains, directly or indirectly, any computer service;
        (b) by means of an electro-magnetic, acoustic, mechanical or other device, intercepts or causes to be intercepted, directly or indirectly, any function of a computer system;
        (c) uses or causes to be used, directly or indirectly, a computer system with intent to commit an offence under paragraph (a) or (b) or under section 430 in relation to computer data or a computer system; or
        (d) uses, possesses, traffics in or permits another person to have access to a computer password that would enable a person to commit an offence under paragraph (a), (b) or (c)."

Under Section 342.1.(1).(d), where the scripts may be interperated as "permits another person to have access to a computer password", the argument is that it permits a computer system temporary access to that password, not a person, for educational relevance, to which the key-string was never disclosed a human person without code manipulation unknown to the author. 

In terms of communications, a excerpt from Canadian Law - Criminal Code:

"184. (1) Every one who, by means of any electro-magnetic, acoustic, mechanical or other device, wilfully intercepts a private communication is guilty of an indictable offence and liable to imprisonment for a term not exceeding five years."
...
"Saving provision
  (2) Subsection (1) does not apply to:
  (c) a person engaged in providing a telephone, telegraph or other communication service to the public who intercepts a private communication,
    (i) if the interception is necessary for the purpose of providing the service,
    (ii) in the course of service observing or random monitoring necessary for the purpose of mechanical or service quality control checks, or
    (iii) if the interception is necessary to protect the person’s rights or property directly related to providing the service;"

Any private communications intercepted are in accordance with 184.(2).(c).(ii) 

Furthuring the communications law, another excerpt from Candian Law - Criminal Code:

"193. (1) Where a private communication has been intercepted by means of an electro-magnetic, acoustic, mechanical or other device without the consent, express or implied, of the originator thereof or of the person intended by the originator thereof to receive it, every one who, without the express consent of the originator thereof or of the person intended by the originator thereof to receive it, wilfully
  (a) uses or discloses the private communication or any part thereof or the substance, meaning or purport thereof or of any part thereof, or
  (b) discloses the existence thereof, is guilty of an indictable offence and liable to imprisonment for a term not exceeding two years."
Exemptions
(2) Subsection (1) does not apply to a person who discloses a private communication or any part thereof or the substance, meaning or purport thereof or of any part thereof or who discloses the existence of a private communication
(a) in the course of or for the purpose of giving evidence in any civil or criminal proceedings or in any other proceedings in which the person may be required to give evidence on oath;
(d) in the course of the operation of
  (i) a telephone, telegraph or other communication service to the public,
  (ii) a department or an agency of the Government of Canada, or
  (iii) services relating to the management or protection of a computer system, as defined in subsection 342.1(2),
if the disclosure is necessarily incidental to an interception described in paragraph 184(2)(c), (d) or (e);
(e) where disclosure is made to a peace officer or prosecutor in Canada or to a person or authority with responsibility in a foreign state for the investigation or prosecution of offences and is intended to be in the interests of the administration of justice in Canada or elsewhere; or
(f) where the disclosure is made to the Director of the Canadian Security Intelligence Service or to an employee of the Service for the purpose of enabling the Service to perform its duties and functions under section 12 of the Canadian Security Intelligence Service Act."

Any private communications recorded is displayed in accordance with 193.(2).(d).(i). 

The author is not liable for any unauthorized access or breach of secure networks as a result of using these scripts or any form of damages sought after. All users are to be in accordance with local laws governing radio transmissions and privacy of communications. The user accepts causation of any action preformed by any script authorized by this repo. The author envokes:

"188.2 No person who acts in accordance with an authorization or under section 184.1 or 184.4 or who aids, in good faith, a person who he or she believes on reasonable grounds is acting in accordance with an authorization or under one of those sections incurs any criminal or civil liability for anything reasonably done further to the authorization or to that section."

BOTTOM LINE: AUTHORIZATION IS REQUIRED ON CHANNEL TO EXECUTE A SCRIPT & IT'S YOUR RESPONSIBILITY!

# Creative Commons License
This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

You accept and agree to be bound by the terms and conditions of this Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ("Public License"). To the extent this Public License may be interpreted as a contract, You are granted the Licensed Rights in consideration of Your acceptance of these terms and conditions, and the Licensor grants You such rights in consideration of benefits the Licensor receives from making the Licensed Material available under these terms and conditions.

You may read the summarized license at: https://creativecommons.org/licenses/by-nc-sa/4.0/

You may read the full license at: https://github.com/thejoemit/wirelessauditing/blob/master/LICENSE.md
