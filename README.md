
# Task 1 – Local Network Port Scan
# Tools Used
- Nmap 7.97 (Command Line)
- OS: Windows 11

# Scan Details
Scanned IP: `192.168.0.105` (Local device)

### Open Ports Found:
# Port   Service           Description                    
1) 135   msrpc       -->   Windows RPC                    
2) 139   netbios-ssn  -->   NetBIOS session service        
3) 445   microsoft-ds -->   SMB over TCP                   
4) 3306  mysql        -->   MySQL Database Server          
5) 5432  postgresql   -->   PostgreSQL Database Server     

# Risks Identified
- Windows sharing ports (135/139/445) may expose system if not firewalled.
- Open database ports (3306/5432) can be vulnerable without authentication.

# Files Included
- `scan_result.txt` – Raw scan output
- `README.md` – Task documentation

