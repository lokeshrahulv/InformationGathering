# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:


Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

### Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:
Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![238300689-505c1008-6602-4c30-a18f-a19831193609](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/fb76804c-c992-4d56-8fbe-8c5ec8c34fc3)

### Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![238300810-18c141eb-f997-4e6a-970b-1278bf0f085f](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/3710ffce-dc91-44a2-8f22-dcfd708decdb)

### Finding Hosting Company
get further detail by using ip2location.com website.

## Output:
![238302790-ad2a8edd-7197-44ae-9f54-94375c7114a9](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/271f8b7c-ec21-4604-9364-b059382e01c4)

## History of the website:
## Output:
https://web.archive.org/
![238300893-192a1d85-246e-45ad-bcd0-0a70e209c601](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/972e2c37-854d-46e8-982e-59377809f140)
```
nc 172.17.52.118 80
```
![238301333-7c38b307-51d1-45b5-85ec-751ed930ba9b](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/aec33bb3-b28a-40bf-b155-1b306ac84b31)

### nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![238301531-4631c0fd-1296-4c74-82fa-8950c48c5a61](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/7846d02a-d57c-4251-a69c-e5c2ba004910)

### Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![238301746-ab6e52ed-b1c2-4c7c-b4cb-edc75d6de5e6](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/dd8cb805-d673-40e9-b304-7817edeee009)
![238302016-3daa0d6f-df5d-4571-bf8b-c2fe63bbc3cc](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/0c41bc61-bc14-4bb5-93db-ba1fb1faf177)
### httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![238301937-a70e6db5-d324-4bee-80f9-9dfdf9b37338](https://github.com/lokeshrahulv/InformationGathering/assets/118423842/9b334d11-7989-43c2-98ab-a0925218bd7c)

## Tracing the Location
### TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in
## Webserver Fingerprinting:
### Netcat:
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
