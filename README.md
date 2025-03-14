# Hiren's BootCD PE - Guia Completo

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

1. Baixar a ISO oficial: [Site Oficial](https://www.hirensbootcd.org/download/)
2. Criar um pen drive bootável com **Rufus**:
   - Escolher a ISO do Hiren’s BootCD PE
   - Definir o sistema de ficheiros como **NTFS**
   - Selecionar **GPT** ou **MBR** dependendo do sistema
   - Clicar em **Iniciar**
3. Reiniciar o PC e iniciar a partir do pen drive
     - Para isso basta ir a Bios no *Boot Order* 

---
## Reset de Password do Windows

1. **Boot pelo Hiren’s BootCD PE**
2. Abrir o **NT Password Edit** (ou outra ferramenta equivalente)
3. Selecionar o disco onde está instalado o Windows
4. Escolher o utilizador e clicar em **Change Password**
5. Definir uma nova password ou limpar a atual
6. Guardar as alterações e reiniciar o PC

---
## Ferramentas Úteis Incluídas

### Gestão de Sistema:
- **NT Password Edit** – Reset de passwords do Windows
- **Mini Windows 10** – Ambiente Windows completo para recuperação
- **MBRFix** – Reparação de MBR (Master Boot Record)

### Diagnóstico e Reparação:
- **HDDScan** – Verificar estado do disco rígido
- **MemTest86+** – Teste de memória RAM
- **BlueScreenView** – Analisar erros do Windows (BSOD)

### Recuperação de Ficheiros:
- **Recuva** – Recuperação de ficheiros apagados
- **TestDisk** – Recuperação de partições

---
## Outros Casos de Uso

- **Clonagem de discos** com Clonezilla
- **Verificação de vírus e malware**
- **Edição do registo do Windows**

---
## Dicas e Recomendações

1-Criar backups antes de qualquer alteração
2-Usar um pen drive de pelo menos **8GB**
3-Testar primeiro em máquinas virtuais antes de usar em PCs reais

---
## Aviso Legal

O **Hiren’s BootCD PE** deve ser usado apenas para fins legais e técnicos. O uso indevido para aceder a sistemas sem autorização pode ser considerado uma infração à legislação de privacidade e segurança.

---
## Contribuições
Queres ajudar a melhorar este guia? Faz um **fork** do repositório e envia um pull request!
