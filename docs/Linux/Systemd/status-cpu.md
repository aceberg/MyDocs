---
tags:
  - systemd
---

# Status: CPU, Mem 

To show CPU and Memory usage in `systemctl status MyService.service` command edit 
`/etc/systemd/system.conf`:

```sh
DefaultCPUAccounting=yes
DefaultMemoryAccounting=yes
```
Then run
```sh
systemctl daemon-reload
```