# OSMF2_0.swc

Forked from here: https://sourceforge.net/adobe/flexsdk/code/HEAD/tree/trunk/frameworks/libs/OSMF2_0.swc

Also found a PDF that I'm including as a time capsule: https://sourceforge.net/projects/flexsdk.adobe/files/Flex_Hero_Preview_Release_Notes_20101024.pdf

## Why?

Forced ssl-redirect:

```
admin@ip-172-31-46-144:~$ sudo wget http://sourceforge.net/adobe/flexsdk/code/HEAD/tree/trunk/frameworks/libs/OSMF2_0.swc?format=raw -O /opt/flex-sdk/frameworks/libs/osmf.swc --no-check-certificate
--2019-09-16 22:27:30--  http://sourceforge.net/adobe/flexsdk/code/HEAD/tree/trunk/frameworks/libs/OSMF2_0.swc?format=raw
Resolving sourceforge.net (sourceforge.net)... 216.105.38.13
Connecting to sourceforge.net (sourceforge.net)|216.105.38.13|:80... connected.
HTTP request sent, awaiting response... 302 Found
Location: https://sourceforge.net/adobe/flexsdk/code/HEAD/tree/trunk/frameworks/libs/OSMF2_0.swc?format=raw [following]
--2019-09-16 22:27:30--  https://sourceforge.net/adobe/flexsdk/code/HEAD/tree/trunk/frameworks/libs/OSMF2_0.swc?format=raw
Connecting to sourceforge.net (sourceforge.net)|216.105.38.13|:443... connected.
GnuTLS: A TLS fatal alert has been received.
Unable to establish SSL connection.
```

# License

The same as root-source. I assume it's Apache License: https://github.com/apache/flex-sdk/blob/ba414443032b49c45ff11b61db452c8a8f428bd8/LICENSE
