# Security Policy

## Supported Versions


| Version | Supported          |
| ------- | ------------------ |
| 3.0.x   | :white_check_mark: |
| 2.0.x   | :white_check_mark: |
| 1.0.x   | :white_check_mark: |

## Security Standards and Validations
This repository consists of `.deb` archives which are directly executed and installed. Hence, security should be a primary aspect.

All the packages here, before getting into the *master branch / release* are taken into possible checks for security issues.

External packages are extracted, attempts are made to reverse the potential changes (Or the changes are made in official package) 
and verify the checksum with the official package to ensure nothing else is added making sure everything safe to the knowledge of all. 
Also checks with common AV Systems and few other tests are done before getting it into the master/release.

The older packages are still retained for any other safety reports incase of any later discoveries.

## Reporting a Vulnerability / Malicious activity

Any security issues can be either reported as an issue or emailed to discord-debian-bullseye@contact.guna.gq based on the severity.

## Suggestions to improve testing
Its obvious that the methods followed here are not efficient and the whole work of any single commit/PR has to be redundantly done in 
backwards for checksum verification. Though its not a big deal given the update release cycles Discord, any suggestions to improve these testing 
processes are highly welcomed!

