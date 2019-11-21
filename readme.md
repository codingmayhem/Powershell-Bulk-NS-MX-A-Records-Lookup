<h1>Powershell bulk domain lookup script</h1>


Get-Content "Source of text file" | Resolve-DNSName -Type NS -DnsOnly | Out-File -FilePath "Where to save the results"

Ex. 

Get-Content C:\Users\User\Desktop\domain-list.txt | Resolve-DNSName -Type NS -DnsOnly | Out-File -FilePath C:\Users\User\Desktop\result.txt



