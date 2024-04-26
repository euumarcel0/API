API Flask para gerenciamento de recursos na AWS
Esta é uma API Flask para gerenciar recursos na AWS usando Terraform. Ela fornece endpoints para criar e destruir diversos recursos, como VPCs, subredes, grupos de segurança e instâncias EC2, entre outros.

Endpoints disponíveis
/login: Realiza o login na AWS executando terraform init no diretório especificado.
/aws/vpc: Cria uma VPC na AWS.
/aws/Subrede Pública: Cria uma subrede pública na AWS.
/aws/Subrede Privada: Cria uma subrede privada na AWS.
/aws/Gateway: Cria um Gateway de Internet na AWS.
/aws/Tabela de Rota: Cria uma tabela de rotas na AWS.
/aws/Grupo de Segurança Linux: Cria um grupo de segurança Linux na AWS.
/aws/Grupo de Segurança Windows: Cria um grupo de segurança Windows na AWS.
/aws/Máquina Virtual Windows: Cria uma instância EC2 Windows na AWS.
/aws/Máquina Virtual Linux: Cria uma instância EC2 Linux na AWS.
/aws/Load Balancer: Cria um Load Balancer na AWS.
/aws/destruir-recursos: Destrói todos os recursos criados na AWS.
Pré-requisitos
Certifique-se de ter instalado os seguintes componentes antes de executar a API:

Python 3.x
Flask
Flask Swagger
Flask Swagger UI
Flasgger
Flask CORS
Terraform
AWS CLI
Configuração
Clone este repositório.
Instale as dependências do Python listadas no arquivo requirements.txt.
Certifique-se de ter configurado corretamente as credenciais da AWS na máquina onde a API será executada.
Certifique-se de ter o Terraform instalado e configurado corretamente.
Execute o aplicativo Flask executando o arquivo app.py.
Documentação Swagger
Acesse /api/aws para visualizar a documentação Swagger, onde você pode encontrar detalhes sobre os endpoints disponíveis e como usá-los.

Notas
Este aplicativo foi desenvolvido para fins educacionais e de demonstração.
Certifique-se de entender os custos associados aos recursos criados na AWS.
Sempre siga as práticas recomendadas de segurança ao lidar com credenciais e recursos na nuvem.
Esse README combinado fornece uma visão geral do aplicativo Flask, seus endpoints e requisitos de configuração, além de incluir notas importantes sobre o uso do aplicativo.

Projeto API Azure e AWS
Este projeto consiste em uma API Flask para gerenciar recursos na nuvem, especificamente na Microsoft Azure. O código está estruturado para interagir com o Terraform, permitindo a criação, modificação e destruição de recursos de infraestrutura na Azure.

Estrutura do Projeto
app.py: Este arquivo contém o código principal da API Flask, onde são definidos os endpoints para interagir com os recursos na Azure.
/Azure: Este diretório contém os arquivos de configuração do Terraform para a criação dos recursos na Azure.
Dependências
Python 3.x
Flask
Flask Swagger
Flask Swagger UI
Flask CORS
Selenium
Terraform
Configuração
Certifique-se de ter todas as dependências instaladas.
Clone este repositório em sua máquina local.
Instale as dependências Python executando pip install -r requirements.txt.
Certifique-se de ter o chromedriver no seu PATH ou especifique o caminho diretamente no arquivo app.py.
Uso
Execute o arquivo app.py para iniciar o servidor Flask.
Acesse a documentação da API Swagger em /api/azure.
Use os endpoints fornecidos para criar, modificar e destruir recursos na Azure.
Endpoints Principais
/azure/criar-grupo-recursos: Cria um Grupo de Recursos na Azure.
/azure/criar-conta-armazenamento: Cria uma Conta de Armazenamento na Azure.
/azure/criar-vnet: Cria uma Virtual Network (VNET) na Azure.
/azure/criar-maquina-virtual-linux: Cria uma Máquina Virtual Linux na Azure.
/azure/destruir-recursos: Destrói todos os recursos criados na Azure.
Contribuindo
Sinta-se à vontade para abrir problemas ou enviar solicitações de pull para melhorias ou correções.
