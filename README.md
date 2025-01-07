# Anti-Forensisc-Techniques
# Anti-Forensic Techniques Investigation

## Overview
This project explores the anti-forensic techniques used by a cybercriminal who exploited job seekers' data and sold it on the dark web. It is based on an investigation conducted by the **VEEW Intelligence Team**.



## Case Overview
- **Project Title:** Anti-Forensic Techniques Investigation
- **Case:** CASE 201
- **Context:** The case investigates how advanced anti-forensic techniques were used to obscure illegal activities and the methods deployed to counter these techniques.

### Key Statistics
- According to the African Development Bank, Africa has about **420 million youth**.
- One-third of this population is unemployed and discouraged, while another third is vulnerably employed.



## Investigation Steps

### Volatile Data Collection
Commands used:
- `netcat -aon` – Capture active network connections and listening ports.
- `ps` – List running processes.
- `route -n` – Extract routing data.

### Tools Used by the Criminal
- **Secure Deletion:** `srm`, `dd`
- **Data Hiding:** `steghide`
- **Encryption:** Various obfuscation techniques
- **Network Anonymity:** Tor Browser, Incognito Mode



## Findings

### Secure Deletion and Disk Wiping
- Despite secure deletion with `srm`, fragments of sensitive data were recovered using `foremost`. Recovered data included:
  - Facebook login details
  - CVV card details
  - Malicious scripts
- [Video Demo](https://youtu.be/WMrI-AVyQcY?si=hmAEuUtQouLOuLOI)

### File Hiding and Obfuscation
- **Hidden Files:** Uncovered using `ls -a`.
- **Obfuscated Scripts:** De-obfuscated using online tools to reveal malicious code.
- [Image Resource](https://www.digitalguardian.com/)

### Steganography and Encryption
- Steganographic techniques detected and decrypted using tools and decryption keys retrieved during the investigation.

### Network Activity
- Use of VPN services (Vpnbook, Proton VPN) and Tor Browser to mask online presence and sell stolen data on dark web forums.

### Browser Activity
- Browser artifacts were uncovered using tools like:
  - `Dumpzilla`
  - `SQL Database Browser`
  - `Bulk_Extractor`
- Findings included session cookies, hashed passwords, and evidence linking the suspect to dark web activities.
- [Video Demo](https://drive.google.com/file/d/1R3_Cs6POwUEwV0PJnwIxyoAjofsvZpHD/view?usp=sharing)



## Recommendations

### For Job Seekers
1. Verify job offers before sharing personal information.
2. Use strong passwords and be vigilant against phishing scams.
3. Stay informed about online security best practices.

### For Employers
1. Limit data collection to what is necessary.
2. Strengthen cybersecurity measures.
3. Train staff on cyber threat awareness.



## References
1. African Development Bank (2016). [Job creation for youth in Africa](https://www.afdb.org/fileadmin/uploads/afdb/Images/high_5s/Job_youth_Africa_Job_youth_Africa.pdf).
2. S. Pokharel, “Browser forensic with Dumpzilla on Linux and Windows,” Medium. [Read more](https://medium.com/@shirishpokharel/browser-forensic-with-dumpzilla-on-linux-and-windows-cef805126a1).



## Thank You!
#Victoria Simon Omaojo
The Cyber Catalyst
