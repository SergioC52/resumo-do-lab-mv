## Resumo: Maquinas Virtuais no Azure
Máquinas virtuais (VMs) no Microsoft Azure são instâncias de servidores virtuais criadas na nuvem, permitindo que usuários executem sistemas operacionais e aplicativos como fariam em servidores físicos. Funcionam como infraestrutura como serviço (IaaS), oferecendo flexibilidade para criar, configurar e gerenciar recursos conforme a necessidade.

O processo de criação envolve a escolha do sistema operacional, tamanho da VM (definindo CPU, memória e armazenamento) e configurações de rede. Após a criação, é possível acessar a VM remotamente para instalar softwares e realizar tarefas de administração.

Em termos de disponibilidade, o Azure oferece diversas opções para garantir a resiliência da aplicação:

Zonas de Disponibilidade: Distribui VMs entre datacenters físicos separados, garantindo alta resiliência a falhas, mas com um custo mais elevado.
Conjuntos de Disponibilidade: Agrupa VMs em diferentes racks dentro de um mesmo datacenter, protegendo contra falhas locais, sendo mais econômico, porém com menor proteção geográfica.
Escalonamento automático: Ajusta os recursos conforme a demanda, reduzindo custos em momentos de baixa utilização e aumentando a capacidade quando necessário.
Essas opções permitem que os recursos sejam adaptados conforme as necessidades de resiliência e orçamento, proporcionando flexibilidade tanto em termos de performance quanto de custos, tornando as VMs uma solução versátil para diferentes cenários de uso.
