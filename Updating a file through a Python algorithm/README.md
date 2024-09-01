# Automated IP Address Update Algorithm in Python

## Table of Contents:

1. [Introduction] (#introduction)
2. [Methodology] (#methodology)
3. [Files and Structure] (#files-and-structure)
4. [Usage Instructions] (#usage-instructions)
5. [Conclusion] (#conclusion)

## Introduction
In organizations with restricted content, access control is crucial to ensure that only authorized IP addresses can access the content. This project aims to develop an algorithm that automates the process of updating the allow-list of IP addresses by removing IP addresses that should no longer have access to the content. 

## Methodology
The methodology employed in this project involves opening the allow-list file and reading its contents into a string format. This string is then converted into a list of IP addresses, allowing for easier manipulation and organization of the data. Next, the algorithm iterates through the remove list, identifying and removing IP addresses that are no longer authorized to access the restricted content. Once the list has been updated, it is converted back into a string format, enabling it to be written back to the allow-list file. Finally, the revised list of IP addresses is written to the allow-list file, ensuring that the file remains up-to-date and accurately reflects the authorized IP addresses.

## Files and Structure
`Algorithm for file updates in Python.docx`: completed document for dynamically updating an allow-list file by removing unauthorized IP addresses and ensuring the file remains current and accurate.

## Usage Instructions
To navigate the repository, review the file listed above. 

## Conclusion
The Automated IP Address Update Algorithm successfully automates the process of updating the allow-list of IP addresses by removing IP addresses that should no longer have access to the content. The algorithm is efficient, easy to implement, and ensures that the allow-list is always up-to-date, thereby maintaining the security and integrity of the restricted content.
