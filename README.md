# Anotações certificação AZ-900

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194557227-2e1ab0b4-a3dd-41fd-b93e-d85da218c2c5.png" width="300px" />
</div>

## Módulo 1: Conceitos de nuvem

### **O que é a nuvem?** 
Computação em nuvem é a entrega de serviços de computação por meio da internet. É uma forma de alugar capacidade computacional e armazenamento do datacenter de terceiros. O provedor de nuvem é responsável por manter a infraestrutura disponível para você.
- Amazon foi a pioneira na computação em nuvem com o serviço da AWS.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194125448-b11da58e-c1b5-4243-8999-cef507d9ba74.png" width="250px" />
</div>

### **Nuvem pública, híbrida e privada:**
Existe uma diferença entre os serviços disponíveis na nuvem, esses serviços são divididos em: Serviços de nuvem pública, híbrida e privada.
- **Nuvem pública:** Qualquer pessoa pode contratar esse serviço, por isso é pública. Nesse tipo de serviço os servidores são totalmente alugados pelos usuários, ou seja, a infraestrutura fica totalmente com o provedor do serviço.
- **Nuvem privada:** As organizações criam um embiente em nuvem em seu datacenter, não tendo acesso de usuários de fora da organização. Nesse tipo de serviço os servidores são comprados e pertencem a organização, desde sua implantação até manutenção. Uma característica da nuvem privada é a necessidade de um investimento inicial para implantação do hardware.
- **Nuvem híbrida:** Esse serviço possui tanto a nuvem pública quanto a nuvem privada. Esse tipo de serviço é utilizado quando a organização possui seus próprios equipamentos mas o armazenamento é excedido; nesse caso a nuvem híbrida vira uma opção muito viável, uma vez que gastar com mais equipamentos é desnecessário e migrar completamente deixando seus atuais equipamentos sem utilidade também é um gasto desnecessário. Dessa forma, une-se a infraestrutura já existente e os serviços da nuvem.

### **Benefícios da nuvem:**
- **Escalabilidade:** Capacidade de aumentar ou diminuir os recursos automaticamente;
- **Alcance global:** Pode-se acessar data centers no mundo inteiro, podendo alocar seus servidores em diversas regiões do planeta;

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194128696-ed528977-06c7-4f78-855e-3e16ee0e44b6.png" width="850px" />
</div>
 
- **Agilidade:** A agilidade na nuvem refere-se a facilidade e rapidez de criar novos recursos e instâncias
- **Recuperação de desastre:** Caso pegue fogo em algum lugar ou ocorra algum desastre, você tem uma recuperação de desastre em algum outro ponto (caso configurado outro ponto do seu serviço), ou seja, existem Backup's em outros data center;
- **Tolerância a falhas:** Diz respeito a quanto o ambiente pode ser acarretado por falhas e sobrevive mesmo com elas, o quanto ele é tolerante a falhas;
- **Elasticidade:** É um dos maiores e mais conhecidos benefícios da nuvem. Elasticidade é quanto o recurso pode se moldar quanto a demanda. Um exemplo bem claro disso é na famosa black friday que a demanda/acessos sobem muito; com a nuvem os recursos acompanham a demanda;
- **Considerações sobre custo preditivo:** Calcula quanto precisará do recurso e o quanto gastará com isso;
- **Segurança:** É um dos maiores benefícios da nuvem, existem diversos recursos que protegem seus dados na nuvem, além da proteção dos próprios data centers dos provedores.

### **Modelo de despesa: Comparação entre CapEx e OpEx:** 
Na nuvem existem dois modelos de despesa: CapEx (Capital Expenditure) e OpEx (Operational Expenditure).
- **CapEx:** Nesse modelo de despesa está incluso o investimento inicial em máquinas, equipamentos e outros bens nas instalações na empresa. É o modelo presente na nuvem privada.
- **OpEx:** No modelo OpEx os gastos são feitos conforme o necessário, ou seja, é feito pagamento conforme o uso do serviço. É o modelo presente na nuvem pública.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194131746-87742188-df1a-49d7-af7e-bbe23d5c5c28.png" width="500px" />
</div>

### **Modelo baseado em consumo:**
Na nuvem os usuários pagam pelos recursos que utilizam. Os modelos de núvem pública são basicamente divididos em três: IaaS, PaaS e SaaS.
- **IaaS:** Nesse modelo o usuário fica responsável pelas atualizações e instalações, o usuário gerencia o hardware para o seu aplicativo. Lembrando que, embora as atualizações e instalações fiquem como responsabilidade do usuário, toda a parte física de instalação e manutenção é realizada pelo provedor da nuvem.
- **PaaS:** No PaaS o nível de gerenciamento da máquina é menor pela parte do usuario. Nesse modelo o usuário somente gerencia as aplicações presentes no servidor.
- **SaaS:** Nesse modelo temos os softwares prontos que entregam um serviço, o usuário para com base no uso; como exemplos de SaaS temos Netflix, Spotify, HBO, etc. São softwares que você acessa pela Internet e já estão prontos para o uso.

## Módulo 2: Principais serviços do Azure ##
### **O que é o Azure?**
"Azure é um conjunto de serviços de nuvem em constante expansão, que ajuda a sua organização a superar os desafios empresariais e atuais e se preparar para os desafios futuros. No portal do Azure é possível acessar e utilizar as suas ferramentas; é possível compilar, gerenciar e monitorar tudo."

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194134675-2eb508d3-5f88-49aa-8cf2-e5d0bf6d5795.png" width="500px" />
</div>

### **Portal do Azure:**
O portal do Azure é utilizado para gerenciamentos dos recursos e interações através da GUI (Graphical User Interface, Interface Gráfica do Usuário).

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194428408-885166db-b915-4bc2-a4fc-28ccfa6abd66.png" width="760px" />
</div>

### **Assinatura do Azure:**
Para começar a utilizar o serviço do Azure é necessário possuir uma assinatura. Uma assinatura é uma unidade lógica de serviços do Azure vinculada a uma conta.
Uma conta pode ter uma ou mais assinaturas; essas assinaturas podem possuir diferentes níveis de gerenciamento de acesso. Geralmente são feitas assinaturas diferentes para ambientes diferentes como departamentos, equipes, etc.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194135305-7191ba42-4158-4ce6-8472-af4332eb18f9.png" width="760px" />
</div>

### **Regiões:**
A Microsoft está espalhada em vários lugares do mundo. Para cada região, existe um par de regiões que é feito para replicar os dados (esses pares ficam no mínimo 300 milhas de distância). Região é uma área do planeta que contém pelo menos um data center (normalmente são vários) e conectados em rede com uma baixa latência. O Azure tem mais regiões globais do que qualquer outro provedor de nuvem. 
- **Regiões especiais do Azure:** Us DoD Central, US Gov Virginia, US Gov lowa e outras: são regiões físicas e lógicas isoladas de rede pertencentes ao Azure para agências e parceiros do governo dos Estados Unidos utilizarem. Esses data centers são acessados e operadores por pessoas selecionadas dos Estados Unidos.
- **Conexão com a China:** O governo chinês é um governo fechado em relação a empresas de fora que vão monitorar dados de lá. Como alternativa a isso, o intermédio entre a China e a Azure é realizado pela empresa 21Vianet que tem parceria com a Microsoft. 

### **Zonas de disponibilidade**
São data centers fisicamente separados na mesma região. Esses data centers, embora estejam na mesma região, possuem equipamentos de alimentação elétrica, refrigeração e rede exclusivos de cada um. 
No Azure existem dois serviços que oferecem suporte a zonas de disponibilidade: Serviços zonais e serviços com redundância de zona.
- **Serviços zonais:** Nesse serviço você escolhe somente uma zona específica para colocar seu recurso.
- **Serviços com redundância de zona:** Nesse serviço a plataforma replica automaticamente os recursos entre as zonas.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194145147-ee909f86-6956-46b0-8136-cac7752611df.png" width="450px" />
</div>

### **Recursos do Azure:**
O Azure oferece diversos recursos dentro da sua plataforma, entre eles: Criação de máquinas virtuais, banco de dados, armazenamento, entre outros.

- **Grupo de recursos:**
O grupo de recursos reúne os recursos e agrupam aqueles que estão conectados. Por meio do grupo de recursos é possível definir configurações em comum entre os recursos presentes nele.

- **Azure Resource Manager:**
Gerencia como os seus recursos serão alocados e criados. As solicitações para criar ou atualizar um recurso são feitas por meio desse recurso.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194149632-bbbf0354-63b1-4f5e-ac9f-e548a7a1660b.png" width="600px" />
</div>

- **Grupos de gerenciamento:** 
O grupo de gerenciamento permite que você gerencie assinaturas, permitindo inclusive atribuir permissõoes para os recursos.

Na imagem abaixo as chaves são as assinaturas e os demais símbolos os grupos. É possível notar que as assinaturas e grupos são divididos pelos departamentos da empresa que provavelmente possuem permissões diferentes.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194150428-35df02bc-7ef6-4c47-b042-5d160197beec.png" width="800px" />
</div>

### **Principais serviços do Azure:**

**1. Computação:**

**Máquinas virtuais:**
Máquinas virtuais são aplicações que permitem rodar um sistema operacional em cima de outro, ou seja, um "computador dentro do computador".
No Azure é possível criar quantas máquinas virtuais forem necessárias com os mais diversos tipos de configuração. É possível escolher entre Linux e Windows.
A plataforma garante: Maior controle do seu orçamento (pagará somente pelo tempo que usar), capacidade de expansão de um ambiente de uma a milhares de máquinas em minutos e criptografia de dados confidenciais.

**Serviço de aplicativo:**
Plataforma para gerenciar, criar, implantar e escalar aplicativos Web e API's com rapidez. Permite trabalhar com .NET, .NET Core, Node.js, Java, Python ou PHP.
A plataforma garante: Serviço totalmente gerenciado com manutenção de infraestrutura, implantações sem tempo de inatividade, suporte para redes virtuais e padrões de segurança e conformidade rigorosos.

**Serviços de contêiner:** No contêiner você trabalha como se fosse em uma VM, entretanto, o Sistema Operacional utilizado é o presente na máquina, não dando liberdade para escolher um Sistema Operacional diferente do que está presente no servidor. 
A plataforma garante: Agilidade, portabilidade e escalabilidade rápida.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194376940-8cc5ab80-50ae-408b-b9ca-9ffc2853eb5e.png" width="800px" />
</div>

**2. Rede:**

O gerenciamento de redes virtual do Azure um serviço que permite agrupar, configurar e implantar redes virtuais em assinaturas da plataforma. É possível definir grupos de rede para identificar e configurar suas redes virtuais.
A plataforma garante: serviço altamente escalonável e disponível, baixa latência e alta largura de banca.

**3. Armazenamento:**

O serviço de armazenamento do Azure é uma solução de nuvem para armazenar dados modernos. Os dados salvos podem ser acessar por HTTP.
O armazenamento de dados possui as camadas: Hot, Cool e Archive. 
- **Hot:** Armazenamento que os dados são acessados com frequência.
- **Cool:** Dados acessados com pouca frequência por pelo menos 30 dias.

- **Standard general-purpose v2:** Também conhecidas como contas de armazenamento, standard general-purpose refere-se a soluções de armazenamento que dão suporte a serviços como Blob, Queue e Table storage.

**4. Banco de dados:**

Banco de dados é um serviço de nível PaaS (Plataforma como serviço) que trata da maioria das funções de gerenciamento de banco de dados. Existem os BD relacionais e não relacionais.
- Azure Cosmos DB: É um serviço não relacional, ou seja, funciona com base em Chave = Valor. Não é possível separar os dados por entidades.
- Banco de dados SQL do Azure, BD Azure para MYSQL e BD do Azure para PostgreSQL: São banco de dados relacionais, podendo ser separados por tabelas como é feito no MYSQL.

### **Azure PowerShell:**
Também conhecido como Azure CLI, é a linha de comando de interações baseadas em automação com o Azure. Nessa CLI é possível acessar sua conta por meio do comando "Connect-AzAccount" e até gerenciar seus recursos por meio de linhas de condução. 

## Módulo 3: Principais soluções

**Análise dados com IA e Machine Learning:**

A Microsoft oferece uma certificação própria para inteligência artificial chamada AI - 900 que aborda conceitos de Inteligência Artificial e Machine Learning (Aprendizado de máquinas). O uso dessas tecnologias permite análise de dados conforme o serviço escolhido. 
- Azure Machine Learning: baseado em nuvem para aprendizado de máquinas.
- Serviços cognitivos: Inteligência artificiais para ver, ouvir, falar, entender e interpretas as necessidades do usuário.
- Serviço bot do azure: Desenvolver bots inteligentes, de nível empresarial.

**IoT:**

A internet das coisas vem tomando cada vez mais espaço no ambiente de trabalho com o uso de aplicativos inteligentes como câmeras para monitor e analisar o desempenho de máquinas, pessoas, setores, etc.
O Azure possui um HUB IoT que permite a comunicação e gerenciamento de dispositivos. 

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194397102-a59857ce-dff6-4b00-af62-293889491e8a.png" width="600px" />
</div>

## Módulo 4: Segurança

Uma das maiores características da plataforma é a segurança que possui e oferece. Desde a segurança física dos seus data centers até a de seus recursos virtuais. Com a plataforma do Azure a empresa não precisará se preocupar com atualizações de hardwares e atualizações de segurança para proteger os seus arquivos.
- **Central de segurança do Azure:** É um serviço de monitoramento que oferece proteção contra ameaças nos data centers do Azure. Esse serviço detecta e bloqueia malwares, analisa e identifica possíveis ataques ao seu ambiente de nuvem, fornece recomendações de segurança e controla o acesso em tempo real. 
- **Azure Sentinel:** É uma solução de gerenciamento de informações e de respostas automatizada de segurança que fornece uma análise de segurança e inteligência contra ameaças em uma empresa. Ele faz uma análise do ambiente de nuvem e aprende com isso por meio de inteligência artificial.
- **Azure Key Vault:** Esse serviço guarda credenciais, armazena segredos do aplicativo em um local de nuvem centralizado para controlar com segurança as permissões e o registro em log de acesso.
- **Host dedicado do Azure:** Fornece servidores físicos que hospedam uma ou mais máquinas virtuais dedicadas à carga de trabalho de uma única organização. Ou seja, uma empresa compra um servidor físico do Azure e utiliza esse servidor sozinha na nuvem.
- Na Microsoft existe um recurso de **segurança compartilhada**, ele divide, de acordo com cada serviço, o que a Microsoft fica responsável e o que não fica.
- **Firewall do Azure:** É um serviço com estado e gerenciamento que concede/nega acesso ao servidor com base no endereço IP de origem, para proteger seus recursos de rede. O Azure fornece proteção de entrada para protocolos HTTP/s e não HTTP como RDP, SSH e FTP.
- **Proteção contra DDoS do Azure:** Os ataques DDoS são aqueles que sobrecarregam e esgotam os recursos da rede. Esse ataque é feito por meio do envio de diversas requisições para determinado site e, assim que ele cai, hackers clonam e podem roubar os dados dos clientes.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194451977-0c6a3ed7-e695-4ada-af8e-04a49e4888e0.png" width="600px" />
</div>

## Módulo 5: Identidade, governança, privacidade e conformidade

**Azure Policy:**

O Azure policy é utilizado para gerenciar e atribuir políticas e regras sobre os recursos como determinar que um recurso de VM só seja implementado com uma capacidade de X Gb no seu ambiente monitorado.

**RBAC (Controle de acesso baseado em função do Azure):**

O RBAC é um sistema de autorização que permite definir o nível de acesso a recursos, ambientes e as áreas de acesso. Essas permissões que os usuários tem podem ser de diversos níveis, entretanto, perante fins educacionais vale ressaltar os seguintes níveis de acesso: 
- Proprietário: Pode ler, alterar e dar permissões;
- Contribuinte: Pode ler e alterar;
- Leitor: Pode ler.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194441851-96961369-328f-4301-8baf-92eb2bd4bc28.png" width="600px" />
</div>

**Bloqueio de recursos:**

O bloqueio de recursos protege os recursos do Azure de exclusão ou alguma modificação acidental. Nele é possível gerenciar os níveis de assinatura, grupos de recursos ou recursos individuais no portal do Azure.

**Marcas (TAG's):** As tags consistem em um par nome-valor que auxiliam a identificar recursos. 
Esses rótulos contribuem no rateio correto de uso dos recursos.
Como utiliza o sistema chave-valor as tags ficam parecidas com:

<div align="center">
 
Centro de custo - TI
 
Projeto - TCB - 2022 - V2
 
Departamento - Recursos Humanos
 
Ambiente - Homologação
 
</div>

**Diferença entre autenticação e autorização:**

Embora pareçam semelhantes, autenticação e autorização não são a mesma coisa. 
A autenticação garante que a combinação entre o nome do usuário e a senha esteja correta (Ela permite que certificados sejam utilizados para identificar pessoas e serviços, uma vez que eles possuem uma chave anexada que identifica a pessoa ou serviço). Já a autorização garante que uma conta tenha permissões suficientes para acessar determinado recurso, ela determina o nível de acesso concedido a uma pessoa ou serviço (A autorização não usa senhas para identificar uma pessoa, somente a autenticação).


**Autenticação multifator do Azure:**

Esse recurso faz a autenticação duas vezes do acesso. Multifator pode ser exemplificado como o número de confirmação do Google quando fazemos um acesso em uma máquina diferente, logo após isso é enviado algum número para confirmação em seu celular a fim de aumentar a segurança nas senhas e cadastros.

**Azure Active Directory:**

É o serviço de gerenciamento de acesso e identidade na nuvem da plataforma. É nesse serviço que a autenticação e cadastro de usuários ocorre.
- **Acesso condicional:** O acesso condicional é utilizado pelo Azure Active Directory para reunir sinais, tomar decisões e impor políticas organizacionais para concluir uma ação. Por exemplo: um gerente de folha de pagamento deseja acessar o aplicativo de folha de pagamento e deve fazer uma autenticação multifator para acessá-lo.

<div align="center">
<img src="https://learn.microsoft.com/pt-br/azure/active-directory/conditional-access/media/overview/conditional-access-signal-decision-enforcement.png" width="720px" />
</div>

**Azure Policy:** 

Azure Policy é um recurso que ajuda a impor padrões organizacionais por meio do portal do Azure. Esses padrões podem ser bloquear a criação de uma VM em determinada região pois a empresa não presta mais serviços para essa área.

**Azure Blueprints:** 

O Azure Blueprints possibilita que equipes de desenvolvimento criem e implantem novos ambientes com facilidade. Ele permite que um ambiente que já existe (Com RBAC para os usuários, políticas, templates de recursos e grupos de recursos) seja copiado e replicado ou copiado em outra conta do Azure. 

**Recomendação: Cloud Adoption Framework:**

Cloud Adoption Framework é um site da própria plataforma do Azure que mostra boas práticas para quem está iniciando no serviço de nuvem. (Url: https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/).

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194444738-6320560d-2e7a-4dde-a4c0-fb3acbaee776.png" width="720px" />
</div>

**Segurança, Privacidade e Conformidade:**

- Segurança: Microsoft protege contra as ameaças.
- Privacidade: Garante a privacidade das organizações por meio de acordos contratuais e fornecendo controle e transparência ao usuário.
- Conformidade: Respeito as legislações.

**Integridade de serviço:** 

## **Módulo 6: Preço e ciclo de vida do Azure:**

**Fatores que afetam os custos:**
1) **Tipo de recurso:** Os custos são específicos do recurso, uma VM tem um custo, um servidor tem outra, um Hub cobra pelas mensagens enviadas, etc;
2) **Serviços:** Existem diversos níveis de clientes, cada um deles é taxado de uma maneira diferente;
3) **Localização:** O local que você instalará seu serviço tem seu próprio preço;
4) **Largura de banda:**  Alguns recursos do Azure permitem a transferência de dados de forma gratuita, entretanto, quando for cobrado, será em base na zona;
5) **Instâncias reservadas:** Com as reservadas do Azure você consegue descontos com o Azure por pagar pelo tempo de 3 anos sem ter utilizado ainda;
6) **Benefício de uso híbrido do Azure:** No Azure você pode importar sua licença de uma máquina para a nuvem.

**Ferramentas para ajudar no seu orçamento:**

**- Calculadora de preços:** É uma ferramenta que ajuda a estimar o preço a ser pago selecionando os recursos do Azure que pretende usar, com suas configurações.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194456410-2c16490a-8a5a-4b8a-81d0-7e371b31e39f.png" width="620px" />
</div>

**- Calculadora de TCO:** É uma ferramenta que permite estimar a economia de custos com o uso do Azure. Esse relatório gerado compara o preço das infraestruturas normais para a nuvem.

<div align="center">
<img src="https://user-images.githubusercontent.com/110680526/194456544-85c83c90-b5a7-4a88-80a0-af8c482ea8b3.png" width="620px" />
</div>

