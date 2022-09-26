# Security-Information-and-Event-Management

NOTE: I am working on uploading more details for this project. Thanks for understanding.

- Used custom __PowerShell__ script to extract metadata from __Windows Event Viewer__ to be forwarded to a third party __API__ in order to derive geo-location data 
- Ingested custom logs containing geographic information (latitude, longitude, state/province, and country) with __Log Analytics Workspace__ configurations in __Azure__
- Mapped geographic data in __Azure Sentinel__ with __Custom Fields__ configurations in Log Analytics Workspace 
- Configured Azure Sentinel Workbook to display global attack data __(RDP brute force)__ on world map according to physical location and magnitude of attacks 
