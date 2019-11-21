<h1>Powershell bulk domain lookup script</h1>


Get-Content "Source of text file" | Resolve-DNSName -Type NS -DnsOnly | Out-File -FilePath "Where to save the results"

