[README.md](https://github.com/user-attachments/files/26107180/README.md)
# Company Intelligence Layer

Internal talent sourcing tool for Zapier's TA team.

Scans any company and returns:

- Full tech stack fingerprint
- Real named engineers to source (pulled from GitHub, blog bylines, conference talks)
- Outreach angles and LinkedIn profiles
- LinkedIn Boolean search strings tuned to the target role
- Sourcing context framed around Zapier's zone model and AI-first direction

## How to use

1. Open the tool at the GitHub Pages URL
2. Enter a company name
3. Optionally select a **role type** (e.g. Backend Engineer, SRE, Applied AI Engineer, Engineering Manager) and **level** (IC3–IC5, M3–M4)
4. Click **Generate Prompt**
5. Copy the prompt and paste it into Claude chat
6. Copy Claude's full response, paste it back into the tool, and click **Render Report**

Adding a role type and level focuses the research on the right signal sources for that type of engineer — blog bylines for SREs, SDK/API repo credits for backend engineers, conference circuits for AI engineers, etc. Without them, the scan runs a general sweep.

## How to update

Replace `index.html` with the latest version from Claude.
