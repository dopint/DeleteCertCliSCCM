@echo Off
net stop CcmExec
sleep 5
Reg Delete HKLM\software\Microsoft\Systemcertificates\SMS\Certificates /f
DEL c:\Windows\SMSCFG.ini
sleep 5
net start CcmExec
