# Bale Alert Action for Splunk 📢
![GitHub release (latest by date)](https://img.shields.io/github/v/release/metafinity/bale_message)  ![Python 3](https://img.shields.io/badge/Python-3-blue)  
<img src="images/my_image.png" alt="لوگو پروژه" width="200"/>

## 📌 Overview  
This is a **Splunk Modular Alert** for sending messages to **Bale Messenger** using the Bale API.  

The App is fully **Python 3 compatible**.  
On Splunk 8+ this version enforces Python 3 execution for the alert action script, in order to satisfy **Splunkbase AppInspect requirements**.  


## 🚀 Features  
- Send Splunk alerts directly to Bale Messenger.  
- Supports **Result Tokens** such as:  
  ```
  $result.fieldname$
  ```  
- Logging for troubleshooting: `bale_alert.log`.  


## ⚙️ Installation  
1. Download the package.  
2. In Splunk Web:  
   **Manage Apps → Install app from file**  
3. Upload the app package.  
4. Configure the app in **Manage Apps**.  


## 🔑 Configuration  
1. Visit [Bale Docs](https://dev.bale.ai/) to create a bot.  
2. Get your **Bot Token** and **Chat ID**.  
3. Configure them in Splunk’s alert action settings.  


## 🐞 Troubleshooting  
Check logs in:  
- `$SPLUNK_HOME/var/log/splunk/bale_alert.log`  
- Or via Splunk search:  
  ```
  index=_internal sourcetype=bale_alert
  ```  


## 📄 License & Support  
This App is built and maintained under MIT License.
For issues, open a ticket in [GitHub Issues](../../issues).  
