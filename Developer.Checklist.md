#Test.TestDeploy

Responsible: N/A

##General checks

|                                                           Check                                                            |    Utført   |   Utført av   |
| :------------------------------------------------------------------------------------------------------------------------- | :---------- | :------------ |
| Review [upgradedocumentation][ref]                                                                                         | 2015-04-29|na|
| Project upgraded to Visual studio 2013 (only first time soluton for multiproject solutions)                                | 2015-04-29|na|
| Codelibraries upgraded to .net 4.5 (BizTalk projects will be upgraded automaticly)                                         | 2015-04-29|na|
| Copy this file to projects as `checklist.md`, for large projects (transport.Customers) one file for each subproject/folder | 2015-04-29|na|
| Check any vs_2013 branch for changes that should be merged into current solution                                           | 2015-04-29|na|

##Project artifacts

|                                Check                                |    Utført   |   Utført av   |
| :------------------------------------------------------------------ | :---------- | :------------ |
| Test maps locally and verify output (refer to [documentation][ref]) | 2015-04-29|na|
| Verify all testfiles for solution (delete extranous)                | 2015-04-29|na|
| Test maps in QA environment and verify output (test against output from POSAP445) | 2015-04-29|na|
| Check and verify general BRE rules.                                 | 2015-04-29|na|
| Check and verify environment specific rules                         | 2015-04-29|na|
| If applicable create new rule(s) for QA                             | 2015-04-29|na|
| If applicable add tracing to solution using CATS                    | 2015-04-29|na|

##BAM

|                                       Check                                       |    Utført   |   Utført av   |
| :-------------------------------------------------------------------------------- | :---------- | :------------ |
| Verify that orchestrations are logged to BAM                                      | 2015-04-29|na|
| Veriy that send ports (if any exists) are logged to BAM with correct data         | 2015-04-29|na|
| Verify that receive locations (if any exists) are logged to BAM with correct data | 2015-04-29|na|
| Verify end to end logging in BAM                                                  | 2015-04-29|na|
| Verify correct system name in BAM                                                 | 2015-04-29|na|


##Binding

|                            Check                            |    Utført   |   Utført av   |
| :---------------------------------------------------------- | :---------- | :------------ |
| Verify bindings for Test                                    | 2015-04-29|na|
| Verify bindings and create new bindings for QA              | 2015-04-29|na|
| Verify bindings for Productions                             | 2015-04-29|na|
| Verify bindings for adapters (changes to FTP,sFTP and FTPs) | 2015-04-29|na|
| Check hosts for WCF adapters (new hosts)                    | 2015-04-29|na|
| Check that the file is logged to BigLogger Path             | 2015-04-29|na|


##Deploy

|                                    Check                                     |    Utført   |   Utført av   |
| :--------------------------------------------------------------------------- | :---------- | :------------ |
| Deploy solution to test                                                      | 2015-04-29|na|
| Deploy and verify solution in QA                                             | 2015-04-29|na|
| Deploy and verify deployment to Productionenvironment during conversion time | 2015-04-29|na|

[ref]: https://github.com/bringMB/Bring.Wiki/wiki/Developer.UpgradeSolutions
