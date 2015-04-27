#Test.TestDeploy

Responsible: N/A

##General checks

|                                                           Check                                                            |    Utført   |   Utført av   |
| :------------------------------------------------------------------------------------------------------------------------- | :---------- | :------------ |
| Review [upgradedocumentation][ref]                                                                                         | No date yet | No person yet |
| Project upgraded to Visual studio 2013 (only first time soluton for multiproject solutions)                                | No date yet | No person yet |
| Codelibraries upgraded to .net 4.5 (BizTalk projects will be upgraded automaticly)                                         | No date yet | No person yet |
| Copy this file to projects as `checklist.md`, for large projects (transport.Customers) one file for each subproject/folder | No date yet | No person yet |
| Check any vs_2013 branch for changes that should be merged into current solution                                           | No date yet | No person yet |

##Project artifacts

|                                Check                                |    Utført   |   Utført av   |
| :------------------------------------------------------------------ | :---------- | :------------ |
| Test maps locally and verify output (refer to [documentation][ref]) | No date yet | No person yet |
| Verify all testfiles for solution (delete extranous)                | No date yet | No person yet |
| Test maps in QA environment and verify output (test against output from POSAP445) | No date yet | No person yet |
| Check and verify general BRE rules.                                 | No date yet | No person yet |
| Check and verify environment specific rules                         | No date yet | No person yet |
| If applicable create new rule(s) for QA                             | No date yet | No person yet |
| If applicable add tracing to solution using CATS                    | No date yet | No person yet |

##BAM

|                                       Check                                       |    Utført   |   Utført av   |
| :-------------------------------------------------------------------------------- | :---------- | :------------ |
| Verify that orchestrations are logged to BAM                                      | No date yet | No person yet |
| Veriy that send ports (if any exists) are logged to BAM with correct data         | No date yet | No person yet |
| Verify that receive locations (if any exists) are logged to BAM with correct data | No date yet | No person yet |
| Verify end to end logging in BAM                                                  | No date yet | No person yet |
| Verify correct system name in BAM                                                 | No date yet | No person yet |


##Binding

|                            Check                            |    Utført   |   Utført av   |
| :---------------------------------------------------------- | :---------- | :------------ |
| Verify bindings for Test                                    | No date yet | No person yet |
| Verify bindings and create new bindings for QA              | No date yet | No person yet |
| Verify bindings for Productions                             | No date yet | No person yet |
| Verify bindings for adapters (changes to FTP,sFTP and FTPs) | No date yet | No person yet |
| Check hosts for WCF adapters (new hosts)                    | No date yet | No person yet |
| Check that the file is logged to BigLogger Path             | No date yet | No person yet |


##Deploy

|                                    Check                                     |    Utført   |   Utført av   |
| :--------------------------------------------------------------------------- | :---------- | :------------ |
| Deploy solution to test                                                      | No date yet | No person yet |
| Deploy and verify solution in QA                                             | No date yet | No person yet |
| Deploy and verify deployment to Productionenvironment during conversion time | No date yet | No person yet |

[ref]: https://github.com/bringMB/Bring.Wiki/wiki/Developer.UpgradeSolutions
