### LFI

* Command

```
ffuf -request req.txt -w ~/pentest/wordlist/lfi-full.txt -r -mr "[a-zA-Z_-]{1,}:x:[0-9]{1,}:[0-9]{1,}:|(\d+){1,3}.(\d+){1,3}.(\d+){1,3}.(\d+){1,3}\s+localhost|for 16-bit app support|boot loader"
```

* Payloads

```
https://raw.githubusercontent.com/swisskyrepo/PayloadsAllTheThings/master/Directory%20Traversal/Intruder/dotdotpwn.txt
```
