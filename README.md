# 🛠️ Build a Complete Linux Backup Server Project

> Author: Anivesh Mohan  
> Blog: [Medium](https://aniveshmohan.medium.com)  
> Status: ✅ Completed (2 Parts)

This project is a complete walkthrough of how I built a **local and remote backup system** using tools like **rsync**, **cron**, and **SSH** — all explained in an easy and fun way!

---

## 🚀 Project Overview

This is a **2-part blog series** where I explain how to set up both **local backups** and **remote automated backups** using rsync and cron jobs on Linux.

---

## 📘 Part 1: Local Backup Using rsync

🔗 [Read Full Blog](https://aniveshmohan.medium.com/%EF%B8%8F-build-a-complete-linux-backup-server-project-local-backup-part-1-15daef1ab7fa)

### 🔹 What’s Inside:
- ✅ Installed rsync on Kali Linux
- ✅ Cloned a sample website for testing
- ✅ Created a local backup folder
- ✅ Explained `rsync /` usage (copy folder vs contents)
- ✅ Performed first backup using `rsync -av`
- ✅ Verified with `ls -l` to check ownership & timestamps

---

## 📘 Part 2: Remote Backup & Automation

🔗 [Read Full Blog](https://aniveshmohan.medium.com/%EF%B8%8F-build-a-complete-linux-backup-server-project-remote-backup-automation-part-2-e9cf8af0b809)

### 🔹 What’s Inside:
- ✅ Kali Linux as local machine, CentOS as remote machine
- ✅ Found IPs using `ip addr`
- ✅ Created remote backup directory
- ✅ Used `rsync -avz` over SSH to copy files
- ✅ Set up **passwordless SSH** using `ssh-keygen` and `ssh-copy-id`
- ✅ Recovered deleted files using **reverse rsync**
- ✅ Automated daily backups at 9:25 AM using **cron**

---

## 🛠️ Tools & Commands Used

- 🐧 Linux (Kali, CentOS)
- 🔁 `rsync` (for file sync)
- ⏰ `cron` (for scheduling)
- 🔐 `SSH` (for secure transfer)
- 📁 `mkdir`, `ls`, `ip addr`
- 🧠 Concepts: incremental backups, passwordless automation, file recovery

