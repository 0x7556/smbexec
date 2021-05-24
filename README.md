# smbexec

AtExec SMB remote execution command (using SCHTASKS) 

### Usage
```Bash
SmbExec 2.0 by 0x7556
Target: Winver >= 6.0 (Vista)
Home: https://github.com/0x7556/smbexec
Usage:
SmbExec host user pass cmdline
SmbExec host user pass cmdline user
Base64 Cmd:
SmbExec host user pass b64cmd cmdline
SmbExec host user pass b64cmd cmdline user
Example:
SmbExec 10.1.1.10 Administrator 123456 whoami
SmbExec 10.1.1.10 Administrator 123456 whoami user
SmbExec 10.1.1.10 Administrator 123456 b64cmd d2hvYW1p
SmbExec 10.1.1.10 Administrator 123456 b64cmd d2hvYW1p user
```
### 2.0 SmbInfo & base64cmd
![image](https://github.com/0x7556/smbexec/blob/master/SmbExec2.png)

### 1.0 Only cmd
![image](https://github.com/0x7556/smbexec/blob/master/smbexec.PNG)
