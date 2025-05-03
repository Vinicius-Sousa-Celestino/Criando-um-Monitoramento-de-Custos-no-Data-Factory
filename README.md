# Criando-um-Monitoramento-de-Custos-no-Data-Factory
Repositório para a entrega do Lab Project, último fundamento do Azure no bootcamp Microsoft AI for Tech - Azure Databricks

Conceitos e práticas aprendidas:
1. Criação de recursos no Azure
2. Monitoriamento de custos com um Data Factory
3. Simples configuração de um Databricks Service

Bom, em resumo, seguindo a risca o andar do curso, fiz a criação e configuração de um grupo de recursos, e dentro dele, um Data factory, além da elaboração de um Azure Databricks Service!

![image](https://github.com/user-attachments/assets/effb82b8-3eba-4765-af76-558c27e94dc4)

Azure Databricks

Objeivo: Realizar a criação do recurso Azure Databricks Service, com o start, fazer a configuração do cluster, upar uma base do adventure works e subir no catalogo, rodar um simples query em pyspark

Problema encontrato: Criação de cluster - por utilizar a versão student do azure, estou limitado a utilizar 6 vCPUs no meu cluster. Tentei algumas distribuuições diferentes de cores, entre o Worker Type e Driver Type, porém o databricks só me disponibilizava VMs com 4 Cores cada

Ainda sem solução, os indicadores do Data Factory ainda não aponta consumos.
