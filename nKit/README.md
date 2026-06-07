# nKit

A lightweight package manager and tool hub for AutoCAD automation tools.

---

<details>
<summary>🇬🇧 English</summary>

## Overview

nKit is the core package manager for the AutoCAD Tools ecosystem.

It provides a unified system for installing, updating, loading, and managing AutoLISP-based tools in AutoCAD.

Instead of manually loading scripts or managing files, users interact with a single command that opens a modern interface inside AutoCAD.

---

## Core Concept

nKit is designed around a simple idea:

> One command. One interface. Full control over your tools.

Users interact with the system through a single entry point inside AutoCAD (e.g. `NK`), which opens a visual tool manager.

---

## Features

* Install and remove tools from a remote registry
* Check for updates (manual trigger only)
* Load and unload AutoLISP modules
* Search and filter available tools
* Manage tool versions (install / downgrade / upgrade)
* View help (GIF / video / documentation)
* Alias support for commands
* Offline-first local registry system

---

## Command Entry

nKit is accessed via a single AutoCAD command:

```text id="c1p9xq"
NK
```

This opens the nKit management palette inside AutoCAD.

---

## Architecture

nKit is split into three layers:

```text id="n7xq3k"
1. Core Engine (AutoLISP)
   - Install / Remove / Update logic
   - Local registry management

2. UI Layer (HTML Palette or DCL fallback)
   - Tool browsing
   - Search & filters
   - Updates interface

3. Remote Registry
   - JSON-based manifest system
   - GitHub / website fallback sources
```

---

## Update Strategy

* No automatic background updates
* Updates are triggered manually by the user
* System is fully usable offline
* Multiple fallback sources are supported

---

## Philosophy

> Tools should not be scattered across files.
> They should behave like a system.

nKit transforms AutoCAD scripts into a managed ecosystem instead of isolated utilities.

---

## Author

Masoud Nasiri
Architect building tools for architects

---

## License

MIT License

</details>

---

<details>
<summary>🇮🇷 فارسی</summary>

## معرفی

nKit هسته مدیریت ابزارهای مجموعه AutoCAD Tools است.

این سیستم برای نصب، بروزرسانی، بارگذاری و مدیریت ابزارهای AutoLISP در محیط AutoCAD طراحی شده است.

به جای اجرای دستی اسکریپت‌ها، کاربر تنها با یک دستور وارد یک محیط گرافیکی مدیریت ابزار می‌شود.

---

## مفهوم اصلی

nKit بر اساس یک ایده ساده ساخته شده است:

> یک دستور. یک رابط. کنترل کامل روی ابزارها.

کاربر تنها با یک دستور وارد محیط مدیریت ابزارها می‌شود (مثلاً `NK`) و تمام عملیات از همانجا انجام می‌شود.

---

## امکانات

* نصب و حذف ابزارها از مخزن آنلاین
* بررسی بروزرسانی‌ها (فقط به صورت دستی)
* بارگذاری و غیرفعال‌سازی ابزارها
* جستجو و فیلتر ابزارها
* مدیریت نسخه‌ها (آپدیت / دانگرید)
* نمایش راهنما (ویدیو / GIF / مستندات)
* پشتیبانی از Alias برای دستورات
* ساختار آفلاین با رجیستری محلی

---

## دستور اصلی

دسترسی به nKit از طریق یک دستور واحد در اتوکد انجام می‌شود:

```text id="q8m2nd"
NK
```

با اجرای این دستور، پنل مدیریت ابزارها باز می‌شود.

---

## معماری سیستم

nKit از سه لایه تشکیل شده است:

```text id="r4t9pw"
1. هسته (AutoLISP)
   - مدیریت نصب و حذف
   - مدیریت نسخه‌ها
   - رجیستری محلی

2. رابط کاربری (HTML یا DCL جایگزین)
   - نمایش ابزارها
   - جستجو و فیلتر
   - مدیریت بروزرسانی

3. مخزن آنلاین
   - فایل‌های JSON
   - GitHub و سایت به عنوان منبع
```

---

## بروزرسانی

* بروزرسانی خودکار در پس‌زمینه انجام نمی‌شود
* فقط با درخواست کاربر فعال می‌شود
* سیستم کاملاً آفلاین قابل استفاده است
* از چند منبع جایگزین پشتیبانی می‌کند

---

## فلسفه طراحی

> ابزارها نباید مجموعه‌ای پراکنده از فایل‌ها باشند.
> باید به صورت یک سیستم یکپارچه عمل کنند.

nKit ابزارهای AutoCAD را از حالت اسکریپت‌های پراکنده به یک اکوسیستم مدیریت‌شده تبدیل می‌کند.

---

## توسعه‌دهنده

مسعود نصیری
معمار ابزارساز برای معماران

---

## مجوز

MIT License

</details>
