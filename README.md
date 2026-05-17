# Day-2-DNS-Traffic-Investigation-Wireshark-SOC-Lab-


🎯 Objective

To analyze DNS traffic using Wireshark and understand how domain names are resolved into IP addresses from a SOC analyst perspective.

⸻

🛠 Tools Used
	•	Kali Linux
	•	Wireshark
	•	Firefox Browser
	•	VMware Workstation Player

⸻

📡 What is DNS?

DNS (Domain Name System) translates human-readable domain names (e.g. google.com) into IP addresses used by computers.

⸻

🔍 Investigation Steps
	•	Captured live network traffic using Wireshark
	•	Applied DNS filter to isolate DNS packets
	•	Analyzed DNS query and response packets
	•	Identified domain resolution behavior (A and AAAA records)
	•	Observed CNAME resolution chains

⸻

📊 Key Observations
	•	DNS queries are used whenever a domain is accessed
	•	Some domains resolve through multiple CNAME records
	•	Both IPv4 (A) and IPv6 (AAAA) responses were observed
	•	Some queries included extended domain suffixes indicating possible misconfiguration or internal naming behavior

⸻

🧠 SOC Analyst Insight

DNS traffic is critical in security monitoring. Analysts use DNS logs to:
	•	Detect malicious domains
	•	Identify unusual or unexpected traffic patterns
	•	Investigate malware communication behavior
	•	Analyze phishing or command-and-control activity

⸻

⚠️ Conclusion

This exercise demonstrated how DNS works in real-time and how SOC analysts can use DNS traffic analysis to understand network behavior and investigate potential anomalies.
