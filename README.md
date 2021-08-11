# lh-bulk-om-upgrader
Bulk upgrade OM firmware via LH

- Python script for bulk upgrade of OM console server from Lighthouse via CLI
- Requires a smart group to be defined in LH


Notes:
- Edit global variables in lh_bulk_upgrader.py
  - group = 'group1'        # Smart group name in LH 
  - fwVersion = '21.Q2.1'   # Update version
  - fwName = 'file.raucb'   # Update filename

- Edit Lighthouse credentials in creds.py

