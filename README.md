# Active Acoustics Strategic Initiative (AA-SI) Windows Virtual Machine

## About
The AA-SI has access to a Windows Virtual Machine (WindowsVM) for processing and analyzing data in the Windows environment. These instructions are for users to:
- Get a WindowsVM
- Setup the WindowsVM
- Install software </br>

As of summer 2026, we are using the passive acoustics monitoring (PAM) WindowsVM. At some time, hopefully in the near future, NOAA Fisheries OCIO will provide a VM and we will update this site. Until that time, we will provide instructions for the PAM VM. 

## For new repositories in nmfs-ost organization

2) Add [topics](https://docs.github.com/en/enterprise-cloud@latest/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics) to help users find repositories.
3) [Add a license](https://docs.github.com/en/enterprise-cloud@latest/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). **This is a MUST for public repositories.** If you are migrating a private repository, it is strongly advised to add a license but not required. Work written by For work  produced by U.S. government employees, we are required to use an [open source license](https://opensource.org/license). If contributors other than FTEs wrote code and the repository does not yet have an open source license, make sure all parties agree before applying an open source license. For data/documentation, use [CC0](https://creativecommons.org/public-domain/cc0/). For code, common choices include [Apache 2.0](https://opensource.org/license/apache-2-0) and [MIT](https://opensource.org/license/mit).
4) For private or internal repositories, Confirm that the file `.github/workflows/secretSCAN.yml` is in this repository. This is a GitHub action that will check for token and keys that are accidentally committed to a repository.
5) For public repositories, you may delete the file `.github/workflows/secretSCAN.yml`. This is because [GitHub secret scanning is used in Public Repositories](https://docs.github.com/en/enterprise-cloud@latest/code-security/secret-scanning/configuring-secret-scanning-for-your-repositories#enabling-secret-scanning-alerts-for-users).
6) Once you have completed the steps, delete the instructions from this `README.md`.

# Disclaimer
This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an ‘as is’ basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.
