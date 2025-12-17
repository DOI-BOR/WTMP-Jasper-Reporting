# USBR WTMP Jasper
This repository contains all the Jasper files related to the Bureau of Reclamation (USBR) Water Temperature Modeling Platform (WTMP) reporting. 
During the reporting workflow, these .jrxml files get compiled into .jasper files. These then get used to create the final reports.

## Dependencies
Jaspersoft Studio is a useful tool for editing these Jasper files.

Any additional dependencies need to be added here.

## Usage
### Usage withing the build process
To be added later.

### Post build implementation
After making any desired changes to the files, the old .jrmxl files must be replaced in the WAT build.
1. In the reports/jasper directory of the WAT build, delete any old versions of the changed files.
2. Place the updated files in the reports/jasper directory of the WAT build.
