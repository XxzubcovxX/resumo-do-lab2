# Desafio de Projeto: Criando uma Máquina Virtual no Azure

Repositório criado para o desafio de projeto da [DIO](https://www.dio.me/) sobre a criação de uma Máquina Virtual (VM) no Microsoft Azure.

## 📝 Descrição

Este projeto documenta o passo a passo para criar e configurar uma máquina virtual com o sistema operacional Ubuntu Server 24.04 LTS através do portal do Azure.

## 🚀 Passo a Passo da Criação

### 1. Acesso ao Portal do Azure
O processo se inicia na página inicial do Microsoft Azure, onde temos uma visão geral dos serviços disponíveis. A partir daqui, navegamos para a seção de Máquinas Virtuais para dar início à criação do nosso recurso.



### 2. Navegação para o Serviço de Máquinas Virtuais
Na página inicial, selecionamos o serviço "Máquinas Virtuais". Esta ação nos leva ao painel de gerenciamento, onde todas as máquinas virtuais existentes são listadas e onde podemos iniciar a criação de uma nova.


### 3. Início da Criação da VM
No painel de Máquinas Virtuais, como nenhuma máquina foi criada ainda, a tela nos apresenta a opção para criar uma nova. Clicamos no botão "Criar" para sermos direcionados ao assistente de configuração.



### 4. Configurações Básicas da Instância
Nesta etapa, definimos as configurações essenciais do projeto e da instância.
- **Grupo de Recursos:** Criamos um novo grupo chamado `teste_group`.
- **Nome da Máquina Virtual:** Nomeamos nossa VM como `teste`.
- **Região:** Escolhemos a região `West Europe` para hospedar nosso recurso.



### 5. Definição da Imagem e Conta de Administrador
Dando continuidade à configuração, definimos:
- **Imagem:** Selecionamos a imagem `Ubuntu Server 24.04 LTS - Gen2` como sistema operacional.
- **Tamanho:** Optamos pelo tamanho `Standard_B1s`, que é elegível nos serviços gratuitos.
- **Autenticação:** Escolhemos o tipo de autenticação por `Chave pública SSH`, definindo o nome de usuário como `azureuser` e o nome do par de chaves como `Andre`.
- **Portas de Entrada:** Permitimos a porta `HTTP`, além da porta SSH que já é padrão.



### 6. Máquina Virtual Criada com Sucesso!
Após revisar e confirmar todas as configurações, a máquina virtual é provisionada e entra em execução. A tela final nos mostra um resumo completo da VM "teste", confirmando que o status está "Em execução" e apresentando informações importantes como o endereço IP público para conexão.



## 🛠️ Ferramentas Utilizadas
- [Microsoft Azure](https://portal.azure.com/)
- [Markdown](https://www.markdownguide.org/)
- [GitHub](https://github.com/)
