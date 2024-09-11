Repository is a collection of code snippets, scripts, configuration files associated with the AVEVA PI System.

None of these files are endorsed by AVEVA. Use as your own risk.

- Enum ISO-3166 Country Names.xml
  Enumeration set for Asset Framework that contains country names as per ISO-3166.

- Get-PIPointAnalysis.ps1
  AFSDK PowerShell script to analyse PI Points and categorise as:
    - New: PI Point has no good data, but was created recently
    - Empty: PI Point has no good data ever
    - Stale: PI Point has no good data recently
    - Good: PI Point has good data recently
 
