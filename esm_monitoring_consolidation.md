---
marp: true
_class: lead
theme: gaia
header: '![width:60px height:45px](./images/gw_monogram_wht_rev.png)'
footer: GWIT Platform and Cloud Computing
paginate: false
backgroundColor: #033C5A
color: #AA9868
style: |
  header {
    display: grid;
    padding: 10px;
    align-content: right;
    justify-content: right;
  }
  footer {
    color: #033C5A;
    background-color: #AA9868;
    display: grid;
    height: 50px;
    line-height: 30px;
    justify-content: right;
  }

---
# PCC: Server Administration
# Monitoring Consolidation
#### (no more nagios)
---
## When ?
- January 14th, 2025

## Why ?
- Common monitoring process for all servers
- One less tool to manage
- Nagios costs money, now it won't

---
## What's Changing ? (Email Formatting)

- Email Formatting
![width:600 height:200](./images/alert_cpu_utilization.png)
![width:600 height:200](./images/alert_free_space.png)

---
## What's Changing ? (Maintenance Mode)
- self service
- mutes alerts for a specified time
![width:375 height:330](./images/maintenance_mode.png)


---
## What's Changing ? (Maint. Mode cont'd)

- [Maintenance Mode for Linux](https://scom.it.gwu.edu/MM/Home/Unix)
- adm credentials required to access scheduler console
- access restricted to GW IP


---
## Links
- [This Presentation](https://github.com/gwit-esd-pcc-serveradministration/esm_monitoring_consolidation.git)
- [OS Teams Consolidation](https://github.com/gwit-esd-pcc-serveradministration/pcc_serveradmin_consolidation_roadshow.git)
---

![bg center: 10%an0%](./images/palantir.png)