# [Patch]Support 16 HDD & 2 NVME on DVA1622
```
In tinycore run this command below before start to build bootloader
curl -O https://raw.githubusercontent.com/maitien2004/xpenology/main/dva1622.dts
./rploader.sh patchdtc dva1622-7.1.0-42661
cp /home/tc/custom-module/dva1622.dtb /home/tc/redpill-load/custom/model_dva1622.dtb
./rploader.sh build dva1622-7.1.0-42661
```
