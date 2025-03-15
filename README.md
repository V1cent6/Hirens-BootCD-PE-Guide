# Hiren's BootCD PE - Guia 

## Introdução
O **Hiren's BootCD PE** (Preinstallation Environment) é um disco de recuperação baseado no Windows 10 PE, contendo diversas ferramentas úteis para diagnóstico e reparação de sistemas. 

É especialmente útil para:
- **Resetar passwords do Windows**
- **Recuperação de ficheiros apagados**
- **Diagnóstico de hardware**
- **Reparação do Windows**
- **Gestão de discos e partições**

---
## Download e Criação do Pen Drive Bootável

1. Baixar a ISO oficial: https://www.hirensbootcd.org/download/
2. Criar um pen drive bootável com **Rufus**:
   - Escolher a ISO do Hiren’s BootCD PE
   - Definir o sistema de ficheiros como **NTFS**
   - Selecionar **GPT** ou **MBR** dependendo do sistema
   - Clicar em **Iniciar**
3. Reiniciar o PC e iniciar a partir do pen drive
     - Para isso basta ir a Bios no *Boot Order* e por a pen em primeiro.

---
## Reset de Password do Windows

1. **Boot pelo Hiren’s BootCD PE**
2. Abrir o **Windows Login Unlocker** 
3. Selecionar o sistema operativo (se tiver apenas 1 sistema operativo instalado apaenas vai aparecer 1)
4. Escolher o utilizador e clicar em **Reset password** ou **Change password** para mudar  a palavra passe ou ate **Bypass** para a apenas conseguir entrar uma vez no windows swm ter pass mas depois de reniciar ou terminar sessao ja vai voltar a pedir a pass.
5. Definir uma nova password ou limpar a atual
6. Guardar as alterações e reiniciar o PC

---


## Contribuições
Queres ajudar a melhorar este guia? Faz um **fork** do repositório e envia um pull request!
