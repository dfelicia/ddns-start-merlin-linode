# ddns-start-merlin-linode
Custom DDNS script to update Linode DNS

## Description

Update Linode DNS on an Asus router running Merlin firmware

## Requirements

1. Install `bash` and `jq` via entware
2. Generate Linode API key, then get Domain ID and Resource ID for your A record, then modify the constants delcared at the top of the script (leave `SCRIPT_NAME` alone).
3. Copy the script to your router as `/jffs/scripts/ddns-start` and make sure it's executable. (Run `dos2unix` on it if you edited it using Winblows.)
4. Test it from command line, and once you're happy change DDNS to "Custom"

## Further Reading
* https://github.com/RMerl/asuswrt-merlin.ng/wiki
* https://www.linode.com/docs/products/tools/cloud-manager/guides/cloud-api-keys/
