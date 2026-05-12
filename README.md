# Vagrant Lab

## 📌 Project Overview

This project is a collection of DevOps practice labs built entirely in a local environment using **Vagrant and Virtual Machines**.

It demonstrates how web applications and CMS platforms can be manually deployed first, and then fully automated using **Vagrant provisioning scripts.

---

## Projects Included

### HTML Website Deployment (CentOS VM)

- Set up a basic HTML template website
- Deployed manually using a Vagrant-created VM
- Environment: **CentOS**
- Learned manual provisioning of web server setup

---

### WordPress Deployment (Ubuntu VM)

- Installed and configured WordPress CMS
- Connected database and web server manually
- Deployed using a Vagrant VM
- Environment: **Ubuntu**
- Accessed locally through browser

---

###  Automation with Vagrant Provisioning

After manual setup, both projects were automated using **Vagrant provisioning scripts**:

- Installation steps converted into shell scripts
- Automated server setup during `vagrant up`
- No manual configuration required anymore
- Fully reproducible environments

---

## Technologies Used

- Vagrant
- VirtualBox
- CentOS Linux
- Ubuntu Linux
- Apache / Web Server setup
- WordPress
- Shell Scripting
- HTML templates
- Git & GitHub

---

## Workflow Summary

### Phase 1: Manual Deployment
- Created VMs using Vagrant
- Manually installed and configured:
  - Web server
  - HTML site
  - WordPress CMS
- Verified everything locally via browser

### Phase 2: Automation
- Converted manual steps into provisioning scripts
- Embedded scripts inside `Vagrantfile`
