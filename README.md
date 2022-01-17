<h3>Bootcamp <a href="https://github.com/eduzz/mentoria-dio">Eduzz</a> - DIO | <a href="https://github.com/lucasrmagalhaes/homework-issues/issues?q=is%3Aissue+label%3AEduzz+is%3Aclosed">Issues</a></h3>

<hr>

<h4>Mentoria 01: Aula Inaugural: Como ser o próximo contratado pela Eduzz</h4>

Apresentação do bootcamp.

<hr>

<h4>Mentoria 02: Carreira Eduzz: cultura e governança</h4>

Como funciona o dia a dia na Eduzz.

<hr>

<h4>Mentoria 03 - Projeto Eduzz: Explicando o projeto Eduzz e prototipando a aplicação</h4>

* [Dribbble](https://dribbble.com/) <br>
* [Behance](https://www.behance.net/) <br>
* [Pinterest](https://www.pinterest.pt/) <br>
* [Figma](https://www.figma.com/) <br>
* [Houston](https://eduzz.github.io/houston/)

Exemplo de Projeto no Figma.

<hr>

<h4>Mentoria 04 - Projeto Eduzz: Componentizando a aplicação e criando interfaces responsivas</h4>

Principios importantes

<ol>
    <li>Estrutura de pastas</li>
    <li>Separação de responsabilidade</li>
    <li>Entender o framework e a linguagem</li>
</ol>

Frameworks recomendados

<ol>
    <li>Redux Toolkit - Gerenciamento do Estado</li>
    <li>MUI - UI components</li>
    <li>Formik - Validação do formulário</li>
    <li>Emotion/Styled Component - Estilização</li>
</ol>

<hr>

<h4>Mentoria 05 - Projeto Eduzz: Criando a base de dados para suportar a aplicação</h4>

**O que é Banco de Dados?** Coleção organizada de informações.

##### Tipos

<ul>
    <li>Bancos de dados relacionais</li>
    <li>Bancos de dados NoSQL</li>
    <li>Data warehouses</li>
    <li>Bancos de dados gráficos</li>
</ul>

##### Banco relacional

<ul>
    <li>MySQL, MariaDB, Postgree, SQLServer, SQLite3</li>
    <li>Armazenam dados em tabelas e linhas</li>
    <li>Usam SQL</li>
    <li>ACID (Atomicidade, Consistência, Isolamento, Durabilidade)</li>
    <li>Integralidade do dado</li>
    <li>Dados bem definidos</li>
</ul>

##### Não relacional

<ul>
    <li>Firebase, MongoDB, ElasticSearch, Redis, Cassandra, DynamoDB...</li>
    <li>Flexibilidade</li>
    <li>Documentos (semelhantes a JSON), chave-valor</li>
    <li>Armazenando registros na mesma coleção que possuem diferentes campos ou atributos</li>
    <li>Escala horizontalmente</li>
    <li>Não tem uma forma padrão de recuperação de dados</li>
</ul>

##### Chave primária

<ul>
    <li>Identificador único de um registro na tabela</li>
    <li>Não pode ser NULL</li>
    <li>Não podem ser simples ou compostas</li>
</ul>

##### Chave estrangeira

<ul>
    <li>Chave primária de outra tabela, ou dela mesma</li>
    <li>Pode ser NULL</p>
</ul>

##### Clientes de BD

<ul>
    <li>MySQL Workbench</li>
    <li>DBeaver</li>
    <li>HeidiSQL</p>
</ul>

##### Migration

<ul>
    <li>Versiona o schema da aplicação</li>
    <li>Controle de alterações do banco</li>
    <li>Pode ser adicionada ao deploy automático</p>
</ul>

##### Seeds

<ul>
    <li>Pode ser usada para DADOS DE TESTE ou valores PRÉ DEFINIDO</li>
    <li>Pode ser adicionada ao deploy automático</li>
</ul>

<hr>

<h4>Mentoria 06 - Projeto Eduzz: Desenvolvendo o back-end da aplicação e plugando o front-end</h4>

<ul>
    <li>Sobre APIs;</li>
    <li>Primeiro endpoint (hands-on);</li>
    <li>Funcionamento do NodeJS;</li>
    <li>Relembrando o que é Typescript;</li>
    <li>Detalhar a arquitetura do projeto; e</li>
    <li>API funcionando!</li>
</ul>

**APIs (Application Programming Interface - Interface de Programação de Aplicação)** <br>
[V8](https://v8.dev/)

Dentro do diretório ```api```
```
docker-compose up
```

```
yarn install
```

```
yarn start
```

[Public APIs](https://github.com/public-apis/public-apis)

<hr>

<h4>Mentoria 07 - Projeto Eduzz: Entendendo e utilizando serviços de mensageria</h4>

- Conceitos sobre processamento assíncrono;
- Message Brokers;
- Funcionamento do RabbitMQ;
- Aplicação prática;
- Nova arquitetura do projeto; e
- Esqueci minha senha funcionando!

O que é assíncrono? <br>
Um processo assíncrono é um processo ou função que executa uma tarefa "em segundo plano", sem que o usuário precise esperar que a tarefa termine. <br>

**Message Brokers** <br>
É quem define para qual fila vai a mensagem <br>
Filas - Message Brokers - Eventos <br>
RabbitMQ, Redis e Amazon SQS <br>

[RabbitMQ Simulator](http://tryrabbitmq.com/)

<hr>

<h4>Mentoria 08 - Projeto Eduzz: Vislumbrando possibilidades de integração da aplicação com a nuvem</h4>

##### O que é nuvem?

O termo nuvem é o nome dado à tecnologia que permite a distribuição de serviços de computação e o acesso online a eles sem a necessidade de instalar programas. Justamente por não necessitar da instalação de programas, ou do armanezamento de dados, o conceito originado do inglês cloud computing faz alusão à "nuvem". <br>

**Alguns serviços na nuvem:** Spotify, Youtube, Facebook, Instagram, Dropbox e Google Docs. <br>

##### Provedores de Cloud vs Meu Servidor 

No meu servidor, tudo eu tenho que fazer, na nuvem eu tenho a possibilidade de tudo ser gerenciado pelo provedor escolhido. <br>
Limitação de recurso: estou limitado ao poder computacional da máquina contratada (contratações de novas máquinas pode levar tempo). <br>

##### Benefícios dos Serviços de Cloud

**Escalabilidade:** Capacidade de um Sistema em adicionar ou remover recursos de maneira autônama sem interrupções. <br>
**Gerenciamento:** Os serviços são gerenciados pelo provedor para que você ponha esforço no seu produto. <br>
**Custo:** Normalmente os serviços contratados são cobrados por tempo de execução, armazenamento, e cosutumam ser baratos. <br>
**Confiabilidade:** Facilita e reduz os custos de backup de dados, recuperação de desastre e continuidade dos negócios, já que os dados podem ser espelhados em diversos sites redundantes na rede do provedor em nuvem. <br>
**Segurança:** Os provedores em nuvem oferecem um amplo conjunto de políticas, tecnlogias e controles que fortalecem a segurança, ajudando a proteger os dados, os aplicativos e a infraestrutura contra possíveis ameaças. <br>

Diversos serviços para surpotarem seu produto:

<ol>
    <li>Banco de Dados</li>
    <li>Caching</li>
    <li>Armazenamento</li>
    <li>Backup</li>
    <li>Rede</li>
    <li>Monitoramento</li>
    <li>DNS</li>
    <li>CDN</li>
    <li>Autenticação/Autorização</li>
    <li>Inteligência Artificial</li>
    <li>Blockchain</li>
    <li>Contâineres</li>
    <li>Deploy</li>
    <li>Etc, etc, etc...</li>
</ol>

**Provedores de serviços de nuvem:** Amazon Web Services, Azure, Google Cloud Platform, Heroku, Vercel e Digital Ocean. <br>

**Serviços que vamos usar:**
- AWS RDS
- AWS ECR
- AWS ECS
- GitHub Actions

[RDS](https://aws.amazon.com/pt/rds/) <br>
É o serviço de banco de dados da AWS. É nele que criamos as nossas instâncias de banco de dados. É um serviço AWS e suporta uma gama de banco de dados relacionais. <br>

[ECR](https://aws.amazon.com/pt/ecr/) <br>
Basicamente é o serviço de armazenamento de imagens de contêineres da AWS. Você também pode usar outros serviços fora da nuvem da AWS, como o <a href="https://hub.docker.com">Docker Hub</a>. <br>

[ECS](https://aws.amazon.com/pt/ecs/) <br>
Faz a orquestração dos nossos contêineres baseado nas configurações que definimos para eles. Ele é o serviço responsável pela escalabilidade da nossa aplicação. <br>

[Calculator API](https://github.com/tgbaldo/dio-calculator-api)

<hr>

<h4>Mentoria 09 - Projeto Eduzz: Retire todas as dúvidas encontradas no desenvolvimento do projeto</h4>

Dicas/Conselhos e os bastidores de um DEV na Eduzz.