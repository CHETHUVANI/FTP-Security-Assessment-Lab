# FTP Security Assessment

## Target
IP: 10.0.2.8

## Service
FTP - TCP/21
Software: vsftpd 3.0.5

## Finding 1
Title:
Anonymous FTP Login Enabled

Severity:
Medium

Evidence:
Nmap detected:
"Anonymous FTP login allowed"

Impact:
Unauthorized users can access FTP resources.

---

## Finding 2
Title:
Anonymous FTP Upload Enabled

Severity:
High

Evidence:
Anonymous user successfully uploaded test.txt.

Impact:
Attackers can upload unauthorized files.

---

## Recommendation

- Disable anonymous FTP access.
- Use authenticated users only.
- Enable FTPS/SFTP.
- Restrict write permissions.
