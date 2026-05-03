Technical Utilities
Forensics Windows Python

A tool specfically made to make PC Checkers / Screensharers Life Easier

Path Scanner
file analysis and detections

Features
Feature	Description
Hash Extraction	Extracts SHA1 hashes from target files
PE Analysis	Entropy calculation and section analysis for Windows PE files
YARA Integration	Custom rules made by me with 20+ detection rules across multiple categories
Amcache Integration	Parses Windows Amcache data for file replacement detection (if picked default path to scan)
SRUM Analysis	Extracts application runtime and focus time data from SRUM
Output Format
CSV Export Contains:
├── File signatures and hash comparisons
├── Entropy analysis of PE sections  
├── YARA rule matches
├── SRUM runtime statistics
├── File replacement indicators
└── MAC timestamp information
Bypass Generic Checks
Generic Bypass detections so you wont have to look for these!

Features:
Event Log Scanning
DLL Usage Analysis  
Scheduled Tasks
Registry Autorun Keys
Mounted Devices
Prefetch Analysis
Modified Extensions
External Execution from other drives
Recent Files
PE Injection
BAM Analysis
Files Executed from Archives
AnyDesk file transfer analysis
File Modifications
Ghost Deletions
Attribute Manipulation
Self Destruct Patterns
Output
Location: C:\Bypass_generics.csv
Results exported to CSV format for you to use Timeline Explorer with.

Tool Downloader
Automated deployment of essential forensic tools

Included Tools
Tools
More Tools!
Even More!!!
Yes, There is more...
Installation Process
# The installer will automatically:
1️⃣ Create C:\SS base directory
2️⃣ Download all tools to individual folders  
3️⃣ Extract archives automatically
4️⃣ Run initial analysis commands where configured
5️⃣ Clean up temporary files
Output Structure
C:\SS\
├── AmcacheParser/
├── ShimCache/
├── SystemInformer/
├── WinLiveInfo/
├── MFTECmd/
└── [Additional tool directories...]
Each tool generates forensic artifacts and CSV's in their respective folders under C:\SS\

Requirements
Windows 10/11
Administrator privileges
Active internet connection for tool downloads
🤝 Contributing
Contributions are welcome! Please feel free to contribute by messaging @txchnology on discord and i will take your ideas to consideration!
