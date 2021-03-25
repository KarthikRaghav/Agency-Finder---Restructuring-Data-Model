## Agency-Finder - Restructuring-Data-Model

# Summary

Restructuring the current data model of the Agency Finder model to prevent creation of redundant program records by the CAS team. 

# Problem Statement

The CAS team is using Agency Finder application in Salesforce to optimize data collection and storage of information about Organizations, Programs and Services. IDS created a data model to store the Agency Finder information in an efficient way. The CAS team currently creates two Program records for a Program that is present in multiple locations. 

When a program has multiple locations, multiple location records need to be created and linked to that particular program instead of creating multiple program records for the same program. This prevents creation of redundant program records.

