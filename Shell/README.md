# Shell

# Generate-NetApp-PublicCA-SSL.sh
- Takes Let's Encrypt SSL certificates and generates a script to paste in to your NetApp CLI to automatically install the certificate.
- Paths assume you use acme.sh, adjust variables at top of file as needed.

## Gists:
  - [auto-netapp-public-ssl.sh](https://gist.github.com/danielewood/7891aef986f892d94e70af2ea695da97)
  - [auto-netapp-public-ssl-transcript](https://gist.github.com/danielewood/059e6ed7990435da5a90c43002da331e)
  - []()

# misc-powershell
Miscellaneous Powershell scripts

## Check-Sennheiser-Status.ps1
Checks Sennheiser Website for in-stock status of products supplies in $URLs array.

## Check-Sennheiser-Status.xml
Scheduled Task XML for Check-Sennheiser-Status.ps1


## Start-VeeamBackupHV.ps1
- Spawns multiple backup-jobs for Veeam server to then queue by itself
- This lets Veeam manage bandwidth and number of jobs instead of waiting for each job to finish.

