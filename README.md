```
Tomato64 Upgrade Script

Usage: t64up [options] [firmware path or URL]

Default is 'dirty' upgrade (NVRAM untouched) unless '-c' is specified.

Options:
  --check          Print latest Tomato64 version number.
  --erase-nvram    Erase all data in NVRAM memory (thorough).
                   Use alone or can be used with '-f'.
  -c               Clean upgrade (delete all settings).
  -d <path>        Overrides default download directory (/tmp/t64upwd/).
  -f               Use Fast-Reboot. Run locally the first time to 
                   ensure correct functionality.
  -n               Use wget '--no-check-certificate'
                   (you can try this if wget fail to download the firmware).
  -o               Only download firmware (no installation).
  -y               Automatic 'YES' to prompts. USE WITH CAUTION!

Infos:
 - URL must begin with \"http(s)://\".
 - Supported format is tzst.

WARNING:
   This script comes with no guarantee.
   This script, especially with option '-y', could be dangerous!
   Make sure you are using the right firmware before proceeding!
   
I'm NOT responsible for any bricked devices. Use at your own risks.
   
USE WITH CAUTION!
```
