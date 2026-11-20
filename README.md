# Warden Hub APT repository

This repository serves the signed APT repository for Warden Hub, an endpoint
protection agent for Ubuntu with a GNOME app. It holds no source code.

Current release: 0.2.3. To install, download
[`wardenhub-archive_2_all.deb`](https://phlthydelphya.github.io/wardenhub/wardenhub-archive_2_all.deb)
and open it in App Center. It adds this repository and installs the rest.

## Signing key

Every release is signed by the Warden Hub archive key:

```
2DAE 5E5A 362C D0C5 B3AD  8C1E A273 13B6 E496 8A04
```

ed25519, sign only, expires 2029-11-17. The `wardenhub-archive` package installs
this key, the sources entry and the update origin. Do not trust a repository that
is signed by any other key.
