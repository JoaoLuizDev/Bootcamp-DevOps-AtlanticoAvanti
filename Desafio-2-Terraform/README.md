# Desafio 2 - Terraform

Este diretório se refere ao desafio 2 do Bootcamp DevOps da Escola Atlântico Avanti.

## 📌 𝐎 𝐝𝐞𝐬𝐚𝐟𝐢𝐨 
Realizar o processo de provisionamento da infra na AWS via Terraform, onde será criado o security group, a EC2 e o deploy do site (via o arquivo script.sh), que será acessado via browser. 

## 🛠️ 𝐎 𝐪𝐮𝐞 𝐚𝐩𝐫𝐞𝐧𝐝𝐢 𝐞 𝐩𝐫𝐚𝐭𝐢𝐪𝐮𝐞𝐢
- Criação e configuração de Security Groups na AWS via Terraform;
- Provisionamento de instâncias EC2 usando Terraform;
- Configuração automática de instâncias EC2 com scripts bash (arquivo script.sh);
- Noções de infraestrutura como código (IaC) e gerenciamento de estados;
- Deploy de aplicações web utilizando infraestrutura automatizada;
- Monitoramento do status da infraestrutura provisionada.

## 💡 Objetivo do desafio
Demonstrar na prática como automatizar o provisionamento de recursos na AWS utilizando Terraform, enfatizando a criação de uma infraestrutura reproduzível e escalável, um dos pilares essenciais no universo DevOps.

## 𝐏𝐚𝐬𝐬𝐨 𝐚 𝐩𝐚𝐬𝐬𝐨 𝐝𝐨 𝐩𝐫𝐨𝐣𝐞𝐭𝐨
✅ Usar conta que ainda está no período free tier ou criar conta no provedor de nuvem AWS;  
✅ Instalar o Terraform Localmente: Baixe e instale o Terraform na máquina;  
✅ Adicionar o Provedor AWS no Terraform: No arquivo de configuração do Terraform, adicione o provedor AWS para que ele possa se comunicar com sua conta;  
✅ Clonar um repositório Git contendo arquivos de um site;   
✅ Escrever Arquivos de Configuração do Terraform;  
✅ Inicializar o Terraform;  
✅ Executar o Comando de Plan: O comando terraform plan exibe o plano de execução, mostrando os recursos que serão criados sem efetivamente criá-los ainda. Utilize este comando para visualizar a infraestrutura antes de criar qualquer recurso;  
✅ Executar o Comando Apply: Após verificar o plano e confirmar que tudo está correto, execute o comando terraform apply para provisionar a infraestrutura na AWS. Isso criará os recursos definidos nos arquivos de configuração;  
✅ Executar o Comando Destroy: Após finalizar o projeto e registrar as evidências, execute o comando terraform destroy para remover todos os recursos provisionados na AWS, garantindo que não haverá cobrança indesejada pelos recursos.

## 🎯 𝐑𝐞𝐬𝐮𝐥𝐭𝐚𝐝𝐨 𝐟𝐢𝐧𝐚𝐥 
O provisionamento foi concluído com sucesso, e o site foi implementado e está acessível via browser utilizando o IP público da instância EC2 configurada.




