Este trecho é uma tradução direta do repositório de William Hatheway (https://github.com/HathewayWill/DTC-MOSIT).

Hatheway, W., Snoun, H., ur Rehman, H., & Mwanthi, A. WRF-MOSIT: a modular and cross-platform tool for configuring and installing the WRF model [Computer software]. https://doi.org/10.1007/s12145-023-01136-y


# DTC Suite Multi Operational System Install Toolkit  

Este é um script **BASH** que fornece opções para instalar os seguintes pacotes do **DTC** em sistemas de 64 bits:  

- **MET v11.1.1**  
- **METplus v5.1.0**  

---

## 📌 Requisitos do Sistema  
- ✅ **Sistema 64 bits**  
- ✅ **Linux Debian Distro** (Ubuntu, Mint, etc.)  
- ✅ **Windows Subsystem for Linux (WSL)** (Debian, Ubuntu, Mint, etc.)  
- ✅ **Linux Fedora Distro**  
- ✅ **MacOS**  

---

## 💻 Instalação no MacOS  
Certifique-se de baixar e instalar o **Homebrew** antes de prosseguir com a instalação.  

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

brew install git

git clone https://github.com/HathewayWill/DTC-MOSIT.git

cd $HOME/DTC-MOSIT

chmod 775 *.sh

./DTC-MOSIT.sh 2>&1 | tee DTC_MOSIT.log
```

## 💾 Instalação com APT (Ubuntu, Debian, Mint, WSL)
📌 Certifique-se de baixar a pasta no seu diretório Home antes de executar os comandos.

cd $HOME
```bash
sudo apt install git -y

git clone https://github.com/HathewayWill/DTC-MOSIT.git

cd $HOME/DTC-MOSIT

chmod 775 *.sh

./DTC-MOSIT.sh 2>&1 | tee DTC_MOSIT.log
```

## 📦 Instalação com YUM/DNF (Fedora, Rocky Linux, CentOS 7)
📌 Certifique-se de baixar a pasta no seu diretório Home antes de executar os comandos.

```
cd $HOME

sudo (yum ou dnf) install git -y

git clone https://github.com/HathewayWill/DTC-MOSIT.git

cd $HOME/DTC-MOSIT

chmod 775 *.sh

./DTC-MOSIT.sh 2>&1 | tee DTC_MOSIT.log
```

🔍 Verificação do Sistema
O script verifica automaticamente:
✅ Arquitetura do sistema
✅ Espaço de armazenamento disponível

✅ Sistemas Testados
🖥 Ubuntu 22.04.4 LTS, Ubuntu 24.04.1 LTS, MacOS Ventura, MacOS Sonoma, CentOS 7, Rocky Linux 9, Windows Subsystem for Linux (Ubuntu). (Máquina do meu teste:	Ubuntu 22.04.5 LTS Release:	22.04)


⏳ Tempo estimado de instalação: ~10 a 30 minutos (com velocidade de download de 10 Mbps).
