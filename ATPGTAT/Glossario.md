### Glossário de Termos de Testes Ágeis

Aqui estão as definições dos principais termos usados ao longo deste livro:

- **Teste de Aceitação**: Testes que verificam se uma história atende ao valor comercial esperado. Podem envolver requisitos funcionais ou não funcionais, como desempenho. Esses testes orientam o desenvolvimento e são realizados em um nível mais alto que os testes de unidade.

- **Interface de Programação de Aplicativos (API)**: Conjunto de funções, procedimentos ou classes que permitem que outros programas invoquem funcionalidades específicas de um software.

- **Construir (Build)**: Processo de converter código-fonte em um artefato implantável. Também se refere ao artefato final que pode ser instalado e executado.

- **Componente**: Parte maior do sistema que pode ser implantada separadamente, como bibliotecas vinculadas dinâmicas (DLLs) em Windows ou arquivos JAR em Java.

- **Teste de Componente**: Verifica o comportamento de um componente e ajuda no design do componente ao testar interações entre objetos.

- **Condições de Satisfação**: Critérios que definem o comportamento desejado do código entregue para uma história. Evoluem durante conversas com o cliente e ajudam a garantir que todas as tarefas estejam bem especificadas.

- **Testes Orientados por Contexto**: Abordagem que adapta práticas de teste às necessidades específicas de um projeto. Baseia-se no princípio de que o valor de qualquer prática depende de seu contexto.

- **Equipe do Cliente**: Grupo que identifica e prioriza os recursos necessários para o negócio. Inclui partes interessadas, especialistas em negócios e usuários finais. Trabalha com a equipe de desenvolvimento para definir e testar histórias.

- **Teste do Cliente**: Teste que verifica o comportamento de uma funcionalidade visível para o cliente, diretamente relacionada a uma história ou recurso.

- **Equipe de Desenvolvimento**: Equipe técnica que cria o software solicitado, incluindo desenvolvedores, testadores, especialistas em banco de dados, entre outros. Trabalha em conjunto para entregar valor ao negócio.

- **Epic**: Funcionalidade ou recurso descrito pelo cliente e listado no backlog do produto. Dividido em histórias menores que são dimensionadas e estimadas.

- **Exploratory Testing (Teste Exploratória)**: Teste interativo que combina design e execução de testes, focando em aprender sobre o aplicativo e encontrar problemas não antecipados.

- **Fake Object**: Substitui a funcionalidade de um componente dependente com uma implementação simplificada, facilitando os testes.

- **Feature**: Funcionalidade descrita pelo cliente, listada no backlog do produto, e dividida em histórias relacionadas para estimativa e desenvolvimento.

- **Functional Test (Teste Funcional)**: Verifica o comportamento esperado do sistema dado um conjunto de entradas e/ou ações.

- **Greenfield**: Projetos de desenvolvimento de aplicativos iniciados do zero, sem código existente, permitindo total liberdade no desenvolvimento.

- **Integrated Development Environment (IDE)**: Conjunto de ferramentas que suporta programação e testes, incluindo editor, compilador, depurador e ferramentas de automação de build.

- **Iteration (Iteração)**: Ciclo de desenvolvimento curto, geralmente de uma a quatro semanas, no final do qual o código pronto para produção pode ser entregue.

- **Java Messaging Service (JMS)**: API de mensagens que permite que componentes de aplicativos baseados na plataforma Java criem, enviem, recebam e leiam mensagens.

- **Legacy System (Sistema Legado)**: Sistema com poucos ou nenhum teste automatizado de regressão, tornando as mudanças e refatorações arriscadas devido à falta de testes.

- **Multipurpose Internet Mail Extensions (MIME)**: Extensão do formato de e-mail para suportar mensagens não textuais e corpos de mensagens multipartes.

- **Mock Object (Objeto Mock)**: Simula as respostas de um objeto existente para ajudar a testar interações entre objetos substituindo um componente real.

- **Product Backlog (Backlog do Produto)**: Lista priorizada de todas as funcionalidades desejadas no produto, que cresce à medida que novas necessidades são identificadas.

- **Product Owner (Dono do Produto)**: Responsável por priorizar o backlog do produto e garantir que o desenvolvimento atenda às necessidades do negócio.

- **Quality Assurance (QA) Team (Equipe de Garantia de Qualidade)**: Equipe que realiza testes para garantir a conformidade com padrões de qualidade, integrada às atividades de desenvolvimento em métodos ágeis.

- **Production Code (Código de Produção)**: Código utilizado em ambiente de produção, em contraste com o código de teste.

- **Refactoring (Refatoração)**: Alteração do código para melhorar sua manutenção e legibilidade sem modificar sua funcionalidade.

- **Regression Test (Teste de Regressão)**: Verifica se a funcionalidade existente do sistema não foi alterada por novas mudanças. Geralmente automatizado para garantir feedback contínuo.

- **Release Candidate (Candidato a Release)**: Versão do produto que pode ser liberada para produção, podendo passar por testes adicionais ou receber documentação extra.

- **Return On Investment (ROI) (Retorno Sobre o Investimento)**: Medida da eficiência de um investimento, calculada como a diferença entre o ganho e o custo do investimento, dividida pelo custo.

- **SOAP (Simple Object Access Protocol)**: Protocolo para troca de mensagens baseadas em XML sobre redes, geralmente usando HTTP/HTTPS, formando a base para comunicação de serviços web.

- **História**: Breve descrição da funcionalidade do ponto de vista do usuário, importante para o usuário ou para a equipe do cliente. Geralmente escrita em fichas e pode ser usada em combinação com conversas e testes para garantir que a funcionalidade foi implementada corretamente.

- **Teste de História**: Define o comportamento esperado para o código entregue pela história. Pode ser voltado para negócios (requisitos funcionais) ou tecnologia (como segurança ou desempenho). É similar ao teste de aceitação, embora o teste de aceitação possa abranger um nível mais alto de verificação.

- **Quadro de Histórias**: Também conhecido como storyboard ou quadro de tarefas, é usado para rastrear o progresso do trabalho durante uma iteração. Cartões de tarefas são usados para representar histórias e seu progresso é visualizado através de colunas ou adesivos em um quadro físico ou virtual.

- **Tarefa**: Parte do trabalho necessário para completar uma história. Normalmente representa um dia ou menos de trabalho e pode incluir ações como implementar um pedaço de uma história, construir infraestrutura ou realizar testes.

- **Dívida Técnica**: Metáfora introduzida por Ward Cunningham para descrever o custo associado a não seguir boas práticas de desenvolvimento, como TDD e refatoração. Semelhante à dívida financeira, a dívida técnica pode aumentar o custo e o esforço de manutenção no futuro.

- **Teste Duplo**: Termo para qualquer objeto ou componente substituto usado em testes, como objetos fictícios, stubs de teste e objetos falsos. Esses "duplicados de teste" ajudam a simular o comportamento de componentes reais durante os testes.

- **Desenvolvimento Orientado a Testes (TDD)**: Abordagem onde o programador escreve um pequeno teste de unidade antes de implementar o código que fará o teste passar. Cada pedaço de código é desenvolvido para passar um teste específico.

- **Desenvolvimento de Teste Primeiro**: Abordagem onde testes são escritos antes do código de produção correspondente, mas o código não é necessariamente feito para passar um teste de cada vez. Inclui testes de cliente, história e unidade.

- **Esboço de Teste (Stub de Teste)**: Objeto que substitui um componente real necessário para o sistema em teste, alimentando entradas específicas no sistema para verificar a lógica sem depender de outros componentes.

- **Equipe de Teste**: Grupo responsável por definir e verificar o comportamento desejado do sistema em teste. Fornece informações sobre a qualidade do sistema, riscos e estratégias de mitigação. Em desenvolvimento ágil, testadores estão integrados à equipe de desenvolvimento.

- **Provador**: Testador que fornece informações sobre o software, ajuda a definir requisitos e critérios de qualidade, e transforma esses requisitos em testes. Testadores realizam atividades como automação de testes e testes exploratórios e colaboram estreitamente com a equipe de desenvolvimento.

- **Tema**: Sinônimo de épico ou recurso, descreve uma funcionalidade no backlog do produto, que é dividida em histórias para estimativa e desenvolvimento.

- **Teste de Unidade**: Verifica o comportamento de uma pequena parte do sistema, como um objeto ou método, normalmente resultado de decisões de design.

- **Velocidade**: Medida da quantidade de valor entregue por uma equipe em cada iteração, normalmente medida em pontos de história, dias ou horas ideais. Ajuda no planejamento de recursos e versões futuras, baseando-se na velocidade das iterações anteriores.

- **WSDL (Web Service Description Language)**: Formato XML usado para descrever serviços de rede como um conjunto de endpoints que operam em mensagens contendo informações orientadas a documentos ou procedimentos.