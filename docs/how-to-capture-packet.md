## Capture packets command

```bash
sudo tstat -l -i en0 -s out
```

อธิบายคำสั่ง
- sudo: รัน tstat ด้วย super user permission
- -l: enable live capture using libpcap
- -i: interface ที่จะทำการ capture
- -s: output directory ที่จะเก็บไฟล์ที่ดัก packets
