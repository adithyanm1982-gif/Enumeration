# Enumeration

# Explore Google hacking and enumeration 

#### Developer: ADITHYA NM
#### Reg No: 212225040011

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:







##dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:

#### 1. site
<img width="1148" height="910" alt="site" src="https://github.com/user-attachments/assets/2f2bbc58-af98-4dca-bf28-aed4153fda2a" />

#### 2. filetype
<img width="1148" height="909" alt="filetype" src="https://github.com/user-attachments/assets/4cd3dab7-b737-4f7d-9455-da1c89192e5f" />

#### 3. intext
<img width="1151" height="912" alt="intext" src="https://github.com/user-attachments/assets/069d68c0-ee65-4039-a1a6-cb04d89722fc" />

#### 4. inurl
<img width="1149" height="911" alt="inurl" src="https://github.com/user-attachments/assets/5b29db7a-ebbf-4242-8dc1-172ef37ef009" />

#### 5. intitle
<img width="1148" height="909" alt="intitle" src="https://github.com/user-attachments/assets/510553d3-3946-4ced-a08b-5aae680d8fba" />

#### 6. link
<img width="1151" height="910" alt="link" src="https://github.com/user-attachments/assets/102e9542-e5ca-4bad-a801-80e58eba2447" />

#### 7. cache
<img width="1151" height="914" alt="cache" src="https://github.com/user-attachments/assets/bde1d194-b4be-416a-9a4e-1d9402d843cd" />

### DNS Enumeration

#### 8. DNS Recon
<img width="1920" height="844" alt="dnsrecon" src="https://github.com/user-attachments/assets/063c75df-4590-427e-a11e-b2539656cdbc" />

#### 9. dnsenum

#### 10. smtp-user-enum

#### 11. Telnet

#### 12. nmap –script smtp-enum-users.nse <hostname>


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

