<img width="816" height="520" alt="image" src="https://github.com/user-attachments/assets/af28dd84-8da4-4611-9b8b-5529f0cc2eba" />


# RAZXOS-W11
**R**og **A**lly **Z**x **O**perating **S**ystem - Windows 11

This repository will explain how to create Windows 11 with all drivers and apps needed for the Rog Ally Z1 Extreme console
  - this should also work with Z1 but i don't have this model

# REQUIERMENTS

For this project and on my case
- Windows 11 Enterprise iso (W11H and W11P also works)
- Rufus
- USB-C HUB or Docking Station
- Keyboard + Mouse (more easy with these)
- 32gb USB Stick (3gen1 or 2) or USB-C
- Rog Ally drivers, especially **NVIDIA MCP**
- Patience

# ROG ALLY DRIVERS
 - https://rog.asus.com/gaming-handhelds/rog-ally/rog-ally-2023/helpdesk_download/
 -   **Advice** : download only Wifi drivers, Armoury Crate and let Windows Update let the work
 - **NVIDIA MCP** : go to https://www.nvidia.com/fr-fr/drivers/
 - download latest **NVIDIA GEFORCE** drivers, extract with 7zip and place folder to the root of your USB stick
 - go to **Device Management** by clicking right on **windows start incon**
 - choose **unknown device**, update drivers and choose where the extracted folder is located
   
# EXPLANATIONS
  - I choose W11 ENT because this version is the most close to a debloated iso
   - no crappy apps like weather, actuallity, solitaire and so on
   - it offer a better MSTSC if you want to play on your regular computer or acces to Admin session if you want to apply updates while playing your games
   
- I use Rufus instead of Microsoft Media Creation tool
   - Official tool prepare stick on FAT32 and have limitation (files limited to 4gb)  


# BUILD ISO

  Open Rufu and choose iso you want to use
    - Prefer **NTFS** instead of **FAT32**
<img width="518" height="653" alt="image" src="https://github.com/user-attachments/assets/d683dd6d-beef-4d20-8af9-a9e8743612a6" />

   - You can choose local account but it is recommended to deactivate all
        
        <img width="573" height="649" alt="image" src="https://github.com/user-attachments/assets/580674be-f4f3-440c-950b-f7ec56fbbd7c" />
        

  Once iso is burned, plug your stick on console and launch installation
  Depending of your SSD (512 or more), you can create partitions or let simply as default
  Once installation is done,with keyboard ==> CTRL + SHIFT + F3
    - this will enter Windows in SYSPREP MODE
      - this mode will allow you to 
        - add needed apps
          - VC Runtimes
          - Vulkan and Open CL addons
          - Drivers
            - For the unknown driver, please find last NVIDIA MCP drivers
          - Application you want as default launcher
            - From Asus
            - From Playnite
            - And so on.....
          - All Windows Updates
          
- **FOR ALL MODIFICATIONS - you have to choose AUDIT MODE AND REBOOT**

<img width="339" height="260" alt="image" src="https://github.com/user-attachments/assets/45a40fae-775d-4544-8cf0-81515742247e" />



Once all modification is done :

<img width="342" height="265" alt="image" src="https://github.com/user-attachments/assets/3a48d433-d0cf-4093-86eb-c0b2809230c8" />


When console if off, turn on and boot to usb stick
You will enter to Windows installation
With keyboard, enter SHIFT + F10 to have command prompt


# AT LAST

if you want to have the build I made, I will share link of my own **INSTALL.ESD** once all steps are finished
This file will not have apps **My Asus** ,**GlideX** and **Edge** because useless for me and my way to have a true hendheld console

**TO BE CONTINUED**





