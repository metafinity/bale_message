# Bale Alert Action for Splunk  
![GitHub release (latest by date)](https://img.shields.io/github/v/release/username/repo)  
![Splunk AppInspect](https://img.shields.io/badge/Splunk-AppInspect-passed-brightgreen)  
![Python 3](https://img.shields.io/badge/Python-3-blue)  

---

## 📌 Overview  
This is a **Splunk Modular Alert** for sending messages to **Bale Messenger** using the Bale API.  

The App is fully **Python 3 compatible**.  
On Splunk 8+ this version enforces Python 3 execution for the alert action script, in order to satisfy **Splunkbase AppInspect requirements**.  

---

## 🚀 Features  
- Send Splunk alerts directly to Bale Messenger.  
- Supports **Result Tokens** such as:  
  ```
  $result.fieldname$
  ```  
- Logging for troubleshooting: `bale_alert.log`.  

---

## ⚙️ Installation  
1. Download the package.  
2. In Splunk Web:  
   **Manage Apps → Install app from file**  
3. Upload the app package.  
4. Configure the app in **Manage Apps**.  

---

## 🔑 Configuration  
1. Visit [Bale Docs](https://dev.bale.ai/) to create a bot.  
2. Get your **Bot Token** and **Chat ID**.  
3. Configure them in Splunk’s alert action settings.  

---

## 🐞 Troubleshooting  
Check logs in:  
- `$SPLUNK_HOME/var/log/splunk/bale_alert.log`  
- Or via Splunk search:  
  ```
  index=_internal sourcetype=bale_alert
  ```  

---

## 📄 License & Support  
This App is built and maintained by **Meysam Talebi**.  
For issues, open a ticket in [GitHub Issues](../../issues).  

---

# 📢 اکشن هشدار Bale برای Splunk  

---

## 📌 معرفی  
این یک **اکشن هشدار ماژولار برای Splunk** است که امکان ارسال پیام به **پیام‌رسان Bale** از طریق API رسمی Bale را فراهم می‌کند.  

این اپلیکیشن کاملاً با **Python 3** سازگار است و روی Splunk نسخه 8 به بالا، اجرای اسکریپت‌ها را فقط با Python 3 انجام می‌دهد تا الزامات **Splunkbase AppInspect** برآورده شود.  

---

## 🚀 قابلیت‌ها  
- ارسال هشدارهای Splunk به پیام‌رسان Bale  
- پشتیبانی از **Result Tokens** مانند:  
  ```
  $result.fieldname$
  ```  
- ثبت گزارش در فایل لاگ برای عیب‌یابی (`bale_alert.log`)  

---

## ⚙️ نصب  
1. بسته‌ی اپلیکیشن را دانلود کنید.  
2. در Splunk Web وارد شوید و از منوی:  
   **Manage Apps → Install app from file**  
3. فایل اپ را بارگذاری و نصب کنید.  
4. پس از نصب، از بخش **Manage Apps** تنظیمات را اعمال کنید.  

---

## 🔑 پیکربندی  
1. به [مستندات Bale](https://dev.bale.ai/) مراجعه کنید و یک ربات ایجاد کنید.  
2. **Bot Token** و **Chat ID** خود را دریافت کنید.  
3. این مقادیر را در تنظیمات اکشن هشدار در Splunk وارد کنید.  

---

## 🐞 عیب‌یابی  
برای بررسی مشکلات:  
- فایل لاگ:  
  ```
  $SPLUNK_HOME/var/log/splunk/bale_alert.log
  ```  
- یا از طریق جستجو در Splunk:  
  ```
  index=_internal sourcetype=bale_alert
  ```  

---

## 📄 پشتیبانی  
این اپلیکیشن توسط **میثم طالبی** توسعه و پشتیبانی می‌شود.  
در صورت وجود مشکل، لطفاً در [GitHub Issues](../../issues) گزارش دهید.  
