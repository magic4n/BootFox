██╗     ██╗███╗   ██╗███████╗ █████╗  ██████╗ ███████╗ ██████╗ ███████╗
██║     ██║████╗  ██║██╔════╝██╔══██╗██╔════╝ ██╔════╝██╔═══██╗██╔════╝
██║     ██║██╔██╗ ██║█████╗  ███████║██║  ███╗█████╗  ██║   ██║███████╗
██║     ██║██║╚██╗██║██╔══╝  ██╔══██║██║   ██║██╔══╝  ██║   ██║╚════██║
███████╗██║██║ ╚████║███████╗██║  ██║╚██████╔╝███████╗╚██████╔╝███████║
╚══════╝╚═╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝ ╚═════╝ ╚══════╝
by foxer

📱 Installation Guide / Инструкция по установке

🇬🇧 English

⚙️ How to install:

1. 🔧 Flash the firmware 3.0.302 Global
2. 🥾 Flash boot:
   ```bash
   fastboot flash boot boot_apatch\boot_ap.img
   ```
   🐧 Linux:
   ```bash
   fastboot flash boot boot_apatch/boot_ap.img
   ```
3. 🔄 Reboot to FastbootD:
   ```bash
   fastboot reboot fastboot
   ```
4. 📦 Flash product:
   ```bash
   fastboot flash product product\product.img
   ```
   🐧 Linux:
   ```bash
   fastboot flash product product/product.img
   ```
5. 💾 Flash system:
   ```bash
   fastboot flash system system\system.img
   ```
   🐧 Linux:
   ```bash
   fastboot flash system system/system.img
   ```
6. 🔓 (Optional) Erase FRP:
   ```bash
   fastboot erase frp
   ```
7. 🚀 Reboot:
   ```bash
   fastboot reboot
   ```

✅ Done!

---

🇷🇺 Русский

⚙️ Как установить:

1. 🔧 Прошейте прошивку 3.0.302 Global
2. 🥾 Прошейте boot:
   ```bash
   fastboot flash boot boot_apatch\boot_ap.img
   ```
   🐧 Linux:
   ```bash
   fastboot flash boot boot_apatch/boot_ap.img
   ```
3. 🔄 Перезагрузитесь в FastbootD:
   ```bash
   fastboot reboot fastboot
   ```
4. 📦 Прошейте product:
   ```bash
   fastboot flash product product\product.img
   ```
   🐧 Linux:
   ```bash
   fastboot flash product product/product.img
   ```
5. 💾 Прошейте system:
   ```bash
   fastboot flash system system\system.img
   ```
   🐧 Linux:
   ```bash
   fastboot flash system system/system.img
   ```
6. 🔓 (Опционально) Сотрите FRP:
   ```bash
   fastboot erase frp
   ```
7. 🚀 Перезагрузитесь:
   ```bash
   fastboot reboot
   ```

✅ Готово!

---

💡 Tip / Совет: Make sure ADB/Fastboot drivers are installed and the device is connected in Fastboot mode.
Убедитесь, что у вас установлены драйверы ADB/Fastboot и устройство подключено в режиме Fastboot.
