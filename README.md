# Public MER Metadata Repo

## Purpose
The purpose for sharing DATIM’s Metadata is to make it easier for Implementing Partners (IPs) and other interested users to collect and report PEPFAR MER data that conforms to DATIM requirements.

DATIM will periodically (as needed) publish the latest DATIM metadata as it related to the most recent version of the PEPFAR Monitoring, Evaluation, and Reporting Indicator Reference Guide.

## Terms of Use
The terms of use are intended to (1) Outline the use and reuse of DATIM’s Metadata and (2) reiterate key responsibilities associated with its use within external systems.

## Key responsibilities for Implementing Partners (IPs) and other interested users

- It is the responsibility of IPs to ensure that data collected is valid with respect to the destination sites, periods, indicators, disaggregation, and mechanisms before it is imported into DATIM. Consequently, all data values must be associated with four metadata dimensions, which describe different aspects of the data. These associated dimensions are noted below.
   - Where — Organization unit (OU): This dimension describes the location of the data (i.e., where the data are captured). Example: clinical facility, community site, or OU level
   - What — Data element (indicator) + disaggregation: This dimension describes the phenomena to which the data value is attached, such as the Number of HTC Tests for Females 1-4. In this case, the data element has a disaggregation of Female 1-4. Data elements in DATIM typically have many different disaggregations with respect to age and gender. In addition, different classes of data elements exist, such as Targets, Results, DSD, and TA.
   - When — Period: This dimension describes the time period of the data being reported. Example: January through March 2016 or April through June 2016
   - Who — Funding mechanism: Also known as the “attribute option combination,” this is an extra custom dimension in DATIM that describes for which implementing mechanism the data are being reported and refers to the Foreign Assistance Coordination and Tracking System (FACTS Info) funding mechanism ID.
- IPs maintain oversight responsibility for their data, ensuring accuracy and completeness and agrees to follow data submission Standard Operating Procedures (SOPs), in alignment with the PEPFAR Calendar and as described in the DATIM support site (https://datim.zendesk.com) .
- **IPs are still responsible to report to PEPFAR regardless of success in implementation/use of the published metadata. As such IPs agree to continue to report MER quarterly results to PEPFAR via already established standard reporting method i.e. data import or manual data entry.**
- Use of the DATIM metadata does not change the data protection requirements of IPs/other interested users.

## Accessing DATIM Metadata
The DATIM metadata package can be accessed via the DATIM-MER-METADATA public repository on Github. Components included are:

- Data Elements and Data Element Groups
- Category Combos and all Child Objects
- Datasets and Data Entry Forms
- Cleaning Favorites and Cleaning Indicators (When Available)
- Validation Rules

## What is not included:

- A fully tested DATIM metadata package i.e. successful use of this package will be the responsibility of the users not the DATIM.
- DATIM metadata package that can be used with any version of DHIS2. The package will be based on DATIM’s currently deployed DHIS2 version; Hence it may or may not be the same version deployed by an IP/other interested users.

## Release Schedule
There is no predefined schedule for when the metadata package will be updated. Users will need to check the public repository to ensure that they’re using the latest published version.

The latest published version may not be the most recent version of the metadata within DATIM.

## Disclaimers
**The metadata available includes several components that are necessary for loading and maintaining a DHIS2 instance to include PEPFAR’s MER metadata that is compatible with DATIM. The package does not address additional pieces and processes required for a successful operation of a DHIS2 instance, for example user management as these should be the expectation is that these are implemented and managed by the partner organization.**

**PEPFAR is not responsible for damage to any production DHIS 2 instances incurred from the use of files found here. We strongly advise all metadata managers to make liberal use of test environments.**

**As such, no guarantees and responsibilities are provided by the act of publishing DATIM’s metadata.**

## Contact us
Have questions, comments, or issue? [Please Submit a request.](https://datim.zendesk.com/hc/en-us/requests/new)

[Back to Zendesk](https://datim.zendesk.com/hc/en-us/articles/360037706811)
