# Risk Register (by Frontline)

Turn the risk spreadsheet nobody opens into a scored, regulator-aligned risk register your board trusts, in minutes. Works in Claude Cowork, Claude Code and the Claude apps.

## What it does

- **Build, clean up or review**: start fresh, fix a messy spreadsheet or SafetyCulture/SAP export, or audit an existing register for gaps
- **Scored properly**: 5x5 matrix (or yours), inherent and residual ratings, hierarchy of controls on every control
- **Critical risks**: flags fatal and life-changing risks and names the critical controls that must never fail, with how to verify them
- **Control gap check**: High/Extreme risks relying on admin or PPE, unverified controls, missing owners, overdue reviews
- **Board view**: inherent vs residual heatmap, top 5 risks and a one-line summary for leadership
- **Multi-site roll-up** when you work across several sites

Supports model WHS laws (AU), WorkSafe Victoria, WorkSafe NZ, US OSHA and UK HSE.

## What you get in v2

- **Real deliverables, not just chat**: a live Excel workbook (formulas, dropdowns, traffic lights), clean charts, and for executives or boards a document you can circulate
- **Numbers you can defend**: every rate calculated in code with the right convention for your jurisdiction (AU/NZ per 1,000,000 hours, US per 200,000 hours)
- **Legal checks built in**: notifiable incident tests and terminology for Australian WHS laws, Victoria, New Zealand, US OSHA and UK RIDDOR
- **Expert reference packs**: fatal risks, critical controls and lead indicators for 12 industries, plus risk and investigation methods

## Try it

Install the plugin, then say "Build a risk register for my civil construction sites" or paste your current register and say "Clean this up and find the gaps". No data? Say "start fresh".

## Make it live

Connect Frontline to keep the register live: site teams update risks from their phones, owners get chased and the heatmap updates itself. https://getfrontline.io

## Privacy

This plugin runs entirely inside your own Claude session. It does not send, store or retain your data anywhere. Privacy policy: https://getfrontline.io/privacy

## Disclaimer

Outputs are a starting point, not legal advice. Check against your own procedures and current legislation, and have a competent person review before relying on them.

## What this plugin runs

The skill includes three readable Python helper scripts in `skills/risk-register/scripts/`: `incident_tools.py` (cleans and summarises the data you upload, using pandas), `charts.py` (draws charts with matplotlib) and `xlsx_builder.py` (builds the Excel output with openpyxl, and if LibreOffice is installed, runs it locally in headless mode to recalculate formulas). They work only on files in your session. They make no network calls and fetch nothing from the internet.
