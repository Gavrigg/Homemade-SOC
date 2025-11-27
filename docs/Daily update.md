## December 29, 2024
- Made the main README.md with the project introduction
- Searched for YouTube videos to document how to build the SOC

&nbsp;

## December 30, 2024
- Searched for information on tools I could use to build the SOC (SIEM, SOAR, IDS, IPS, AI...)
- I wrote about the incident handler's handbook
- Searched for information about ISO 27001

&nbsp;

## December 31, 2024
- Searched for information on ISO 27001
- Written and summarized the information on ISO 27001
- Translated the README.md from /docs from Spanish to English

&nbsp;


## January 9, 2025
- Searched information about different SIEM tools
- I will use Wazuh as the default SIEM
- Installed Wazuh OVA in VirtualBox
- Deployed Wazuh and added my PC as an Agent
- Implemented rules to create alerts on the server in order to monitor changes made to a directory in real time
- Implemented rules to create alerts on the server in order to stop brute force attacks

## November 27, 2025
- Just fixed an old PC and started using it as a Ubuntu Server: i5 10500F, Nvidia GTX1060, 8GB RAM DDR4, 1TB HDD, 250 SSD
- Implemented basic security measures: ufw, fail2ban, linys, ssh keys
- Organized the disks storage in logic volumes:

### **SSD**
| LV         |   Mounting   | Size |
| ---------- | :---------: | :----: |
| LV_Root    |     `/`     | 20 GB  |
| LV_apps    | `/srv/apps` | 70 GB  |
| LV_var_lib | `/var/lib`  | 50 GB  |
| LV_var_log | `/var/log`  | 10 GB  |
| LV_swap    |   `swap`    |  8 GB  |

### **HDD**
| LV         |   Mounting   | Size |
| ---------- | :---------: | :----: |
| LV_Home              |    `/home`     |  50 GB  |
| **LV_Backups**       | `/mnt/backups` | 300 GB  |
| **LV_DATA**          |    `/mnt/`     |         |
| **Physical partition** |  `/boot/efi`   | 1.049GB |
| —                    | Espacio libre  | ~35 GB  |
