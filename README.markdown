# ImgurFox

A Firefox extension by Chromakode and koryk to upload images to imgur.com

# Setup

Make sure python is installed, probably python 2.

# Compiling

```bash
./buildxpi.py
```

generates `imgurfox.xpi` in the root directory.

# Installing

1. In Firefox, visit [about:config](about:config) and set `xpinstall.signatures.required` to **false**. This only needs to be done once per Firefox installation, not every time you sideload a new xpi. [More details](https://support.mozilla.org/en-US/kb/add-on-signing-in-firefox?as=u&utm_source=inproduct#w_override-add-on-signing-advanced-users) 
1. Drag and drop `imgurfox.xpi` from your file browser (e.g. Explorer or Finder) onto a Firefox window.
1. Click [Install] button on the callout drawer confirming "install an unsigned extension: Imgur Uploader?"
1. Restart Firefox.
