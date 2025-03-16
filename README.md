# Hiren's BootCD PE - Guia Completo

## Introdução
O **Hiren's BootCD PE** (Preinstallation Environment) é um disco de recuperação baseado no Windows 10 PE, contendo diversas ferramentas úteis para diagnóstico e reparação de sistemas. 

É especialmente útil para:
- **Resetar passwords do Windows**
- **Entre outros**

---
## Download e Criação do Pen Drive Bootável

1. Baixar a ISO oficial: [Site Oficial](https://www.hirensbootcd.org/download/)
2. Criar um pen drive bootável com **Rufus**:
   - Escolher a ISO do Hiren’s BootCD PE
   - Definir o sistema de ficheiros como **NTFS**
   - Selecionar **GPT** ou **MBR** dependendo do sistema
   - Clicar em **Iniciar**
3. Reiniciar o PC e iniciar a partir do pen drive:
   - Para isso, aceder à BIOS/UEFI e modificar a ordem de boot para colocar o pen drive em primeiro lugar.

---
## Reset de Password do Windows

1. **Iniciar o PC pelo Hiren’s BootCD PE**
2. Abrir o **Windows Login Unlocker**
3. Selecionar o sistema operativo (se existir apenas um, será automaticamente reconhecido)
4. Escolher o utilizador e selecionar uma das opções:
   - **Reset password** – Apagar a password existente
   - **Change password** – Definir uma nova password
   - **Bypass** – Permitir o login sem senha apenas uma vez (após reiniciar ou terminar sessão, a password será necessária novamente)
5. Aplicar as alterações e reiniciar o PC

---
## Contribuições
Queres ajudar a melhorar este guia? Faz um **fork** do repositório e envia um pull request!

---

# English Version

## Introduction
**Hiren's BootCD PE** (Preinstallation Environment) is a recovery disk based on Windows 10 PE, containing several useful tools for diagnosing and repairing systems.

It is especially useful for:
- **Resetting Windows passwords**
- **File recovery**
- **Hardware diagnostics**
- **Windows repair**
- **Disk and partition management**

---
## Download and Create a Bootable USB Drive

1. Download the official ISO: [Official Site](https://www.hirensbootcd.org/download/)
2. Create a bootable USB drive using **Rufus**:
   - Select the Hiren’s BootCD PE ISO
   - Set the file system to **NTFS**
   - Choose **GPT** or **MBR**, depending on your system
   - Click **Start**
3. Restart the PC and boot from the USB drive:
   - To do this, access the BIOS/UEFI and modify the boot order to prioritize the USB drive.

---
## Windows Password Reset

1. **Boot from Hiren’s BootCD PE**
2. Open **Windows Login Unlocker**
3. Select the operating system (if only one OS is installed, it will be detected automatically)
4. Choose the user and select one of the following options:
   - **Reset password** – Remove the current password
   - **Change password** – Set a new password
   - **Bypass** – Temporarily log in without a password (after restarting or logging out, the password will be required again)
5. Apply the changes and restart the PC

---
## Contributions
Want to help improve this guide? Fork the repository and submit a pull request!


