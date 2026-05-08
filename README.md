# Virtual Scroll Access System

**A file management platform that enables users to store, download, preview, and edit files in binary format.**

## Overview

Virtual Scroll Access System is a JavaFX desktop application for storing, previewing, and managing files in binary format. Files are converted to binary on upload, previewed and editable in their binary form within the application, and can be downloaded to retrieve the original or modified file. It features role-based access control, password-protected files, user profile management, search filters, and a scroll of the day feature.

## How To Run

```bash
gradle clean build run
```

## How To Test:

```bash
gradle test jacocoTestReport
```

## Admin Privileges

Should you wish to use the application as admin (add/edit/remove users and scrolls; set scroll of the day):  

Username: admin  
Password: admin

## User Accounts

The program includes several preconfigured user accounts:  

Username: bbat  
Password: password

Username: lulu  
Password: password

Username: lewlew  
Password: password

Username: fmurphy  
Password: password

Username: pete_g  
Password: password

## Locked Scrolls 

The program features a locked scroll that requires a password for access:

Filename: The Turing Journal  
Password: test

## Tech Stack
- JDK 17
- JavaFX 17
- Gradle 8.5
- JUnit 5
- JaCoCo

## Preview

[![](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/VSAS-MainPage.png)](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/VSAS-MainPage.png)

[![](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/GUI-UserProfileEditPage.png)](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/GUI-UserProfileEditPage.png)

[![](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/GUI-LockedScroll.png)](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/GUI-LockedScroll.png)

[![](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/GUI-SearchOptions.png)](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/GUI-SearchOptions.png)

[![](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/GUI-ViewScrolsPage.png)](https://github.com/bbat2575/virtual-scroll-access-system/raw/main/images/GUI-ViewScrolsPage.png)
