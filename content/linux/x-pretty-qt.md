---
title: Patch `xsession` so QT looks nice
---

After writing [Make QT less ugly](https://theorangeone.net/posts/make-qt-less-ugly/), I switched to LightDM, which completely broke it.

This is the patch for `/etc/lightdm/Xsession` to stop it overriding my tweaks.

{{< github_file repo="realorangeone/dotfiles" path="files/xsession.patch" >}}
