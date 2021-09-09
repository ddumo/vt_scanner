# vt_scanner
A tool to check documents against VirusTotal. It will upload the file in question, if it doesn't find the hash in the first check. 
This tool uses VT's API's to streamlines an anylsts work.
Please do not abuse VT's policy of 4 uploads/min.
The tool, as written, will make it difficult to abuse VT's rate policies.

Getting Started.
NOTE: This is currently optimized for Linux, but it works in Windows, as well.

1 - Go to VirusTotal: https://www.virustotal.com/  and get your personal API key
2 - import vt-py with pip install vt-py      or       pip3 install vt-py
3 - Download vt_scanner.py and place it into your preferred directory
4 - Call the program: python3 vt_scanner.py  some.file


If you'd like to make calling this program more simple, make a call function:
1 - chmod+x vt_scanner.py
2 - sudo cp vt_scanner.py /bin/scan    # This will allow you to call the scanner from any directory with the call "scan"

