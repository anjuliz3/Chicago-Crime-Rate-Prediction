# Chicago-Crime-Rate-Prediction
Model to predict Chicago crime rates using time forecasting with Facebook Prophet module.


The Chicago Crime dataset contains a summary of the reported crimes occurred in the City of Chicago from 2001 to 2017.
Dataset has been obtained from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system.


Dataset contains the following columns:

ID: Unique identifier for the record.
Case Number: The Chicago Police Department RD Number (Records Division Number), which is unique to the incident.
Date: Date when the incident occurred.
Block: address where the incident occurred
IUCR: The Illinois Unifrom Crime Reporting code.
Primary Type: The primary description of the IUCR code.
Description: The secondary description of the IUCR code, a subcategory of the primary description.
Location Description: Description of the location where the incident occurred.
Arrest: Indicates whether an arrest was made.
Domestic: Indicates whether the incident was domestic-related as defined by the Illinois Domestic Violence Act.
Beat: Indicates the beat where the incident occurred. A beat is the smallest police geographic area – each beat has a dedicated police beat car.
District: Indicates the police district where the incident occurred.
Ward: The ward (City Council district) where the incident occurred.
Community Area: Indicates the community area where the incident occurred. Chicago has 77 community areas.
FBI Code: Indicates the crime classification as outlined in the FBI's National Incident-Based Reporting System (NIBRS).
X Coordinate: The x coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection.
Y Coordinate: The y coordinate of the location where the incident occurred in State Plane Illinois East NAD 1983 projection.
Year: Year the incident occurred.
Updated On: Date and time the record was last updated.
Latitude: The latitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
Longitude: The longitude of the location where the incident occurred. This location is shifted from the actual location for partial redaction but falls on the same block.
Location: The location where the incident occurred in a format that allows for creation of maps and other geographic operations on this data portal. This location is shifted from the actual location for partial redaction but falls on the same block.
