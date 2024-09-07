# Apêndice B

Aqui estão as respostas baseadas nas informações fornecidas:

### Capítulo 1: Uma Visão Geral

**1.1 Quais são as três partes de uma história de usuário?**  
**Resposta:** Cartão, Conversação e Confirmação.

**1.2 Quem faz parte da equipe do cliente?**  
**Resposta:** A equipe do cliente inclui aqueles que garantem que o software atenderá às necessidades de seus usuários pretendidos. Isso pode incluir testadores, um gerente de produto, usuários reais e designers de interação.

**1.3 Quais das seguintes não são boas histórias? Por que?**  
**Resposta:** Veja o quadro B.1 para detalhes específicos.

**1.4 Quais são as vantagens das conversas sobre requisitos sobre os documentos de requisitos?**  
**Resposta:** Documentos escritos implicam uma precisão que eles não podem apoiar. As histórias de usuários, com cartões como lembretes para manter conversas, evitam a falsa aparência de serem altamente precisas. Escrever as coisas não é garantia de que os clientes conseguirão o que desejam; na melhor das hipóteses, os clientes receberão o que foi escrito. Conversas frequentes, especialmente aquelas próximas e durante o desenvolvimento do recurso que está sendo discutido, levam a um entendimento maior e compartilhado entre os desenvolvedores e os clientes.

**1.5 Por que você gostaria de escrever testes no verso de um cartão de história?**  
**Resposta:** Escrever testes no verso de um cartão é uma ótima maneira de o cliente comunicar suas expectativas e suposições sobre uma história.

### Capítulo 2: Escrevendo histórias

**2.1 Para as histórias a seguir, indique se é uma boa história ou não. Se não, por quê?**  
**Resposta:** Veja o quadro B.2 para detalhes específicos.

**2.2 Divida este épico em histórias de componentes de tamanho apropriado: "Um usuário pode criar e alterar agentes automatizados de busca de emprego."**  
**Resposta:** Minimamente, esse épico deve ser dividido em duas histórias, uma para criar e outra para alterar os agentes. A divisão sugerida inclui:
- Um usuário pode criar um agente automatizado de busca de emprego.
- Um usuário pode editar os parâmetros de pesquisa de um agente de busca de emprego automatizado.
- Um usuário pode alterar os horários em que um agente de busca de emprego automatizado será executado.
- Um usuário pode alterar a forma como os resultados de um agente automatizado de busca de emprego serão relatados.

### Capítulo 3: Modelagem de função do usuário

**3.1 Dê uma olhada no site do eBay. Quais funções de usuário você pode identificar?**  
**Resposta:** Algumas funções incluem Vendedor Único, Pequeno Vendedor, Vendedor Frequente, Comprador Pouco Frequente, Comprador Frequente, Vendedor Corporativo, Fabricante, Processador de Pagamentos, Colecionador, Membro do Clube, Desenvolvedor de Software, Afiliado, Vendedor Sem Fio, Comprador Sem Fio.

**3.2 Consolide as funções que você criou na pergunta anterior e mostre como você apresentaria os cartões de função. Explique sua resposta.**  
**Resposta:** Consolidei os vendedores em uma função genérica de Vendedor e três vendedores especializados: Pequeno Vendedor, Vendedor Frequente e Vendedor Corporativo. Da mesma forma, consolidei os compradores em Comprador Infrequente, Comprador Frequente e Colecionador. Mantive também Processador de Pagamentos, Afiliado e um Usuário Wireless genérico.

**3.3 Escreva descrições de persona para a função de usuário mais importante.**  
**Resposta:** Brenda é uma compradora frequente. Durante uma semana típica, ela visita o site pelo menos uma vez por dia e faz uma média de uma ou duas compras por semana. Ela normalmente compra filmes e livros, mas também comprou itens de jardinagem e cozinha. Ela é corretora de imóveis e se sente muito confortável em nosso site, mas se sente um pouco desconfortável aprendendo a maioria dos novos softwares. Ela geralmente acessa o site de sua conexão dial-up em casa, mas ocasionalmente o acessa de sua conexão de escritório mais rápida.

### Capítulo 4: Reunindo Histórias

**4.1 Que problemas você esperaria se uma equipe reunisse requisitos apenas por meio do uso de questionários?**  
**Resposta:** Os questionários podem levar muito tempo para serem entregues, então o projeto levará mais tempo para ser concluído. Alguém precisará agregar e interpretar os resultados, o que significa que haverá algum grau de má interpretação. Como os questionários não fornecem uma verdadeira comunicação bidirecional, será extremamente difícil para uma equipe obter feedback sobre se está no caminho certo.

**4.2 Reformule as perguntas a seguir para que sejam livres de contexto e abertas. Você acha que o usuário deveria ter que digitar uma senha? O sistema deve salvar automaticamente o trabalho do usuário a cada 15 minutos? Um usuário pode ver as entradas do banco de dados salvas por outro usuário?**  
**Resposta:**
- Descreva como o sistema deve proteger dados confidenciais.
- O que um usuário faria se o sistema travasse enquanto o estivesse usando?
- Conte-me sobre a acessibilidade dos dados salvos por um usuário.

**4.3 Por que é melhor fazer perguntas abertas e sem contexto?**  
**Resposta:** Perguntas sem contexto não implicam uma resposta ("Quando você parou de bater em sua esposa?"), então o entrevistado não sente necessidade de dar a resposta "certa". As perguntas abertas permitem respostas detalhadas que vão além de um simples sim ou não. Perguntas abertas e sem contexto são melhores porque não influenciam a resposta e permitem uma gama mais ampla de respostas do que sim ou não.

### Capítulo 5: Trabalhando com proxies de usuário

**5.1 Quais problemas podem resultar do uso do gerenciador de usuários como proxy para os usuários?**  
**Resposta:** Mesmo que o gerente dos usuários seja um usuário atual do software, suas necessidades quase certamente diferem das necessidades dos usuários. Pior, se ela é uma ex-usuária, seu conhecimento do sistema está desatualizado.

**5.2 Quais problemas podem resultar do uso de um especialista em domínio como proxy para os usuários?**  
**Resposta:** Um problema é que o especialista em domínio pode não ser um usuário do sistema. Se for, seu uso do sistema pode diferir de usuários menos experientes. Um segundo problema é que você pode acabar com um sistema perfeito para especialistas, mas que não pode ser usado por aqueles com menos de conhecimento de domínio de nível especializado.

### Capítulo 6: Histórias de usuários de teste de aceitação

**6.1 Quem especifica os testes? Quem ajuda?**  
**Resposta:** O cliente especifica os testes. O cliente geralmente trabalhará com um programador ou testador para realmente criar os testes, mas minimamente o cliente precisa especificar os testes que serão usados para saber quando uma história foi desenvolvida corretamente.

**6.2 Por que especificar testes antes que as histórias sejam codificadas?**  
**Resposta:** Os testes são especificados antes do início da codificação porque são um método útil e eficaz para comunicar as suposições do cliente sobre a nova funcionalidade.

### Capítulo 7: Diretrizes para Boas Histórias

**7.1 Suponha que a história "Um candidato pode procurar vagas em aberto" seja muito grande para caber em uma iteração. Como você dividiria isso?**  
**Resposta:** Esta história provavelmente pode ser dividida com base nos parâmetros de pesquisa suportados, como localização, palavras-chave, cargo, salário e assim por diante. Além disso, pode haver diferentes maneiras de apresentar os resultados. Uma história inicial pode cobrir uma lista muito simples de cada trabalho correspondente. Essa história pode ser aumentada por uma história para aprimorar a exibição dos resultados, talvez com mais detalhes sobre cada trabalho, permitindo que o usuário selecione uma ordem de classificação ou quais campos são exibidos ou fornecendo um link para mais detalhes sobre o trabalho.

**7.2 Qual dessas histórias tem o tamanho adequado e pode ser considerada uma história fechada?**  
**Resposta:** Veja o quadro B.3 para detalhes específicos.

**7.3 Que mudanças simples poderiam melhorar a história "Os usuários podem postar seus currículos"?**  
**Resposta:** Conforme escrito, não está claro se um usuário pode postar vários currículos. Isso, sem dúvida, aparecerá durante as conversas sobre a história, mas é melhor escrever a história com mais clareza, como "Um candidato a emprego pode postar um ou mais currículos".

**7.4 Como você testaria a restrição "O software será fácil de usar"?**  
**Resposta:** Para testar isso, você deve primeiro definir o que significa "fácil de usar". Isso significa que um usuário habilidoso pode concluir tarefas comuns com um número mínimo de pressionamentos de tecla? Ou isso significa que um novo usuário pode atingir rapidamente um determinado nível de proficiência com o software? Mais comumente, significará o último. Em caso afirmativo, defina um ou mais testes, como:
- Um novo usuário pode procurar um emprego, registrar-se no sistema e postar seu currículo dentro de 30 minutos após ver o sistema pela primeira vez.
Testes como esses não podem ser realizados como parte das compilações noturnas de um projeto, mas podem ser verificados por testes de usabilidade ocasionais durante os quais novos usuários veem o software e são observados.

### Capítulo 8: Estimando histórias de usuários

**8.1 Durante uma reunião de estimativa, três programadores estão estimando uma história. Individualmente, eles estimam a história em dois, quatro

 e oito pontos. A média seria quatro, mas a equipe decide usar oito. Qual é a principal razão para adotar a estimativa mais alta?**  
**Resposta:** O principal motivo é que a estimativa mais alta reflete a visão mais pessimista de um membro da equipe. Se a equipe decidir que a estimativa mais pessimista é a mais precisa, a equipe deve estar preparada para abordagens mais conservadoras ao projeto. É preferível usar a estimativa mais alta para fornecer mais tempo para o desenvolvimento do software.

**8.2 Quais os problemas que podem surgir ao dividir a história de usuário "um candidato pode se inscrever para um emprego" em histórias menores?**  
**Resposta:** Alguns problemas potenciais incluem:
- **Semelhante:** A subdivisão pode se tornar muito pequena e levar a uma sobrecarga de gerenciamento ou dificuldades na integração das partes.
- **Funcionalidade:** Pode haver a necessidade de garantir que todas as histórias menores sejam integradas de forma a fornecer uma funcionalidade coerente e completa.
- **Desafios:** Pode haver desafios adicionais ao tentar identificar todos os componentes necessários para garantir que cada parte funcione como um todo.

### Capítulo 9: Conclusão

**9.1 Qual a vantagem de usar histórias de usuários em vez de requisitos escritos?**  
**Resposta:** Histórias de usuários são mais flexíveis e adaptáveis às mudanças. Elas facilitam uma compreensão mais colaborativa e dinâmica entre a equipe de desenvolvimento e o cliente, além de incentivar um diálogo contínuo para esclarecer e refinar os requisitos.

**9.2 Como as histórias de usuários ajudam a melhorar o processo de desenvolvimento?**  
**Resposta:** Elas promovem a comunicação contínua entre desenvolvedores e clientes, ajudam a garantir que o produto final atenda às necessidades reais dos usuários e permitem uma adaptação mais ágil às mudanças de requisitos ou prioridades.

Claro, aqui estão as respostas baseadas nos capítulos fornecidos:

### Capítulo 10: Planejando uma Iteração

**10.1 Desagregar esta história em suas tarefas constituintes: "Um usuário pode visualizar informações detalhadas sobre um hotel."**  
**Resposta:**
- Projete a aparência das páginas da web para exibir informações detalhadas sobre o hotel.
- Codifique o HTML para exibir fotos de hotéis e quartos.
- Codifique o HTML para exibir um mapa mostrando a localização do hotel.
- Codifique o HTML para exibir uma lista de comodidades e serviços do hotel.
- Determine como gerar e integrar mapas.
- Escreva SQL para recuperar informações do banco de dados.
- Teste a funcionalidade e a apresentação das informações detalhadas.

### Capítulo 11: Medindo e Monitorando a Velocidade

**11.1 Uma história estimada em um ponto da história na verdade levou dois dias para ser concluída. Quanto isso contribui para a velocidade quando calculado no final da iteração?**  
**Resposta:** Contribui com um ponto. A velocidade é calculada com base no número de pontos completados, não no tempo gasto.

**11.2 O que você pode aprender com um gráfico de burndown diário que não pode ser visto em um gráfico de burndown de iteração?**  
**Resposta:** O gráfico de burndown diário mostra o progresso detalhado da equipe em cada dia da iteração, permitindo a avaliação se o trabalho planejado será concluído no prazo. Também ajuda a identificar problemas antecipadamente e ajustar o trabalho se necessário.

**11.3 Que conclusões você deve tirar da Figura 11.7? O projeto parece que terminará adiantado, atrasado ou dentro do cronograma?**  
**Resposta:** A equipe está adiantada. A Figura 11.7 mostra que a equipe está progredindo melhor do que o previsto e alcançou a velocidade esperada mais cedo. No entanto, não se deve tirar conclusões firmes após apenas duas iterações.

**11.4 Qual é a velocidade da equipe que terminou a iteração mostrada na Tabela 11.3?**  
**Resposta:** Dezesseis. Apenas as histórias totalmente concluídas são contabilizadas para a velocidade.

**11.5 Quais circunstâncias fariam com que um gráfico de burndown de iteração refletisse uma tendência ascendente?**  
**Resposta:** A tendência ascendente ocorre se novos trabalhos forem adicionados mais rapidamente do que o trabalho concluído, ou se a equipe descobrir que uma quantidade significativa de trabalho futuro foi subestimada.

**11.6 Preencha a Tabela 11.4 escrevendo os valores ausentes na tabela.**  
**Resposta:** Veja a Tabela B.4 para os valores preenchidos.

### Capítulo 12: Que Histórias Não São

**12.1 Quais são as principais diferenças entre histórias de usuários e casos de uso?**  
**Resposta:** Histórias de usuários geralmente abrangem um escopo menor e são menos detalhadas do que casos de uso. Histórias de usuários são mais voltadas para a comunicação e compreensão geral, enquanto casos de uso são mais detalhados e destinados a documentação permanente.

**12.2 Quais são as principais diferenças entre histórias de usuários e declarações de requisitos do IEEE 830?**  
**Resposta:** Declarações de requisitos do IEEE 830 focam em atributos da solução e são elaboradas antecipadamente, enquanto histórias de usuários focam nos objetivos do usuário e são desenvolvidas de forma iterativa. Histórias de usuários valorizam conversas sobre documentação formal.

**12.3 Quais são as principais diferenças entre histórias de usuários e cenários de design de interação?**  
**Resposta:** Cenários de design de interação são muito mais detalhados, descrevendo a persona e o contexto do uso em profundidade, enquanto histórias de usuários são mais gerais e focadas em objetivos do usuário.

**12.4 Para um projeto não trivial, por que é impossível escrever todos os requisitos no início do projeto?**  
**Resposta:** É impossível porque o ciclo de feedback é crucial. Conforme os usuários interagem com o sistema, novos requisitos emergem e ajustes são necessários.

**12.5 Qual é a vantagem de pensar nos objetivos dos usuários em vez de listar os atributos do software a ser construído?**  
**Resposta:** Pensar nos objetivos dos usuários ajuda a garantir que o produto final atenda às necessidades e expectativas dos usuários, ao invés de apenas satisfazer uma lista de atributos. Isso proporciona uma visão mais holística e orientada ao valor do produto.

### Capítulo 13: Por Que Histórias de Usuários?

**13.1 Quais são as quatro boas razões para usar histórias de usuários para expressar requisitos?**  
**Resposta:**  
1. **Comunicação verbal:** Promovem conversas e entendimento compartilhado.
2. **Compreensibilidade:** São fáceis de entender para todos os envolvidos.
3. **Tamanho adequado para planejamento:** São pequenas e manejáveis.
4. **Apoio ao desenvolvimento iterativo:** Facilitam a adaptação e evolução contínua.

**13.2 Quais podem ser as duas desvantagens de usar histórias de usuários?**  
**Resposta:**  
1. **Organização:** Em grandes projetos, pode ser difícil manter muitas histórias organizadas.
2. **Rastreabilidade:** Pode ser necessário complementar histórias com documentos adicionais para rastreabilidade.

**13.3 Qual é a principal diferença entre design participativo e empírico?**  
**Resposta:** No design participativo, os usuários são parte da equipe de design, enquanto no design empírico, os designers observam e estudam os usuários para tomar decisões de design.

**13.4 O que há de errado com a declaração de requisitos, "Todos os relatórios de várias páginas devem ser numerados"?**  
**Resposta:** A declaração é vaga e não especifica claramente o que significa "numerados" ou sob quais condições isso deve ser feito.

### Capítulo 14: Um Catálogo de Cheiros de Histórias

**14.1 O que você deve fazer se a equipe estiver constantemente encontrando dificuldades para planejar a próxima iteração?**  
**Resposta:** Verifique se as histórias são interdependentes, muito pequenas ou muito grandes. Ajustar o tamanho e a granularidade das histórias pode ajudar a facilitar o planejamento.

**14.2 O que a equipe deve fazer se estiver constantemente ficando sem espaço para escrever nos cartões de história?**  
**Resposta:** Use cartões menores para forçar a disciplina de manter as histórias breves e concisas.

**14.3 O que pode fazer com que o cliente tenha dificuldade em priorizar histórias?**  
**Resposta:** Se as histórias forem muito grandes ou pequenas, ou se não estiverem claras em termos de valor para o usuário ou cliente.

**14.4 Como saber se você está dividindo muitas histórias?**  
**Resposta:** Confie na intuição. Se histórias são divididas frequentemente por motivos além de serem épicos ou grandes demais para uma iteração, pode ser um sinal de que você está dividindo demais.

### Capítulo 15: Usando Histórias com Scrum

**15.1 Descreva as diferenças entre um processo incremental e um iterativo.**  
**Resposta:** Um processo **iterativo** refina o produto por meio de ciclos sucessivos, enquanto um processo **incremental** constrói e entrega o produto em partes ou incrementos.

**15.2 Qual é a relação entre o backlog do produto e o backlog do sprint?**  
**Resposta:** O backlog do produto contém todos os itens desejados para o produto. No início de cada sprint, os itens mais prioritários são selecionados e movidos para o backlog do sprint para serem trabalhados durante o sprint.

**15.3 O que se entende por incremento de produto potencialmente entregável?**  
**Resposta:** É um incremento do produto que é totalmente codificado, testado e pronto para ser entregue ou liberado aos usuários.

**15.4 Quem é responsável por priorizar o trabalho e selecionar o trabalho que a equipe executará durante um sprint?**  
**Resposta:** O Product Owner prioriza o trabalho, mas a equipe decide quais itens do backlog do produto serão selecionados e trabalhados durante o sprint.

**15.5 Quais perguntas são respondidas por cada membro da equipe no scrum diário?**  
**Resposta:**  
- O que você fez ontem?
- O que você vai fazer hoje?
- O que está no seu caminho?

### Capítulo 16: Tópicos Adicionais

**16.1 Como você deve lidar com um requisito para que um sistema seja dimensionado para uso por 1.000 usuários simultâneos?**  
**Resposta:** Escreva isso como uma restrição e planeje testes para validar o sistema com 100 usuários simultâneos inicialmente, aumentando progressivamente até 1.000 usuários em várias iterações.

**16.2 Você prefere escrever histórias em cartões de anotações ou em um sistema de software? Defenda sua resposta.**  
**Resposta:** Cartões de anotações são ideais para projetos presenciais e para manter histórias breves e visíveis. No entanto, para equipes distribuídas ou com requisitos rigorosos de rastreabilidade, um sistema de software pode ser preferível.

**16.3 Qual é o impacto de um processo iterativo na interface do usuário de um aplicativo?**  
**Resposta:** O refinamento iterativo pode causar mudanças frequentes na interface do usuário, o que pode dificultar a familiarização e o aprendizado dos usuários sobre o sistema.

**16.4 Dê alguns exemplos de sistemas que poderiam se beneficiar de uma consideração mais inicial da interface do usuário do que normalmente é dada em um projeto ágil.**  
**Resposta:**  
- Produtos comerciais que competem pela

 facilidade de uso.
- Software para iniciantes.
- Software usado esporadicamente, mas intensivamente (como software de preparação de impostos).
- Software para usuários com necessidades especiais, como baixa visão ou distúrbios de movimento.