
# Test 

Open PowerShell

-c:\
-cd c:\temp\

Download Sample and .ps to c:\temp

at prompt
'PS C:\temp>'

Run

'& "C:\temp\Ajoneuvorekisteri-Parse Modern XK Range.ps1" .\Ajoneuvorekisteri-Parse Modern XK Range-sample.txt'

# Read deal
Download Traficom Tieliikennedata dump from https://tieto.traficom.fi/fi/avoin-data 
and extract it to c:\temp\ 
file name is like: .\TieliikenneAvoinData_30_06_2026.csv

# Edit Script parameters to match wanted car model

Run modified script against to data dump

'& "C:\temp\Ajoneuvorekisteri-Parse Modern XK Range.ps1" .\TieliikenneAvoinData_30_06_2026.csv'

You see progress
'Scanned lines: 515761    Matches: 13'

There are some 5 Million lines, so it takes a while...