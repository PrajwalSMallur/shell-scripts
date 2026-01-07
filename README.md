# Shell Scripts

This repository contains a collection of useful **Linux shell scripts** (Bash) to automate common system administration and monitoring tasks. :contentReference[oaicite:1]{index=1}

Shell scripts are text files that contain sequences of commands interpreted by a Unix shell such as Bash. They help automate repetitive tasks, manage services, and perform system checks. :contentReference[oaicite:2]{index=2}

## 📦 Repository Contents

Below is an overview of the scripts included in this repository:

### 🛠️ Deployment & Cleanup
- **Automated Deployment Script**  
  A script to automate deployment steps such as copying files, setting permissions, or restarting services.

- **Cleanup Script**  
  Removes temporary files, old logs, or unused artifacts to free up space.

### 📊 System Monitoring
- **Disk Usage Monitor Script**  
  Checks local disk usage and reports high usage so corrective action can be taken.

- **Service Monitor Script**  
  Monitors whether specific services are running and restarts them if needed.

- **Tomcat Service Monitor Script**  
  Specifically checks the Apache Tomcat service, restarts it if down, and can log status.

## 📋 How to Use

1. **Clone the repository**
   ```sh
   git clone https://github.com/chandakesujay-bit/Shell-Scripts.git
   cd Shell-Scripts
