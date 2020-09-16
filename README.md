# Overview
**Technologies Used:**
- Python
  - Dash
- SQL
- Hive/CKP
- Google API

# VDI

# Local
- Go to www.reportbuilder.thefreeosk.com
- Configurate options to generate a Google Slides report
- Submit and go to report and opens up a new tab with the Google Slides doc

**Celery Tasks**
- On Monday of every week, query for all new eligible placements and update the pl_info and item_info files for the GUI
- Grab config files and Query for data on Friday at 2p.m

# Server
- Hosts GUI (Dash app)
- Generates Google Slides Presentations
- Stores historical metrics for each program
- Runs scheduled task (Celery)
- Uploads and retrieves data from FTP

# Slack Bot
