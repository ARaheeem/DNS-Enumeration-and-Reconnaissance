# DNS-Enumeration-and-Reconnaissance

**Scenario**:
As a penetration tester, you are working to discover weaknesses and vulnerabilities that the client, Structureality, will need to mitigate. You are tasked with finding issues related to domain names and IP addresses that the client believes could be related to attacks or potential vulnerabilities

**Skills shown**:
- WHOIS Analysis: Conducted domain name reconnaissance to extract registrar, contact, and expiration data for asset profiling.
- ARIN Lookup: Researched IP address ownership and network range via Regional Internet Registry to assess attribution and legitimacy.
- IP Reputation Validation: Verifies malicious activity history using AbuseIPDB, supporting threat classification and incident triage.
- DNS Enumeration with nslookup: Retrieves A, MX, NS, and TXT records for domain infrastructure mapping and email/host configuration validation.
- Advanced DNS Interrogation using dig: Performs precise query structuring and record inspection for in-depth protocol and server analysis.

 **Whois Reconnaissance**:
To find out who owns a registered domain name, use a whois service.  The linked firm name, address, phone number, email address, and staff members listed as contact points can also be obtained through this process.
     <img width="539" height="352" alt="image" src="https://github.com/user-attachments/assets/b45e2a0f-4886-4e24-a078-6f2d11d52a69" />
     <img width="530" height="329" alt="image" src="https://github.com/user-attachments/assets/7c85d074-f0e2-433d-a9b4-0f6961d7aa27" />
- Notice many registration values are displayed as "REDACTED FOR PRIVACY" and this often indicates that the registrar is withholding information in regard to the registration details of the domain to protect the PII of personnel at the organization.

**ARIN lookup**:
   <img width="524" height="407" alt="image" src="https://github.com/user-attachments/assets/25b991b5-76e0-43ac-b4f5-f93f4d06078c" />
   <img width="547" height="299" alt="image" src="https://github.com/user-attachments/assets/38b035d7-d2b1-4ff9-9984-b074599cd72a" />
- By doing further research you will learn that M247 is a reputable company that offers Internet services all throughout Europe.  Consequently, this information is not very helpful in identifying the sender of the dubious email.  There is no assurance that the IP address was not spoof, but it does suggest that the source may have been in Paris. Additionally, the first line of "Source Registry" in the ARIN search results shows that the IP address is registered with the RIPE NCC RIR (Regional Internet Registry) instead of ARIN.  From the ARIN header menu, choose About, then Our Region, and finally Regional Internet Registry Regions to see the regional responsibilities for the five RIRs.

**Abuseipdb**:
  <img width="404" height="257" alt="image" src="https://github.com/user-attachments/assets/39d424e9-ac9f-4a9a-a20a-f48c1b4f49d5" />
  <img width="554" height="248" alt="image" src="https://github.com/user-attachments/assets/82da8ea6-1e18-4dae-97e8-b9f39c6a6dc3" />
  <img width="665" height="334" alt="image" src="https://github.com/user-attachments/assets/4c1d5a84-add4-4e88-b8d0-aec6c51d8a68" />
  <img width="650" height="236" alt="image" src="https://github.com/user-attachments/assets/ed91df14-ac83-405a-b6ab-dea1d4d653b5" />
  <img width="593" height="247" alt="image" src="https://github.com/user-attachments/assets/811578e1-eebf-4c8f-8864-8b51830b1169" />







     
