For people who are using GPO to push the policy, we have seen some issues people use the samples and files. Here are the notes if you are using GPO:
1. The 4.18.2103.3 or later platform version is required for file-path-based support
2. Please make sure put group(groups) and policy(policies) into ‘<Groups></Groups>’ and ‘<PolicyRules></PolicyRules>’; otherwise, it will not work.
3. If you want to download the ADML and ADMX files from here and replace the files in PolicyDefinitions and PolicyDefinitions/en-US, you may see an error dialog. To solve this, after you download the files, please copy content of the file and paste to notepad and then do save-as with right file extension (.admx or adml).
4. Here is our official document: https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/device-control-removable-storage-access-control?view=o365-worldwide#frequently-asked-questions
