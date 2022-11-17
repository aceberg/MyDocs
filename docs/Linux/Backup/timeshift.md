---
tags:
  - backup
---

# Timeshift

Create:
```
timeshift --create --comments "A new backup" 
```
```
--tags D stands for Daily Backup
--tags W stands for Weekly Backup
--tags M stands for Monthly Backup
--tags O stands for On-demand Backup -- default tag
```
Restore:
```
timeshift --restore
```
List:
```
timeshift --list
```