<h1>Powershell bulk domain lookup script</h1>


Get-Content <path of domain list> | Resolve-DNSName -Type <Type of lookup (NS,A,MX)> -DnsOnly | Out-File -FilePath <path of where you want the results saved>

Ex. 

Get-Content C:\Users\User\Desktop\domain-list.txt | Resolve-DNSName -Type NS -DnsOnly | Out-File -FilePath C:\Users\User\Desktop\result.txt



