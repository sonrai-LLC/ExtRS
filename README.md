# ExtRS
ExtRS provides a framework for extending the capabilities of the report data models provided by SSRS that determine what can be rendered on a report. With ExtRS, (prounounced "extras"), common public API endpoints and SDK clients are consolidated into a Swiss Army knife of supplemental, publicly available data that can compliment your reporting. API operations provide SSRS user management, granular report item security and other metric datasets and values that may prove useful for one or more of your reports. 

Additionally, the general purpose ExtRS API operations can alert users, get weather, sports, news info, data-driven alerts and lots more.

SSRS ain't dead- it's just a niche tool that hasn't fully realized its potential- yet. 😊

# Requirements
This plug-in works as a drop-in Nuget package for any .NET Core or .NET Standard project as well an SSRS Custom Assembly as described by Microsoft here: https://docs.microsoft.com/en-us/sql/reporting-services/custom-assemblies/using-custom-assemblies-with-reports?view=sql-server-ver15

# Contents
This package includes the following components:
- ExtRS.dll

# Related SSRS Tools
- [ExtRSAuth](https://github.com/sonrai-LLC/ExtRSAuth) for enabling further extension of the SSRS Microsoft Custom Security Sample.
