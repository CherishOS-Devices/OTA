Read This Before Proceeding :-

After you finish compiling a build, before uploading, you need to type this into your terminal:

```bash 
     date +%s
```
It will generation for u it is datetime and add it after generate json

Clone the OTA repo in your ROM directory.
To generate json and push OTA,
```bash
bash OTA/support/ota.sh <device_codename> <rom_folder> <maintainer_name> <maintainer_url> <forum_url>

e.g.
bash OTA/support/ota.sh lavender cherish "Hung Phan" https://t.me/hungphan2001 https://forum.xda-developers.com/
```
After uploading........

NOTES:
- ROM directory will look for *home/<os_username>/<rom_folder>*.
- Use double quotes for parameters with more than a single word, like maintainer name in the example above.
- All parameters are mandatory.
