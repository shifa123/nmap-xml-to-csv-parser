# Nmap XML to CSV Parser

#Command : python newxmltocsv.py nmapxmloutput.xml  nmapcsv.csv

#Expect output :
rohit@Rohits-MacBook-Pro nmap % cat nmapcsv.csv 
ip,hostname,port,protocol,service,version
192.168.43.213,,22,tcp,ssh,OpenSSH (8.0p1 Debian 6) (protocol 2.0)
192.168.43.213,,80,tcp,http,Apache httpd (2.4.41)
192.168.43.213,,111,tcp,rpcbind, (2-4) (RPC #100000)
192.168.43.213,,9876,tcp,http,Apache httpd (2.4.41) ((Debian))
192.168.43.213,,9999,tcp,ftp,vsftpd (2.0.8 or later)

#Commands used :-
python = Tool
newxmltocsv.py = The Script
nmapxmloutput.xml = XML Output 
nmapcsv.csv = CSV Output


