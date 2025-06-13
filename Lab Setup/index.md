---
title: Step 1 – Download Kali Linux ISO
---

# 📥 Step 1 – Download Kali Linux ISO

## 🔗 Official Download

Visit the official [Kali Linux Downloads page](https://www.kali.org/get-kali/) and choose:

- **Installer ISO** (for bare metal)

Example:

![Image](images/1.png)

---
title: Step 2 – Create Bootable USB
---

# Step 2 – Create a Bootable USB Drive

## Rufus Download

- **Windows**: [Rufus](https://rufus.ie)

### ✅ Rufus (Windows)

1. Insert your USB drive (at least 8 GB).
2. Open Rufus.
3. Select:
   - **Device**: your USB stick
   - **Boot selection**: the `.iso` file
   - **Partition scheme**: MBR (or GPT for UEFI)
4. Click **Start**.

Example:
![Image](images/2.png)


---
title: Step 3 – BIOS/UEFI Configuration
---

# Step 3 – Configure BIOS/UEFI

## What to Do
*Note that you many need to determine your exact settings to boot from this drive*

1. Reboot your computer.
2. Press key to enter BIOS (often `F2`, `F10`, `DEL`, or `ESC`).
3. Enable/disable:
   - **Boot from USB**: Enable
   - **UEFI or Legacy Boot**:
     - Use UEFI if your USB was built for it
     - Use Legacy for MBR schemes
4. Set the **USB Drive** as the first boot option.


---
title: Step 4 – Install Kali Linux
---

## Boot from USB

1. Insert your bootable USB.
2. Power on and select **Boot Menu** (e.g., `F12`, `ESC`, or `F9`).
3. Select the USB.

## Begin Install

Choose from the menu:

- Graphical Install

### Graphical Install Steps:

1. Select Language, Region, and Keyboard.
2. Configure Network or skip.
3. Set hostname (e.g., `kali-machine`)
4. Create a user/password.
5. Choose disk partitioning:
   - Use entire disk (for full Kali install)
   - Manual (for dual boot)
6. Install the optional software and programs that come with the installation
7. Install GRUB when prompted.

## Final Reboot

Remove the USB when installation finishes. Boot into Kali. 
*You may need to go back into BIOS to choose the drive you installed Kali onto*

[Next ➡️ Required Software](../Required Software/)