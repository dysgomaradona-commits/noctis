NOCTIS v0.6 — English Localization

Overview

NOCTIS v0.6 introduces full English localization across the project, replacing Arabic user-facing messages, command descriptions, and module text with English.

The goal is to make NOCTIS more accessible to an international audience.

Localization Changes

- Translated 116 lines across the reported project files.
- Removed Arabic characters from Python (".py") source files.
- Updated command descriptions and startup messages.
- Updated module output messages and tool descriptions.
- Updated the project banner version to v0.6.
- Preserved the existing 14-command structure and automation workflow.

Updated Files

File| Changes
"noctis.py"| Command descriptions and quick-start message
"core/banner.py"| Version updated to 0.6
"modules/recon.py"| DNS, ports, and WHOIS messages
"modules/webhunter.py"| Scanning and testing messages
"modules/sql.py"| Option descriptions and sqlmap messages
"modules/dir.py"| Wordlist and extension descriptions
"modules/sub.py"| subfinder and httpx messages
"modules/port.py"| Nmap descriptions
"modules/scan.py"| Full scan workflow descriptions
"modules/intel.py"| Intelligence-gathering descriptions
"modules/logic.py"| IDOR/BOLA descriptions
"modules/brain.py"| Decision engine descriptions
"modules/report.py"| HTML report text
"modules/phone.py"| Phone intelligence descriptions
"modules/waf.py"| WAF and encoding descriptions
"tools/facesheet.py"| Face and name investigation interface
"tools/linksheet.py"| Investigation interface
"tools/phoneintel.py"| Phone intelligence tools
"tools/webhunter.py"| Standalone WebHunter version

Final Verification

According to the supplied release notes:

- 14 commands with English descriptions.
- No Arabic characters in Python source files.
- Syntax verification: ALL SYNTAX OK.
- Archive: "noctis-v0.6.tar.gz"
- Archive location: Downloads.

Version Comparison

Version| Language| Modules| Automation
v0.3| Arabic| 2| No
v0.5| Arabic| 14| Yes
v0.6| English| 14| Yes

Release

NOCTIS v0.6 — English Localization

This release focuses on international accessibility and consistent English-language output while retaining the existing modular architecture.
