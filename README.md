# Repositorio_Valente
Guia Detalhado: Como Criar uma Máquina Virtual no Azure

Passo a Passo para Criar uma Máquina Virtual no Azure:

Acessar o Portal Azure:

Acesse: https://portal.azure.com

Realize o login com sua conta da Microsoft.

Criar um novo recurso:

No menu lateral, clique em "Criar um recurso".

Selecione "Computar" > "Máquina virtual".

Configurações básicas:

Escolha a assinatura e grupo de recursos (ou crie um novo).

Dê um nome à VM e escolha a região onde ela será hospedada.

Escolha a imagem (ex.: Ubuntu, Windows Server).

Selecione o tamanho da máquina (CPU/RAM).

Configure o usuário administrador (nome e senha ou chave SSH).

Discos:

Escolha o tipo de disco de inicialização (SSD Padrão, Premium, etc).

Rede:

Selecione ou crie uma rede virtual e sub-rede.

Configure se deseja um IP público e regras de firewall (como porta 22 para SSH ou 3389 para RDP).

Opções avançadas:

Defina extensões, scripts de inicialização e opções de monitoramento (opcional).

Revisar e criar:

Clique em "Revisar + criar".

Verifique os detalhes e clique em "Criar".

Acesso à VM:

Após a criação, acesse a VM pelo menu "Máquinas Virtuais".

Utilize SSH (Linux) ou RDP (Windows) conforme configurado.

Resumo em Forma de Anotações: Como Funciona a Nuvem (Cloud Computing)

✅ Elasticidade: recursos sob demanda, escalam para mais ou menos conforme a necessidade.

✅ Modelo pay-as-you-go: você paga somente pelo que usar.

✅ Alta disponibilidade: servidores em múltiplas regiões e zonas de disponibilidade.

✅ Segurança: criptografia, controle de acesso, firewalls, e monitoramento constante.

✅ Gerenciamento Centralizado: console web unificado (ex.: portal Azure).

✅ Automatização: scripts, templates (ARM, Terraform), escalonamento automático.

✅ Serviços PaaS e SaaS: além de infraestrutura (IaaS), há serviços prontos para uso.
