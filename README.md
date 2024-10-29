# Benefícios da Azure

#### Alta Disponibilidade
- Recursos disponíveis sempre que necessário;
- Azure SLA (Service Level Agreement): é um compromisso da Microsoft em garantir a disponibilidade e o desempenho dos serviços que ela oferece na nuvem. 	
	- Basicamente, é um contrato que define o nível de serviço que você pode esperar ao usar produtos do Azure. 
    - O SLA especifica a porcentagem de tempo que um serviço estará disponível. Algumas porcentagens comuns de disponibilidade para diferentes serviços:
        - 99,9%: Significa que o serviço pode estar fora do ar por até 43,2 minutos por mês. Muitos serviços, como Azure App Service e Azure Storage, oferecem essa disponibilidade.
        - 99,95%: Isso permite um tempo de inatividade de até 21,6 minutos por mês. Serviços como Azure SQL Database em configurações específicas podem ter esse SLA.
        - 99,99%: Permite um tempo de inatividade de até 4,4 minutos por mês. Serviços críticos, como Azure Virtual Machines em zonas de disponibilidade, podem oferecer essa porcentagem.
        - 99,9999%: Este nível extremamente alto de disponibilidade é menos comum e permite um tempo de inatividade de apenas 31,5 segundos por mês, e pode ser visto em serviços como o Azure Cosmos DB, em certas configurações.
    - Se a Microsoft não conseguir cumprir o SLA, você pode ter direito a créditos na sua conta, o que pode ajudar a compensar a perda de serviço. 
    - Para que o SLA seja válido, você deve seguir certas práticas recomendadas, como configurar redundâncias e monitorar os serviços adequadamente.

#### Escabilidade
- Você paga apenas pelo que usa;
- É possível reduzir recursos caso a demanda caia e, assim, reduzir os custos;
- É possível escalar verticalmente a capacidade de processamento.

#### Elasticidade
- Se houver um salto repentino acentuado na demanda, os recursos implantados podem ser expandidos automaticamente ou manualmente;
- É possível adicionar máquinas virtuais ou contêiners por meio da expansão;
- Se houver quedas significativas na demanda, os recursos implantados poderão ser reduzidos horizontalmente de maneira automática ou manual.

#### Confiabilidade
- Devido ao design descentralizado , a nuvem dá suporte a uma infraestrutura confiável;
- Permite recursos implantados em várias regiões do mundo;
- Recursos podem lidar com falhas pois continuarão funcionando.

#### Previsibilidade
- Permite avançar com confianças, seja no desempenho dos recursos ou no custo, ambas influenciadas pelo Microsoft Azure Well-Architected Framework.

#### Segurança
- Não deve ser garantida somente pelo provider, a implementação é responsabilidade do cliente.
- Azure oferece recursos de segurança interna e externa, alguns pagos outros não.

#### Governança
- Gerenciamento e padrões dos recursos utilizados;
- Auditoria de nuvem: ajuda a sinalizar qualquer recurso que esteja fora de conformidade com os padrões corporativos ou os padrões de mercado e fornece estratégias de mitigação (resolução de problemas);
- Mantém a nuvem protegida e atualizada.

#### Gerenciabilidade
- Fornece opções de capacidade de gerenciamento como via portal, via linha de comando, via APIs ou usando o PowerShell;
- Diz respeito a gerenciar os recursos de nuvem, como escalar automaticamente a implantação de recursos com base na necessidade.
