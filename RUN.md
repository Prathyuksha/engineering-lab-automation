## How to Run Automation

### Step 1: Open Chrome
Open Chrome manually.

### Step 2: Open an Engineering College Lab Page
Example:
https://www.tce.edu/academics/departments/civil-engineering/material-test-lab

### Step 3: Attach Browser Relay
Click the Clawdbot Browser Relay extension and ATTACH the tab.

### Step 4: Verify Tab
clawdbot browser tabs

### Step 5: Run Automation
clawdbot agent --local --agent main -m "You are reading an engineering college webpage opened in the browser. Extract ONLY Civil and Mechanical Engineering laboratory details. Collect: college name, department, lab name, list of testing machines, and lab in-charge or contact details if available. Prepare a clean structured report. After preparing the report, send it to WhatsApp."
