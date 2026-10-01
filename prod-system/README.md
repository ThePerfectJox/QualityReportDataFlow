Last error:
```
Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Try the new cross-platform PowerShell https://aka.ms/pscore6

PS C:\Users\USER> cd /qualityreportdataflow
PS C:\qualityreportdataflow> python main.py
1) Loading .env
2) Connecting to MySQL
3) Running query
   50 rows, columns: ['ID GL', 'Nama GL', 'ID PPSKT', 'Nama PPSKT', 'UB [1]', 'UB [2]', 'UB [3]', 'UB [4]', 'UB [5]', 'UB [6]', 'UH [1]', 'UH [2]', 'UH [3]', 'UH [4]', 'UH [5]', 'UH [6]', 'Avg CW [1]', 'Avg CW [2]', 'Start', 'End', 'Tanggal']
4) Writing Excel
   C:\QualityReportDataFlow\reports\2026\october\quality_report_20261001_161046.xlsx
5) Building email
   recipients: ['joshuanehemia.subagyo@sampoerna.com']
6) Sending email
Flow failed: SMTPServerDisconnected: Connection unexpectedly closed
PS C:\qualityreportdataflow> python test/TestEmailManager.py
TEST EMAIL MANAGER
Regex check:
  good@example.com -> True
  bad@@example     -> False
Login: password
No attachment found at C:\QualityReportDataFlow\reports\2026\october\test_users.xlsx (sending without attachment).
Recipients: ['joshuanehemia.subagyo@sampoerna.com']
Could not send email: SMTPServerDisconnected: Connection unexpectedly closed
PS C:\qualityreportdataflow>
```