# EasyFilter
EasyFilter 1.0 - Free UDP Amplification Lists Filter.

# Installation
```wget -O filter.py https://raw.githubusercontent.com/Alemalakra/EasyFilter/master/filter.py && chmod 777 filter.py```

# Usage
```
[!] EasyFilter 1.0 by Alemalakra.
[!] Usage: filter.py <INPUT> <OUTPUT> <PROTOCOL> <MIN BYTES> <OUTPUT SYNTAX>
[!] Protocols: chargen, ntp, quake, ssdp, ldap, dns, snmp, mdns, tftp, portmap, netbios
[!] Output syntax variables: [space], [ip], [bytes]
```

# Sample Usage
```python filter.py ntp_old.txt ntp_filtred.txt ntp 42 [ip][space][bytes]```

# Requeriments
- [x] Python 2.*
- [x] Server offshore (BulletProof, Recommended)
