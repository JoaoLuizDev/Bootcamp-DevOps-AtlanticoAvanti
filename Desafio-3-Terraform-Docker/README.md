# Desafio 3 - AWS + Terraform + Docker

Este diretório se refere ao desafio 3 do Bootcamp DevOps da Escola Atlântico Avanti.

## 📌 𝐎 𝐝𝐞𝐬𝐚𝐟𝐢𝐨 
O desafio consiste em realizar o processo de provisionamento da infra na AWS via Terraform, onde será criado o security group, a EC2, instalar o Docker, via o arquivo de “script.sh”, e subir uma imagem com uma aplicação rodando.

## 🛠️ 𝐎 𝐪𝐮𝐞 𝐚𝐩𝐫𝐞𝐧𝐝𝐢 𝐞 𝐩𝐫𝐚𝐭𝐢𝐪𝐮𝐞𝐢
- Criação e configuração de Security Groups na AWS via Terraform;
- Provisionamento de instâncias EC2 utilizando Terraform;
- Instalação automatizada do Docker em instâncias EC2 usando scripts bash (arquivo script.sh);
- Aplicação de infraestrutura como código (IaC) para automação e gerenciamento de estados;
- Deploy de aplicações web em contêineres Docker usando infraestrutura automatizada;
- Monitoramento do status da infraestrutura provisionada e da aplicação em execução.

## 💡 Objetivo do desafio
Automatizar o provisionamento e a configuração de uma infraestrutura na AWS usando Terraform e Docker, reforçando práticas de infraestrutura como código (IaC) para criar ambientes escaláveis e reproduzíveis.

## 𝐏𝐚𝐬𝐬𝐨 𝐚 𝐩𝐚𝐬𝐬𝐨 𝐝𝐨 𝐩𝐫𝐨𝐣𝐞𝐭𝐨
✅ Usar conta que ainda está no período free tier ou criar conta no provedor de nuvem AWS;  
✅ Instalar o Terraform Localmente: Baixe e instale o Terraform na máquina;  
✅ Adicionar o Provedor AWS no Terraform: No arquivo de configuração do Terraform, adicione o provedor AWS para que ele possa se comunicar com sua conta;  
✅ Clonar um repositório Git contendo arquivos de um site;   
✅ Escrever Arquivos de Configuração do Terraform;  
✅ Inicializar o Terraform;  
✅ Executar o Comando de Plan: O comando terraform plan exibe o plano de execução, mostrando os recursos que serão criados sem efetivamente criá-los ainda. Utilize este comando para visualizar a infraestrutura antes de criar qualquer recurso;  
✅ Executar o Comando Apply: Após verificar o plano e confirmar que tudo está correto, execute o comando terraform apply para provisionar a infraestrutura na AWS. Isso criará os recursos definidos nos arquivos de configuração;  
✅ Usar o Docker para subir uma imagem da aplicação na instância EC2 provisionada;  
✅ Executar o Comando Destroy: Após finalizar o projeto e registrar as evidências, execute o comando terraform destroy para remover todos os recursos provisionados na AWS, garantindo que não haverá cobrança indesejada pelos recursos.

## 🎯 𝐑𝐞𝐬𝐮𝐥𝐭𝐚𝐝𝐨 𝐟𝐢𝐧𝐚𝐥 
O provisionamento foi concluído com sucesso. A instância EC2 foi configurada, o Docker foi instalado, e a aplicação está em execução. A aplicação pode ser acessada via browser utilizando o IP público da instância EC2.

![1](https://github.com/user-attachments/assets/94b40413-647f-4ed3-8181-d188a5352bea)
![2](https://github.com/user-attachments/assets/aa98bc29-8953-47fa-807c-c21f133d8b81)
![Captura de Tela (549)](https://github.com/user-attachments/assets/94d2c111-765f-4c74-b9a1-911b89163891)
![Captura de Tela (550)](https://github.com/user-attachments/assets/b5d01c1f-1a4a-476a-9c3b-67b11ca12f1f)
![Captura de Tela (551)](https://github.com/user-attachments/assets/1931e0e2-8af9-42b8-bd7d-b44f0c18c230)
![Captura de Tela (552)](https://github.com/user-attachments/assets/3399b524-c7af-45a6-80ab-90ceaaf308ba)
![Captura de Tela (553)](https://github.com/user-attachments/assets/e40e5ce6-f3f2-42f8-8c4d-ee94002f167a)
![Captura de Tela (554)](https://github.com/user-attachments/assets/c1738129-dd91-4a7f-aaa5-57406995189d)
![Captura de Tela (555)](https://github.com/user-attachments/assets/a85ebd12-2c4b-46e4-8e1d-1437a03912b8)

