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
