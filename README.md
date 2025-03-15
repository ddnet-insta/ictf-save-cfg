# cfg

Server configs for the official ddnet-insta gCTF/iCTF servers.

![servers](https://raw.githubusercontent.com/ddnet-insta/images/refs/heads/master/public_servers.png)

This repository should be cloned into the storage location of the server
and also has to be renamed to cfg.
It needs another repo cloned into it for common configs to fully work

```
# assume we are next to the DDNet-Server or in ~/.teeworlds
# or any other storage location that you use

git clone git@github.com:ddnet-insta/gctf-ictf-cfg.git cfg
cd cfg
git clone git@github.com:ddnet-insta/common-configs.git
git clone git@github.com:ddnet-insta/shared-cfg-secrets.git
git clone git@github.com:ddnet-insta/gctf-ictf-cfg-secrets.git
```
