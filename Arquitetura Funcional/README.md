# Detalhamento da POC

## LWSA Cloud Plataform

    Plataforma de cloud da LWSA. Responsável por prover os serviços e produtos a serem distribuídos aos clientes da Cloud LWSA.

    O LWSA Cloud Plataform é composto por uma série de microserviços responsáveis por se comunicarem com os serviços do Cloud Stack,  Min.io, GaleraCluester, OpenSearch, Kafka, Kubernets e qualquer outra plataforma a ser disponibilizada em nossa cloud.

    O LWSA é um integrador, responsável por prover as interfaces e contratos dos serviços que estão na rede interna da LWSA para o mundo. O console e o cli consumiram os seriços do LWSA Cloud Plataform.

    Exemplo, a partir do CLI um usuário gostaria de provisionar uma máquina virtual no CloudStack. O Usuário insere o comando no CLI, o CLI delega o comando ao API Gateway que contém o mapping para os paths do LWSA Cloud Plataform, responsáveis pelo provisionamente de máquinas virtuais. o LWSA Cloud Plataform, se comunica com o Cloud Stack, Sistemas de Billing e entre outras ferramentas para garantir o provisionamento seguro do recurso.