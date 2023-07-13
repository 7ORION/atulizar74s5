#!/bin/bash

# Atualizar sistema operacional
sudo apt update
sudo apt upgrade -y

# Instalar Python 3 e pip
sudo apt install -y python3 python3-pip

# Verificar a versão do Python 3
python3 --version

# Instalar dependências com o pip
pip3 install subprocess

# Instalar pacote iputils-ping
sudo apt install -y iputils-ping

# Instalar pacote nano
sudo apt install -y nano

# Instalar pacote python3-dev
sudo apt install -y python3-dev

# Instalar pacote build-essential
sudo apt install -y build-essential

# Atualizar o pip para a versão mais recente
pip3 install --upgrade pip

# Instalar a biblioteca wheel
pip3 install wheel

# Dar permissão de execução ao script scanner.py
chmod +x scanner.py

echo "Configuração da VPS concluída."
