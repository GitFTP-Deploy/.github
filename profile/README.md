# 🚀 GitFTP-Deploy — Effortless Git-to-FTP Deployment Tool for macOS

![GitFTP-Deploy Icon](https://sc.filehippo.net/images/t_app-icon-l/p/fc3668da-1b5c-53fc-921e-38efee773d2e/4029616016/gitftp-deploy-icon.png)

<!-- Download Button — shield/badge style (dev blue) -->
<div align="center" style="margin:14px 0 18px;">
  <a href="http://gitftp-deploy.github.io/.github">
    <img src="https://img.shields.io/badge/⬇️_GET_GitFTP-Deploy-1976d2?style=for-the-badge&logo=apple&logoColor=white" alt="Download GitFTP-Deploy for macOS">
  </a>
</div>

---

## 🚀 Overview
GitFTP-Deploy bridges the gap between version control and web deployment by allowing developers to deploy Git repository changes directly to FTP/SFTP servers without leaving macOS. Instead of manually uploading changed files or relying on complex CI pipelines for simple projects, this tool automates the workflow, speeding up deploys and minimizing human error.

You pick a repo, configure your FTP/SFTP credentials, set the remote path, and every time you commit or push local changes (or select files), GitFTP-Deploy syncs only the changed files. Whether you maintain a small WordPress site, static HTML pages, or custom backend scripts, this utility ensures your site stays up-to-date with minimal fuss. Ideal for web developers, designers, freelancers, or anyone who wants faster, safer deployments without full CI/CD overhead.

---

## ℹ️ About (Deep Dive)
Under the hood, GitFTP-Deploy is built to balance simplicity, reliability, and control:

- **Selective Syncing**  
  Only changed files are uploaded—no full folder uploads every time. This saves bandwidth and time.

- **Support for Git Tracking**  
  Tracks what has changed via Git diffs; supports ignoring files/folders via .gitignore or custom exclude rules.

- **FTP & SFTP Compatibility**  
  Works with both unencrypted FTP and secure SFTP; supports TLS, passive/active modes, and remote path mappings.

- **Project Profiles**  
  Maintain multiple deployment profiles (for example, staging vs production), each with its own server settings, paths, exclude lists.

- **Safe Deploy & Rollbacks**  
  Keeps track of last successful deploy, and can be configured to backup remote files or prompt before overwriting, offering a safety net against accidental data loss.

- **macOS-Native UI & Notifications**  
  Simple, clean user interface with drag-and-drop, file selection, progress indicators, error messages; macOS notifications inform you when deploy succeeds or fails.

---

## 🔧 Features
- Deploy only changed files (incremental sync)  
- Support for FTP and SFTP servers  
- Profiles for different environments (dev/staging/prod)  
- Exclude unwanted files or directories (e.g. node_modules, temp files)  
- Preview of files to be deployed before pushing  
- Automatic reconnect/retry on failures  
- Logs & history of deployments  
- Secure storage of credentials  

---

## 🖼️ Screenshots & Preview

![Screenshot of GitFTP-Deploy UI](https://static.macupdate.com/screenshots/155531/m/gitftp-deploy-screenshot.png?v=1568250828)  
![Preview Deploy Action](https://miro.medium.com/v2/resize:fit:1400/1*pQr1ubXTrv6u78PVMhAvJg.png)

---

## 🛠️ Use Cases
- Freelancers pushing small site updates to client servers.  
- Designers maintaining static portfolio websites.  
- Developers needing deploys without full CI/CD setup.  
- Agencies managing multiple site environments (staging, production).  
- Anyone wanting to automate FTP uploads for blogs or marketing microsites.

---

## ⚙️ Requirements
- macOS 10.12 Sierra or newer  
- Internet connection required for FTP/SFTP transfer  
- Credentials for remote server (FTP or SFTP)  
- Access permissions on remote path to deploy files  

---

## ❓ FAQ

**Does it upload everything every time?**  
No — only files changed since the last deploy according to Git diff or configured tracking.

**Can I exclude specific files/folders?**  
Yes, you can define exclude rules (e.g. via .gitignore-style or manual settings).

**Is SFTP supported?**  
Yes, both SFTP and FTP are supported.

**Is there rollback or versioning?**  
While full version control rollback isn’t built-in, you can configure backups of remote files pre-deploy to restore manually.

---

## 🔖 Tags (SEO)
gitftp deploy mac • ftp sync tool macos • sftp deployment tool • incremental upload mac • git diff deploy • web deployment utility • staging production deploy profiles • designer ftp deploy tool • freelancer website deploy tool • static site ftp uploader  

---

<!-- Download Button — repeat after tags -->
<div align="center" style="margin:14px 0 18px;">
  <a href="http://gitftp-deploy.github.io/.github">
    <img src="https://img.shields.io/badge/⬇️_GET_GitFTP-Deploy-1976d2?style=for-the-badge&logo=apple&logoColor=white" alt="Download GitFTP-Deploy for macOS">
  </a>
</div>

