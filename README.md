# Projeto Estácio 04 - Integração Claude e Ollama em Máquina Virtual

[![Estácio](https://img.shields.io/badge/Instituição-Estácio-blue.svg)](https://estacio.br)
[![Status do Projeto](https://img.shields.io/badge/Status-Em%20Desenvolvimento-green.svg)]()

## 📝 Descrição do Projeto
Este repositório contém a documentação, scripts e arquivos de configuração referentes ao **Projeto 04** da Universidade Estácio. O principal objetivo deste projeto é configurar e provisionar um ambiente de Máquina Virtual (VM) capaz de orquestrar modelos de Inteligência Artificial, integrando a API do **Claude** (Anthropic) e modelos de linguagem locais rodando via **Ollama** (versão/modelo 3.4).

## 🛠️ Tecnologias Utilizadas
* **Virtualização:** VirtualBox / VMware (ou Hyper-V)
* **Sistema Operacional da VM:** Linux (Ubuntu 22.04/24.04 recomendado)
* **IAs Utilizadas:** 
  * API do Claude (Anthropic) para tarefas complexas baseadas em nuvem.
  * [Ollama](https://ollama.com/) para execução de LLMs open-source localmente na máquina virtual.
* **Linguagem:** Python 3.10+ (ou a linguagem utilizada para a integração)

## ⚙️ Pré-requisitos
Antes de começar, você precisará ter instalado em sua máquina host:
* Um software de virtualização (VirtualBox, VMware).
* Uma imagem ISO de uma distribuição Linux (ex: Ubuntu Server).
* Acesso à internet para download dos pacotes e modelos do Ollama.
* Chave de API do Claude (Anthropic API Key).

## 🚀 Instalação e Configuração

### 1. Preparando a Máquina Virtual
1. Crie uma nova VM alocando pelo menos **4 cores de CPU** e **8GB de RAM** (recomendado para rodar modelos locais no Ollama de forma fluida).
2. Instale o sistema operacional Linux.
3. Atualize os pacotes do sistema:
   ```bash
   sudo apt update && sudo apt upgrade -y
