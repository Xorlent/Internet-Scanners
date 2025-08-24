# Internet-Scanners
List of Internet scanner IPs by organization  
Created leveraging [SANS research](https://isc.sans.edu/) data feed  

> [!IMPORTANT]
> Shortly after publishing this list of scanner IPs, the SANS feed no longer includes Stretchoid addresses.  I have contacted SANS for an explanation.

## Instructions
Point your security product/firewall to the following URL as an external threat feed/IP list.  
  
Stretchoid.txt example:  
```https://raw.githubusercontent.com/Xorlent/Internet-Scanners/main/stretchoid.txt```  
  
If your appliance or program does not correctly interpret Windows CR/LF, you can post-process the list with (thanks @jlongua):  
```sed -i "s/\r//g" stretchoid.txt```
