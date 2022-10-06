# Estudos certificação AZ-900
![image](https://user-images.githubusercontent.com/110680526/194125011-655bc899-f84e-48d3-bb00-a329157ba7b2.png)

## Módulo 1: Conceitos de nuvem

### **O que é a nuvem?** 
Computação em nuvem é a entrega de serviços de computação por meio da internet. É uma forma de alugar capacidade computacional e armazenamento do datacenter de terceiros. O provedor de nuvem é responsável por manter a infraestrutura disponível para você.
- Amazon foi a pioneira na computação em nuvem com o serviço da AWS.

![image](https://user-images.githubusercontent.com/110680526/194125448-b11da58e-c1b5-4243-8999-cef507d9ba74.png)

### **Nuvem pública, híbrida e privada:**
Existe uma diferença entre os serviços disponíveis na nuvem, esses serviços são divididos em: Serviços de nuvem pública, híbrida e privada.
- **Nuvem pública:** Qualquer pessoa pode contratar esse serviço, por isso é pública. Nesse tipo de serviço os servidores são totalmente alugados pelos usuários, ou seja, a infraestrutura fica totalmente com o provedor do serviço.
- **Nuvem privada:** As organizações criam um embiente em nuvem em seu datacenter, não tendo acesso de usuários de fora da organização. Nesse tipo de serviço os servidores são comprados e pertencem a organização, desde sua implantação até manutenção. Uma característica da nuvem privada é a necessidade de um investimento inicial para implantação do hardware.
- **Nuvem híbrida:** Esse serviço possui tanto a nuvem pública quanto a nuvem privada. Esse tipo de serviço é utilizado quando a organização possui seus próprios equipamentos mas o armazenamento é excedido; nesse caso a nuvem híbrida vira uma opção muito viável, uma vez que gastar com mais equipamentos é desnecessário e migrar completamente deixando seus atuais equipamentos sem utilidade também é um gasto desnecessário. Dessa forma, une-se a infraestrutura já existente e os serviços da nuvem.

### **Benefícios da nuvem:**
- **Escalabilidade:** Capacidade de aumentar ou diminuir os recursos automaticamente;
- **Alcance global:** Pode-se acessar data centers no mundo inteiro, podendo alocar seus servidores em diversas regiões do planeta;

![image](https://user-images.githubusercontent.com/110680526/194128696-ed528977-06c7-4f78-855e-3e16ee0e44b6.png)

- **Agilidade:**
- **Recuperação de desastre:** Caso pegue fogo em algum lugar ou ocorra algum desastre, você tem uma recuperação de desastre em algum outro ponto (caso configurado outro ponto do seu serviço), ou seja, existem Backup's em outros data center;
- **Tolerância a falhas:** Diz respeito a quanto o ambiente pode ser acarretado por falhas e sobrevive mesmo com elas, o quanto ele é tolerante a falhas;
- **Elasticidade:** É um dos maiores e mais conhecidos benefícios da nuvem. Elasticidade é quanto o recurso pode se moldar quanto a demanda. Um exemplo bem claro disso é na famosa black friday que a demanda/acessos sobem muito; com a nuvem os recursos acompanham a demanda;
- **Considerações sobre custo preditivo:** Calcula quanto precisará do recurso e o quanto gastará com isso;
- **Segurança:** É um dos maiores benefícios da nuvem, existem diversos recursos que protegem seus dados na nuvem, além da proteção dos próprios data centers dos provedores.

### **Modelo de despesa: Comparação entre CapEx e OpEx:** 
Na nuvem existem dois modelos de despesa: CapEx (Capital Expenditure) e OpEx (Operational Expenditure).
- **CapEx:** Nesse modelo de despesa está incluso o investimento inicial em máquinas, equipamentos e outros bens nas instalações na empresa. É o modelo presente na nuvem privada.
- **OpEx:** No modelo OpEx os gastos são feitos conforme o necessário, ou seja, é feito pagamento conforme o uso do serviço. É o modelo presente na nuvem pública.

![image](https://user-images.githubusercontent.com/110680526/194131746-87742188-df1a-49d7-af7e-bbe23d5c5c28.png)

### **Modelo baseado em consumo:**
Na nuvem os usuários pagam pelos recursos que utilizam. Os modelos de núvem pública são basicamente divididos em três: IaaS, PaaS e SaaS.
- **IaaS:** Nesse modelo o usuário fica responsável pelas atualizações e instalações, o usuário gerencia o hardware para o seu aplicativo. Lembrando que, embora as atualizações e instalações fiquem como responsabilidade do usuário, toda a parte física de instalação e manutenção é realizada pelo provedor da nuvem.
- **PaaS:** No PaaS o nível de gerenciamento da máquina é menor pela parte do usuario. Nesse modelo o usuário somente gerencia as aplicações presentes no servidor.
- **SaaS:** Nesse modelo temos os softwares prontos que entregam um serviço, o usuário para com base no uso; como exemplos de SaaS temos Netflix, Spotify, HBO, etc. São softwares que você acessa pela Internet e já estão prontos para o uso.

## Módulo 2: Principais serviços do Azure ##
### **O que é o Azure?**
"Azure é um conjunto de serviços de nuvem em constante expansão, que ajuda a sua organização a superar os desafios empresariais e atuais e se preparar para os desafios futuros. No portal do Azure é possível acessar e utilizar as suas ferramentas; é possível compilar, gerenciar e monitorar tudo."

![image](https://user-images.githubusercontent.com/110680526/194134675-2eb508d3-5f88-49aa-8cf2-e5d0bf6d5795.png)

### **Assinatura do Azure:**
Para começar a utilizar o serviço do Azure é necessário possuir uma assinatura. Uma assinatura é uma unidade lógica de serviços do Azure vinculada a uma conta.
Uma conta pode ter uma ou mais assinaturas; essas assinaturas podem possuir diferentes níveis de gerenciamento de acesso. Geralmente são feitas assinaturas diferentes para ambientes diferentes como departamentos, equipes, etc.

![image](https://user-images.githubusercontent.com/110680526/194135305-7191ba42-4158-4ce6-8472-af4332eb18f9.png)

### **Regiões:**
A Microsoft está espalhada em vários lugares do mundo. Para cada região, existe um par de regiões que é feito para replicar os dados (esses pares ficam no mínimo 300 milhas de distância). Região é uma área do planeta que contém pelo menos um data center (normalmente são vários) e conectados em rede com uma baixa latência. O Azure tem mais regiões globais do que qualquer outro provedor de nuvem. 
- **Regiões especiais do Azure:** Us DoD Central, US Gov Virginia, US Gov lowa e outras: são regiões físicas e lógicas isoladas de rede pertencentes ao Azure para agências e parceiros do governo dos Estados Unidos utilizarem. Esses data centers são acessados e operadores por pessoas selecionadas dos Estados Unidos.
- Conexão com a China: O governo chinês é um governo fechado em relação a empresas de fora que vão monitorar dados de lá. Como alternativa a isso, o intermédio entre a China e a Azure é realizado pela empresa 21Vianet que tem parceria com a Microsoft. 

### **Zonas de disponibilidade**
São data centers fisicamente separados na mesma região. Esses data centers, embora estejam na mesma região, possuem equipamentos de alimentação elétrica, refrigeração e rede exclusivos de cada um. 
No Azure existem dois serviços que oferecem suporte a zonas de disponibilidade: Serviços zonais e serviços com redundância de zona.
- **Serviços zonais:** Nesse serviço você escolhe somente uma zona específica para colocar seu recurso.
- **Serviços com redundância de zona:** Nesse serviço a plataforma replica automaticamente os recursos entre as zonas.

![image](https://user-images.githubusercontent.com/110680526/194145147-ee909f86-6956-46b0-8136-cac7752611df.png)

### **Recursos do Azure:**
O Azure oferece diversos recursos dentro da sua plataforma, entre eles: Criação de máquinas virtuais, banco de dados, armazenamento, entre outros.
### **Grupo de recursos:**
O grupo de recursos reúne os recursos e agrupam aqueles que estão conectados. Por meio do grupo de recursos é possível definir configurações em comum entre os recursos presentes nele.
### **Azure Resource Manager:**
Gerencia como os seus recursos serão alocados e criados. As solicitações para criar ou atualizar um recurso são feitas por meio desse recurso.

![image](https://user-images.githubusercontent.com/110680526/194149632-bbbf0354-63b1-4f5e-ac9f-e548a7a1660b.png)

### **Grupos de gerenciamento:** 
O grupo de gerenciamento permite que você gerencie assinaturas, permitindo inclusive atribuir permissõoes para os recursos.

Na imagem abaixo as chaves são as assinaturas e os demais símbolos os grupos. É possível notar que as assinaturas e grupos são divididos pelos departamentos da empresa que provavelmente possuem permissões diferentes.

![image](https://user-images.githubusercontent.com/110680526/194150428-35df02bc-7ef6-4c47-b042-5d160197beec.png)

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

![image](https://user-images.githubusercontent.com/110680526/194376940-8cc5ab80-50ae-408b-b9ca-9ffc2853eb5e.png)

**2. Rede:**

O gerenciamento de redes virtual do Azure um serviço que permite agrupar, configurar e implantar redes virtuais em assinaturas da plataforma. É possível definir grupos de rede para identificar e configurar suas redes virtuais.
A plataforma garante: serviço altamente escalonável e disponível, baixa latência e alta largura de banca.

**3. Armazenamento:**

O serviço de armazenamento do Azure é uma solução de nuvem para armazenar dados modernos. Os dados salvos podem ser acessar por HTTP.
O armazenamento de dados possui as camadas: Hot, Cool e Archive. 
- Hot: Armazenamento que os dados são acessados com frequência.
- Cool: Dados acessados com pouca frequência por pelo menos 30 dias.



