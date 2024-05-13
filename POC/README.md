# Detalhamento da POC
Padrões de Imagens

RockyLinux // Ubuntu ? 

MinIO 

Criar, deleta e atualizar bucket.
Regra de ciclo de vida dos objetos.
Regra de migração hot pra cold.
Nível pra cluster, Conta, Bucket.
Versionamento de Objetos 
Site estático 

Kubernetes 


Terraform + Gestão de Imagens

Cloudstack Addon Infraestrutura (Arquitetura/Operação)
Cloudstack Suporte a qual versão do Kubernetes
Cloudstack Upgrade de versão
Cloudstack criar imagem 
Cloudstack Provisionamento de kubernetes
Cloudstack Gerencia do Manager e do Workers
Cloudstack Resize dos nodes de Managers e do Workers
Cloudstack Auto Scaling HPA 
Cloudstack Auto Scaling Métricas
Cloudstack Karpenter
Cloudstack SecComp, SeLINUX, Apparmor


Terraform + Gestão de Imagens + Ansible (configuration manager)

Provisionar as vms (SO, Pacotes, Tunnings) (terraform)
Provisionar o kubernetes (Multi CP) (Criar DNS, Fazer se conhecer e registrar) (Kubespray, ) (terraform, ansible, kubespray)


kubespray - https://github.com/kubernetes-sigs/kubespray
ansible - https://docs.ansible.com/ansible/latest/collections/kubernetes/core/docsite/kubernetes_scenarios/k8s_intro.html
terraform (ignition + userdata) 