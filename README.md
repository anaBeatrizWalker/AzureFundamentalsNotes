# Tipos de Serviços da Azure

### Iaas (Infraestrutura como Serviço)
- Serviços e recursos onde o cliente/usuário tem mais acesso e liberdade de personalização;
- Também são os serviços em que o cliente necessita acompanhar e configurar, pois seu funcionamento não é garantido totalmente pelo provider;
- Oferece a maior gestão;
- Exemplos: servidores e armazenamento, firewalls/segurança de rede.

### Paas (Plataforma como Serviço)
- Oferece uma plataforma completa para o desenvolvimento, teste e implantação de aplicativos. 
- Com PaaS, os desenvolvedores têm acesso a ferramentas, serviços e recursos necessários para criar software, sem precisar se preocupar com a infraestrutura subjacente, como servidores e redes;
- Ofereca gestão intermediária;
- Exemplo: sistemas operacionais e ferramentas para desenvolvedores, análise de negócios de gerenciamento de banco de dados.

### Saas (Software como Serviço)
- Entrega software pela internet. Em vez de instalar e manter programas em computadores locais, os usuários acessam aplicativos por meio de um navegador. Isso elimina a necessidade de downloads e atualizações manuais, já que tudo é gerenciado pelo provider;
- Oferece a menor gestão;
- Exemplo: aplicativos hospedados, Microsoft 365, Google Workspace.

### Modelo de Responsabilidade Compartilhada
- Define as responsabilidades de segurança e gerenciamento entre o provedor de serviços em nuvem e o cliente;
- Essa divisão de responsabilidades ajuda a garantir que tanto o provedor quanto o cliente cumpram suas obrigações de segurança, criando um ambiente mais seguro e eficiente.

|  **Responsabilidade** | **Saas** | **Paas** | **Iaas** | **Local** 
| ------------- | ------------- | ------------- | ------------- | ------------- | 
| Informações e dados  | Cliente  | Cliente  | Cliente  | Cliente |     
| Dispositivos móveis e PCs  | Cliente  | Cliente  | Cliente  | Cliente  | 
| Contas e identidades  | Cliente  | Cliente  | Cliente  | Cliente |     
| Infraestrutura de identidade e diretório  | Compartilhada  | Compartilhada  | Cliente  | Cliente  | 
| Aplicativos  | Microsoft  | Compartilhada  | Cliente  | Cliente |
| Controles de rede  | Microsoft  | Compartilhada  | Cliente  | Cliente | 
| Sistema Operacional  | Microsoft  | Microsoft  | Cliente  | Cliente |       
| Hosts Físicos  | Microsoft  | Microsoft  | Microsoft  | Cliente  |  
| Rede física  | Microsoft  | Microsoft  | Microsoft  | Cliente |  
| Datacenter físico  | Microsoft  | Microsoft  | Microsoft  | Cliente  | 
