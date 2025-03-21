<#
    Powershell for Digital Forensics

    Case 001: Forensic Copy
    Create Example evidence files

    Author: Danyelle Jackson
    Date: 2025-03-21

#>

# Clear the terminal window
Clear-Host 

# Write the terminal window 
Write-Output ""
Write-Output "----------------------------------------------------------"
Write-Output "Starting Case 001 CREATE EVIDENCE script" 
Write-Output "----------------------------------------------------------"
Write-Output "In a PowerShell terminal, run:" 
Write-Output ".\evidence.ps1" 
Write-Output "----------------------------------------------------------"
Write-Output "First, we'll clean up and old evidence" 
Write-Output "" 
Write-Output "----------------------------------------------------------"
Write-Output "      Start CASE 001 UNDO script" 
Write-Output "---------------------------------------------------------" 
Write-Output "      Deleted directory '.\evidence-copy' and any child files."
Write-Output "      Done cleaning up and old evidence" 
Write-Output "---------------------------------------------------------"
Write-Output "Done creating evicence. See new .\evidence subfolder." 
Write-Output "---------------------------------------------------------" 




# df-mod2-forensic-copy 
Get-FileHash -Path .\evidence\1.txt -Algorithm SHA256
Get-FileHash -Path .\evidence\2.txt -Algorithm SHA256
Get-FileHash -Path .\evidence\3.txt -Algorithm SHA256
Get-FileHash -Path .\evidence\4.txt -Algorithm SHA25
Get-FileHash -Path .\evidence\5.txt -Algorithm SHA256
Get-FileHash -Path .\evidence-copy\\evidence\1.txt -Algorithm SHA256
Get-FileHash -Path .\evidence-copy\\evidence\2.txt -Algorithm SHA256
Get-FileHash -Path .\evidence-copy\\evidence\3.txt -Algorithm SHA256
Get-FileHash -Path .\evidence-copy\\evidence\4.txt -Algorithm SHA256
Get-FileHash -Path .\evidence-copy\\evidence\5.txt -Algorithm SHA256
