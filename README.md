<img width="1244" height="460" alt="WSL" src="https://github.com/user-attachments/assets/e1dd7c45-9d8d-4d3b-bee6-94855d6312ef" />




# Welcome to GitHub WSL!

This is your README. READMEs are where you can communicate what your project is and how to use it.

Write your name on line 6, save it, and then head back to GitHub WSL.
# 🐧 Tutorial de Instalação do WSL (Windows Subsystem for Linux)

Este repositório contém um **guia passo a passo para instalar e configurar o WSL** no Windows 10 ou Windows 11, permitindo rodar um ambiente Linux diretamente no Windows.

---

## 📋 Pré-requisitos

- Windows 10 **versão 2004 ou superior** (Build 19041+)
- Windows 11
- Conta com **permissões de administrador**
- Virtualização ativada no BIOS/UEFI

---

## 🚀 Instalação Rápida (Recomendada)

### 1️⃣ Abrir o PowerShell como Administrador
- Clique com o botão direito no **Menu Iniciar**
- Selecione **Windows Terminal (Admin)** ou **PowerShell (Admin)**

### 2️⃣ Executar o comando de instalação
```powershell
wsl --install
---
Esse comando irá:

Ativar o WSL

Instalar o WSL 2

Instalar o Ubuntu como distribuição padrão

4️⃣ Criar usuário Linux

Defina um nome de usuário

Crie uma senha (não aparece ao digitar — comportamento normal)

✅ Pronto! O WSL está instalado e funcionando.

---

Verificando a instalação

Para listar as distribuições instaladas:

wsl -l -v


Para verificar a versão do WSL:

wsl --version

---
Instalando outras distribuições Linux

Listar distribuições disponíveis:

wsl --list --online


Instalar uma distro específica (exemplo: Debian):

wsl --install -d Debian

⚙️ Configurações úteis
Definir WSL 2 como padrão
wsl --set-default-version 2

Converter uma distro do WSL 1 para WSL 2
wsl --set-version Ubuntu 2
