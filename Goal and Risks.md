# Goal

The goal is to restructure the data model so that when a program is in multiple locations, two location records need to be created and added to the program. This should be done to avoid the creation of redundant program records by the CAS team.

# Risks

1. Referral details of a specific program are currently stored in the Program object.

2. When a Program is in multiple locations, referral details may also vary depending on the location.

3. This problem restricts CAS team from creating a new Location record as Location object does not store the Referral details information.

4. Instead they create a new Program record to store the new Location and Referral detail information


