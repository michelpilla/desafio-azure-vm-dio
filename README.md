# desafio-azure-vm-dio


#  Desafio DIO: Gerenciamento de Máquinas Virtuais no Azure (Windows)

Este repositório documenta o desafio prático realizado no Bootcamp AZ-104 da DIO, com foco na criação, configuração e gerenciamento de máquinas virtuais no Microsoft Azure.

##  Objetivos

- Criar e configurar uma VM Windows no Azure
- Aprender sobre conectividade, segurança e gerenciamento
- Consolidar conhecimentos práticos sobre IaaS no Azure

##  Conceitos Aplicados

- Criação de Resource Groups
- Provisionamento de máquinas virtuais com Windows Server
- Abertura e controle de portas no NSG
- Configuração de IP público e nome DNS
- Acesso remoto via RDP
- Gerenciamento de recursos pelo Azure Portal e CLI

##  Etapas Realizadas

1. **Criação do Resource Group**
2. **Criação da Máquina Virtual**
   - SO: Windows Server 2022 Standard (Gen2)
   - Tamanho: Standard B2ms
   - Autenticação: Nome de usuário e senha
3. **Configuração do NSG (Network Security Group)**
   - Abertura da porta 3389 para acesso remoto
4. **Acesso Remoto**
   - Conexão via Remote Desktop (mstsc.exe) ou pode ser usar 
   - Teste de acesso ao sistema
5. **Instalações e Configurações Iniciais**
   - Ativação de serviços
   - Instalação de softwares (Ex: IIS com `Add-WindowsFeature -Name Web-Server`)
6. **Encerramento e Limpeza**
   - Deallocar a VM para economizar créditos
   - Excluir recursos não utilizados

##  Dicas e Aprendizados

- Sempre use senhas fortes e seguras para acesso RDP
- Reduza custos desligando ou desalocando VMs fora de uso
- Use tags para organização e gerenciamento dos recursos



