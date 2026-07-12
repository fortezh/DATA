shel v tejto zlozke

(Get-FileHash -Path battery.ota.bin -Algorithm md5).Hash.ToLower() | Out-File -FilePath battery.md5 -Encoding ASCII