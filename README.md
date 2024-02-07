<h1>Suspicious File Hash</h1>

<h2>Description</h2>
I was given a file hash and instructed to determine if it’s a malicious file based on the evidence gathered on the VirusTotal (OSINT) website, as well as finding different types of IOC’s associated with this file.
<br />
<br />
SHA256 file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b

<h2>1. Entered hash file into VirusTotal website</h2>

![IMG_7186](https://github.com/wilsonmantilla/VirusTotal/assets/159208489/1e833a99-e830-4a14-8774-e8e33429fc09)


<h2>2. Analyzed VirusTotal Report</h2>

- This file has is known as malware Flagpro, commonly used by the threat actor BlackTech
- This information was found in the “Detection” and “Community” tabs

![IMG_7187](https://github.com/wilsonmantilla/VirusTotal/assets/159208489/2bb87a54-43d4-4376-ab63-f37ab7f5a729)

<h2>3. Determined that hash file is malicious</h2>
 
- When looking at the summary, 58/72 vendors have flagged this file as malicious. 

![IMG_7189](https://github.com/wilsonmantilla/VirusTotal/assets/159208489/c77698e5-225c-4e90-ac07-56bdc34d239b)

<h2>4. Located IOC's</h2>

- Domain: http://org.misecure.com/index.html (this domain was detected as malicious under the “Relations” tab)

![4](https://github.com/wilsonmantilla/VirusTotal/assets/159208489/37e9f13f-a2ae-44bb-90fd-0e0b069fbb4b)


- IP address:104.115.151.81 (detected as one of the many IP addresses associated with this file. Listed under “Relations”)

![5](https://github.com/wilsonmantilla/VirusTotal/assets/159208489/f4a1b806-e920-4882-a190-01c529b9ccdb)



- Hash value:287d612e29b71c90aa54947313810a25 is an MD5 hash value pertaining to this file. Found in the “Details” tab)

![6](https://github.com/wilsonmantilla/VirusTotal/assets/159208489/0f3ee65a-33ad-49a6-8420-71978f9f9410)

