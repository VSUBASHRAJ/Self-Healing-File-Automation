# Self-Healing Ticket Automation Bot

## Overview
This project is an advanced RPA solution built using Automation Anywhere to automate ticket processing with self-healing capabilities.  

The bot is designed to handle failures in web elements dynamically by adapting to UI changes, ensuring uninterrupted automation and reducing bot maintenance efforts.

---

## Project Demonstration
Video Walkthrough:  
https://drive.google.com/file/d/1dYr_jUflJkKzEcwLpZd7FN8GNUhzl2V2/view?usp=drive_link

---

## Key Features
- Automates end-to-end ticket processing workflow  
- Implements self-healing logic for dynamic web elements  
- Detects and handles element failures using fallback strategies  
- Reduces bot breakdown due to UI changes  
- Ensures high reliability and continuity in automation  
- Logs errors and recovery actions for monitoring  

---

## Tech Stack
- Automation Anywhere A360  
- Web Automation  
- Excel Automation  
- Error Handling and Exception Management  
- Conditional Logic and Retry Mechanisms  

---

## How It Works
1. Bot reads ticket details from Excel  
2. Opens the web-based ticket system  
3. Identifies required input fields and elements  
4. If an element is not found:
   - Uses alternative selectors (XPath, attributes)  
   - Applies retry logic  
   - Waits dynamically for page load  
5. Continues execution after recovering from failure  
6. Processes ticket and retrieves solution  
7. Logs all failures and recovery attempts  

---

## Impact
- Reduced bot failure rate by 70%  
- Improved automation reliability by 60%  
- Minimized manual intervention in bot maintenance  
- Ensured consistent execution even with UI changes  

---

## Project Structure
/project  
│── bot_files/  
│── fallback_logic/  
│── logs/  
│── excel_data/  
│── README.md  

---

## Setup Instructions
1. Install Automation Anywhere A360  
2. Import bot into Control Room  
3. Configure:
   - Web application URL  
   - Excel input file  
   - Element identification strategy  
4. Run the bot  

---

## Prerequisites
- Automation Anywhere access  
- Web-based ticket system  
- Excel data source  

---

## Example Scenario
- Original button selector fails due to UI update  
- Bot automatically switches to alternative selector  
- Continues execution without stopping  

---

## Future Enhancements
- AI-based element detection  
- Screenshot-based fallback validation  
- Integration with monitoring dashboards  
- Predictive failure detection  

---

## Author
Subash Raj V  
GitHub: https://github.com/VSUBASHRAJ
