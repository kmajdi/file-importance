# File Importance Estimator
This is a project of estimating how important a file is in a given file system to the owner of the file. This estimation will use factors such as:
- Extension (type) of the file
- Metadata of the file
- Latest use date of the file
- Availability of the file online
- Latest operation run on the file
- Size of the file
- Count of users in Owner group, Read group, Write group, Execute group
- Indication of whether a file is for one-time use (such as a setup file) or a long-term use file
- Processes that have accessed / will access the file automatically
- Overall estimated value of the parent directory of the file
