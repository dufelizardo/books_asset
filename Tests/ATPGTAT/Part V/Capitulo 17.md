# Capítulo 17

### Pontapé Inicial da Iteração: Papel dos Testadores Ágeis

O início de cada iteração é crucial para garantir que todos os aspectos do desenvolvimento e teste estejam alinhados. Aqui está um guia sobre como os testadores ágeis podem atuar efetivamente durante o planejamento e início da iteração:

#### **1. Sessão de Planejamento de Iteração**

- **Preparação Prévia:**
  - **Revisão da Iteração Anterior:** Antes do planejamento, é útil realizar uma retrospectiva para avaliar o que funcionou e o que pode ser melhorado.
  - **Revisão de Histórico:** Se você fez preparações antecipadas, a sessão de planejamento será mais eficiente.

- **Durante o Planejamento:**
  - **Discussão Detalhada:** A equipe de desenvolvimento deve discutir uma história de cada vez, escrever e estimar tarefas necessárias. A preparação antecipada pode acelerar este processo.
  - **Participação de Stakeholders:** Idealmente, o proprietário do produto ou outros representantes do cliente devem participar para fornecer detalhes e esclarecer dúvidas.

- **Uso de Ferramentas:**
  - **Visualização:** Utilize ferramentas como projetores para mostrar casos de teste, histórias e cartões de tarefas. Isso ajuda a manter todos na mesma página.

#### **2. Aprendendo os Detalhes das Histórias**

- **Recolha de Informações:**
  - **Perguntas e Exemplos:** Faça perguntas para esclarecer todos os aspectos das histórias e obtenha exemplos específicos. Isso ajuda a garantir que todos entendam o propósito e os detalhes da história.
  - **Exemplos e Testes:** Transforme exemplos em testes de aceitação para orientar o desenvolvimento. Assegure que todos na equipe compreendam o que constitui a conclusão da história.

- **Dimensionamento e Divisão:**
  - **Histórias Pequenas e Gerenciáveis:** As histórias devem ser pequenas o suficiente para serem completadas em poucos dias. Se uma história parecer muito grande, divida-a em partes menores.

#### **3. Considerando Todos os Pontos de Vista**

- **Diversidade de Perspectivas:**
  - **Papel dos Testadores:** Coloque-se no lugar de diferentes envolvidos: usuários, partes interessadas, desenvolvedores, etc. Avalie a história de múltiplas perspectivas para identificar possíveis impactos e problemas.
  - **Discussões de Impacto:** Identifique e discuta possíveis impactos imprevistos e problemas de desempenho. 

- **Pico de Desenvolvimento e Teste:**
  - **Teste de Novas Tecnologias:** Se estiver lidando com novas tecnologias ou funcionalidades, considere realizar um pico de desenvolvimento e teste para avaliar a viabilidade e os desafios.

#### **4. Evitando Aumento de Escopo**

- **Gerenciamento de Escopo:**
  - **Identificação de "Bling":** Esteja atento a componentes não essenciais que podem ser adiados ou removidos se o escopo começar a se expandir além do planejado.

- **Desafios de Implementação:**
  - **Questões de Desempenho:** Se surgirem questões de desempenho ou outras preocupações durante o planejamento, levante-as para discussão e considere realizar picos de teste para avaliar o impacto.

#### **Resumo de Atividades dos Testadores Ágeis no Início da Iteração**

1. **Contribuir para o Planejamento:** Participe ativamente das sessões de planejamento, ajudando a definir e detalhar histórias e testes.
2. **Clarificar Histórias:** Garanta que as histórias sejam compreendidas e testáveis, e colabore para escrever testes de aceitação de usuário.
3. **Avaliar Impactos:** Considere o impacto das histórias no sistema como um todo e identifique possíveis problemas.
4. **Gerenciar Escopo e Desafios:** Acompanhe o escopo da história e levante questões de desempenho e outros desafios potenciais.

Seguindo essas diretrizes, os testadores ágeis podem desempenhar um papel essencial em garantir que o início da iteração seja produtivo e que as histórias sejam bem compreendidas e prontas para o desenvolvimento e teste.

### Escrevendo Cartões de Tarefas para Testes e Desenvolvimento

Escrever e estimar cartões de tarefas é uma etapa essencial na iteração ágil, ajudando a garantir que tanto o desenvolvimento quanto os testes estejam bem planejados e sincronizados. Aqui está um guia sobre como fazer isso de forma eficaz:

#### **1. Escrever Cartões de Tarefas**

- **Identificação e Criação de Cartões:**
  - **Desenvolvimento e Testes:** Escreva cartões de tarefas para desenvolvimento e teste simultaneamente. Inclua todas as atividades necessárias, como a codificação da funcionalidade e a criação de casos de teste.
  - **Exemplos de Cartões de Tarefas:**
    - **Desenvolvimento:** “Implementar cálculo de custo de envio.”
    - **Teste:** “Escrever casos de teste FitNesse para cálculo de custo de envio.”

- **Revisão e Estimativa:**
  - **Revisão Coletiva:** Todos os membros da equipe devem revisar e dar feedback sobre os cartões. Isso ajuda a garantir que todos os aspectos sejam cobertos e que as estimativas sejam realistas.
  - **Estimativa de Tempo:** Estime o tempo necessário para cada tarefa. Inclua tempo para tarefas relacionadas a testes, como a escrita e a execução de testes unitários e de integração.

- **Exemplo de Estimativas:**
  - **Cartão de Desenvolvimento:** “Codificar integração com API de envio – 4 horas.”
  - **Cartão de Teste:** “Escrever e executar testes de integração com API – 6 horas.”

#### **2. Gerenciamento de Tarefas Durante a Iteração**

- **Organização no Storyboard:**
  - **Colunas do Storyboard:** Coloque todos os cartões de tarefas na coluna "A Fazer". À medida que o trabalho avança, mova os cartões para "Trabalho em Andamento" e, finalmente, para "Concluído".
  - **Sincronização de Cartões:** Certifique-se de que os cartões de teste e desenvolvimento estejam sincronizados. Em algumas equipes, os cartões de teste são movidos para "Trabalho em Andamento" antes dos cartões de desenvolvimento para fornecer uma direção clara para a codificação.

- **Exemplo de Fluxo:**
  - **Desenvolvimento:** Cartão "Codificar cálculo de custo de envio" vai para "Trabalho em Andamento."
  - **Teste:** Cartão "Escrever testes para custo de envio" também vai para "Trabalho em Andamento" para garantir que os testes acompanhem o desenvolvimento.

#### **3. Considerações Especiais**

- **Tarefas Externas e Recursos Compartilhados:**
  - **Dependências:** Se uma história depende de partes externas ou recursos compartilhados, como APIs de terceiros, inclua cartões de tarefas para garantir que essas dependências sejam abordadas.
  - **Exemplo de Tarefa Externa:** “Verificar acesso e especificações da API de BigExpressShipping.”

- **Correção de Bugs:**
  - **Estimativas para Bugs:** Inclua tempo estimado para correção e teste de bugs. Com o tempo, os membros da equipe aprenderão a estimar melhor esse tempo.
  - **Rastreamento de Bugs:** Pode ser útil rastrear bugs separadamente para obter uma estimativa mais precisa para iterações futuras.

- **Dados de Teste:**
  - **Preparação Antecipada:** Pense nos dados de teste durante o planejamento de iteração e garanta que estejam prontos quando a iteração começar.
  - **Exemplo de Tarefa de Dados:** “Preparar e carregar dados de produção para teste completo de snapshot.”

#### **4. Abordagens Alternativas**

- **Testes em Cartões de Desenvolvimento:**
  - **Integração de Testes:** Algumas equipes preferem integrar tarefas de teste diretamente nos cartões de desenvolvimento, evitando o modelo de mini-cascata onde o teste ocorre apenas após a codificação.
  - **Exemplo de Integração:** Um único cartão pode incluir “Codificar e testar funcionalidade de cálculo de custo de envio.”

- **Adaptação e Flexibilidade:**
  - **Adaptação às Necessidades:** Escolha a abordagem que melhor se adapta à sua equipe e ao projeto. Se os cartões de tarefas não estão funcionando como esperado, ajuste o processo conforme necessário.

#### **Conclusão**

Escrever e estimar cartões de tarefas é uma parte crucial da preparação para uma iteração ágil bem-sucedida. Ao seguir estas práticas, você pode garantir que todas as atividades, desde o desenvolvimento até os testes, sejam bem planejadas e executadas de forma eficiente. A colaboração da equipe, revisão contínua e ajustes nas estimativas e abordagens são fundamentais para o sucesso do processo ágil.

### Decidindo Sobre a Carga de Trabalho na Iteração

Decidir a carga de trabalho que sua equipe pode assumir em uma iteração é crucial para garantir um fluxo de trabalho equilibrado e a entrega bem-sucedida das histórias. Aqui está uma abordagem prática para gerenciar a carga de trabalho e garantir que os testes sejam adequadamente planejados e executados.

#### **1. Avaliação da Capacidade da Equipe**

- **Histórico de Performance:**
  - **XP:** Em Extreme Programming (XP), você não deve exceder o número de pontos de história que completou na última iteração. Isso proporciona uma base sólida e realista sobre o que sua equipe pode alcançar.
  - **Scrum:** No Scrum, o comprometimento é feito com base no tempo estimado necessário para concluir as histórias. Certifique-se de que o tempo estimado inclua todas as fases de desenvolvimento e teste.

- **Planejamento Conservador:**
  - **Estimativas Realistas:** Ao estimar o número de histórias para a iteração, seja conservador. Inclua histórias extras ou de risco mais alto para ter uma margem de segurança, e ajuste conforme a equipe libera tempo.

- **Exemplo:**
  - Se sua equipe completou 20 pontos de história na última iteração, comprometa-se com um número semelhante para a próxima. Se novas histórias ou tarefas são adicionadas, ajuste as estimativas para garantir que o volume de trabalho permaneça gerenciável.

#### **2. Considerações para Testabilidade**

- **Testabilidade das Histórias:**
  - **Planejamento Antecipado:** Avalie a testabilidade das histórias durante o planejamento da iteração. Considere como cada história será testada e quais desafios podem surgir.
  - **Impacto nos Testes:** Pergunte-se como as mudanças afetarão os testes e se há formas de simplificar ou melhorar a testabilidade.

- **Exemplo:**
  - Se uma história envolve mudanças em um fluxo de trabalho complexo, como um sistema de distribuição de pagamentos, certifique-se de que haja pontos de integração e verificação que permitam testes eficazes em cada etapa.

#### **3. Gerenciamento da Carga de Trabalho**

- **Alocação de Tempo para Testes:**
  - **Testes como Prioridade:** Garanta que o tempo alocado para testes seja suficiente. A carga de trabalho não deve se concentrar apenas na codificação, mas também na validação completa das funcionalidades.
  - **Distribuição de Trabalho:** Organize o trabalho de modo que as tarefas de codificação e teste estejam interligadas. Quando uma tarefa de codificação for concluída, deve haver uma tarefa de teste pronta para garantir que a funcionalidade esteja completa.

- **Exemplo:**
  - Para uma história que envolve a criação de uma nova funcionalidade, aloque tempo suficiente para escrever testes de unidade e testes de integração. Se um cartão de tarefa de codificação for movido para "Concluído", um cartão correspondente para testar a funcionalidade deve ser iniciado imediatamente.

#### **4. Gerenciamento de Riscos e Novas Tecnologias**

- **Identificação de Riscos:**
  - **Novas Tecnologias e Conhecimento:** Inclua novos componentes ou tecnologias como riscos no plano de teste. Estime generosamente para permitir a curva de aprendizado e a adaptação.
  - **Colaboração com Outras Equipes:** Se trabalhar com outras equipes ou usar novas tecnologias, comunique-se e coordene para resolver problemas potenciais.

- **Exemplo:**
  - Se a equipe está integrando uma nova API, escreva um cartão de tarefa para verificar a documentação da API e garantir que os dados possam ser acessados e testados adequadamente.

#### **5. Colaboração com Clientes**

- **Engajamento e Feedback:**
  - **Reuniões de Planejamento:** Colabore estreitamente com clientes ou proxies para garantir uma compreensão clara dos requisitos e testes necessários.
  - **Revisões e Ajustes:** Realize revisões regulares dos requisitos e casos de teste com os clientes para esclarecer dúvidas e ajustar o planejamento conforme necessário.

- **Exemplo:**
  - Ao trabalhar em uma história que envolve a geração de relatórios financeiros, revise os requisitos com o proprietário do produto para garantir que todos os dados e cálculos necessários estejam corretos e que os testes cubram todas as variações possíveis.

#### **Conclusão**

Gerenciar a carga de trabalho na iteração requer um equilíbrio cuidadoso entre desenvolvimento e teste. Ao adotar uma abordagem conservadora no planejamento, considerar a testabilidade das histórias, alocar adequadamente o tempo para testes, gerenciar riscos associados a novas tecnologias e colaborar estreitamente com clientes, você pode melhorar a eficácia da equipe e a qualidade do produto final. A comunicação aberta e o planejamento cuidadoso são fundamentais para o sucesso da iteração.

### Testes de Alto Nível e Exemplos: Abordagens e Práticas

Testes de alto nível são essenciais para orientar a equipe durante o desenvolvimento e garantir que o trabalho esteja alinhado com os requisitos do cliente. Aqui estão algumas práticas e dicas sobre como usar testes de alto nível efetivamente, com base nas descrições e exemplos fornecidos.

#### **1. Definindo Testes de Alto Nível**

Testes de alto nível são projetados para capturar o comportamento geral e o objetivo principal de uma história. Eles não entram em detalhes técnicos profundos, mas ajudam a equipe a entender o que deve ser alcançado e como o sistema deve se comportar em cenários principais.

- **Exemplos Práticos:**
  - **Custo de Envio:** Para a história sobre exibir o custo de envio para entrega em 5 dias, os testes de alto nível poderiam incluir:
    - Verificar se o custo de frete é exibido corretamente ao inserir um endereço de entrega.
    - Confirmar que o custo de envio estimado corresponde ao valor final na fatura.
    - Garantir que a alteração do endereço de entrega atualize o custo de frete.
    - Testar a atualização do custo de frete ao adicionar ou remover itens do carrinho.

- **Ferramentas de Representação:**
  - **Matriz de Teste:** Pode ser usada para representar visualmente diferentes cenários e seus resultados esperados.
  - **Desenhos e Diagramas:** Ajuda a ilustrar o fluxo de trabalho e a interface do usuário, como mostrado por Paul Rogers, para facilitar a compreensão das regras de negócios e comportamentos esperados.

#### **2. Criando Testes de Alto Nível**

- **Transformando Exemplos em Testes:**
  - **Identifique Cenários Chave:** Comece com exemplos de comportamento esperado e não esperado. Transforme esses exemplos em testes que capturam a funcionalidade principal e os requisitos da história.
  - **Modelagem Visual:** Utilize diagramas, fluxogramas ou esboços para representar visualmente como a funcionalidade deve operar. Isso ajuda a comunicar claramente os requisitos e facilita a compreensão para toda a equipe.

- **Ferramentas e Métodos:**
  - **Testes Gráficos:** Use técnicas de modelagem gráfica, como os desenhos de Paul Rogers, para representar regras e comportamentos complexos.
  - **Desenhos e Anotações:** Capturas de tela ou esboços de interfaces podem ser anotados para ilustrar alterações ou pontos de teste.

#### **3. Revisão e Colaboração com a Equipe**

- **Com Programadores:**
  - **Discussão Direta:** Realize reuniões para revisar os testes de alto nível com os programadores. Isso ajuda a garantir que todos tenham uma compreensão clara e alinhada da história e dos requisitos.
  - **Desenho e Diagramação:** Use quadros brancos ou ferramentas digitais para desenhar e revisar diagramas e fluxogramas de testes. Isso pode revelar áreas de confusão ou oportunidades de melhoria no design.

- **Com Clientes:**
  - **Revisão de Casos de Teste:** Apresente os testes de alto nível para os clientes para garantir que eles estão de acordo com os requisitos e expectativas. Isso proporciona uma oportunidade para ajustar e esclarecer qualquer detalhe.
  - **Feedback:** Solicite feedback dos clientes sobre os exemplos e cenários de teste para garantir que todas as suas necessidades sejam atendidas.

#### **4. Ajustes e Iterações**

- **Experimente e Ajuste:**
  - **Revisões Contínuas:** À medida que a equipe desenvolve e testa, esteja pronto para ajustar os testes de alto nível com base em novas descobertas e feedback.
  - **Documentação Atualizada:** Mantenha a documentação de testes atualizada e acessível para todos os membros da equipe.

- **Aprendizado Cruzado:**
  - **Compartilhamento de Conhecimento:** A revisão dos testes com programadores e clientes também serve como uma oportunidade para aprendizado cruzado, permitindo que os testadores entendam melhor as perspectivas técnicas e os programadores entendam melhor os requisitos de teste.

#### **Exemplo de Aplicação Prática**

- **História:** Exibir o custo de envio baseado no peso e destino do pedido.
- **Testes de Alto Nível:**
  - **Teste 1:** Inserir um endereço de entrega e verificar se o custo de frete é exibido corretamente.
  - **Teste 2:** Comparar o custo estimado de envio com o valor final na fatura.
  - **Teste 3:** Alterar o endereço de entrega e confirmar a atualização no custo de frete.
  - **Teste 4:** Adicionar ou remover itens do carrinho e verificar se o custo de frete é atualizado corretamente.

Esses testes devem ser complementados com discussões e revisões contínuas para garantir que atendam às necessidades e expectativas da equipe e do cliente. As técnicas visuais e a colaboração direta são chave para assegurar a precisão e a eficácia dos testes de alto nível.

A documentação de casos de teste, especialmente em projetos ágeis, desempenha um papel crucial para garantir a clareza e a manutenção do projeto. Quando bem organizada, essa documentação não apenas descreve os requisitos, mas também fornece um meio eficaz para verificar se o sistema está funcionando como esperado. Aqui está um guia sobre como usar casos de teste como documentação e assegurar que eles sejam eficazes e utilizáveis.

### **Casos de Teste como Documentação**

#### **1. Integração de Casos de Teste e Documentação**

- **Documentação Viva:** Em ambientes ágeis, a documentação deve ser dinâmica e refletir a atual condição do software. Casos de teste executáveis funcionam como documentação ao fornecer uma descrição clara e precisa do que o sistema deve fazer e permitir verificações contínuas de seu funcionamento.
  
- **Testes Executáveis:** São fundamentais porque têm resultados que podem ser verificados automaticamente, evitando interpretações errôneas dos requisitos. A documentação baseada em testes executáveis é difícil de contestar, pois os resultados são objetivos e mensuráveis.

- **Histórias e Requisitos:** Casos de teste não substituem histórias ou requisitos narrativos, mas complementam e validam esses documentos. Eles mostram, na prática, como o sistema deve se comportar em diferentes cenários e condições.

#### **2. Exemplo Prático: A História de Lisa**

- **Utilização de Testes FitNesse:** A história de Lisa destaca como usar testes, como o FitNesse, para demonstrar a funcionalidade real do sistema. Se houver um mal-entendido sobre os requisitos, um teste que reproduza o cenário exato pode fornecer uma visão clara do que está acontecendo, permitindo ajustes rápidos e precisos.

- **Benefícios dos Testes Executáveis:** Como mostrado, um teste executável pode ajudar a esclarecer e resolver disputas sobre a funcionalidade, fornecendo uma evidência objetiva do que o sistema faz.

#### **3. Organizando Casos de Teste e Documentação**

- **Uso de Wikis e Ferramentas de Documentação:**
  - **Vantagens e Desvantagens:** Wikis são flexíveis e permitem fácil colaboração, mas podem se tornar desorganizados se não forem bem estruturados. A hierarquia e a organização dos documentos podem se tornar confusas, dificultando a localização de informações específicas.
  - **Refatoração e Manutenção:** Revisitando e reestruturando regularmente a documentação pode ajudar a manter a clareza e a organização. A equipe deve definir uma estratégia clara para a estrutura de documentação e revisá-la periodicamente.

- **Ferramentas e Processos:**
  - **Pesquisa de Ferramentas:** Explore novas ferramentas que possam ajudar a organizar e gerenciar requisitos e testes. Ferramentas especializadas podem oferecer melhor organização, busca e rastreamento de mudanças.
  - **Redator Técnico:** Contratar um redator técnico pode ajudar a criar uma documentação bem organizada e compreensível, além de garantir que os casos de teste e os requisitos sejam apresentados de forma clara e acessível.

#### **4. Boas Práticas para Documentação de Casos de Teste**

- **Clareza e Precisão:**
  - **Escrita Clara:** Certifique-se de que os casos de teste são escritos de maneira clara e que os resultados esperados são específicos e compreensíveis.
  - **Revisões Regulares:** Revise e atualize os casos de teste regularmente para refletir mudanças nos requisitos e no sistema.

- **Acessibilidade e Organização:**
  - **Hierarquia de Documentos:** Organize a documentação em uma estrutura hierárquica clara para facilitar a navegação e a busca de informações.
  - **Indexação e Pesquisa:** Utilize ferramentas que permitam a fácil indexação e pesquisa de documentos para melhorar a acessibilidade.

- **Integração com Desenvolvimento:**
  - **Feedback Contínuo:** Mantenha um ciclo contínuo de feedback entre testadores, desenvolvedores e stakeholders para garantir que a documentação esteja sempre atualizada e precisa.
  - **Documentação de Mudanças:** Registre e comunique mudanças nos requisitos e na documentação para todos os membros da equipe.

### **Resumo**

Casos de teste são uma forma eficaz de documentação em projetos ágeis, pois oferecem uma descrição prática e verificável das funcionalidades do sistema. Para garantir que sejam úteis e mantidos, é crucial adotar boas práticas de organização, usar ferramentas adequadas e revisar a documentação regularmente. Isso não só facilita a comunicação entre equipes, mas também assegura que o sistema esteja sempre alinhado com os requisitos e expectativas dos stakeholders.

### **Resumo do Capítulo sobre Planejamento de Iteração e Testes Ágeis**

1. **Definição do Tom da Iteração:**
   - **Planejamento da Iteração:** A sessão de planejamento define a abordagem e o foco da iteração, impactando diretamente o desenvolvimento e os testes.

2. **Papel dos Testadores no Planejamento:**
   - **Aprendizado das Histórias:** Testadores ajudam a equipe a entender as histórias por meio de perguntas e análise de diferentes perspectivas.
   - **Tarefas de Teste:** Devem ser escritas e estimadas realisticamente, podendo ser incluídas nos cartões de tarefas dos desenvolvedores.

3. **Integração de Tarefas de Teste e Desenvolvimento:**
   - **Cartões de Tarefas:** É importante que as tarefas de teste sejam bem definidas e integradas com as tarefas de desenvolvimento, e que a equipe se comprometa a concluir todas as tarefas de teste.

4. **Compromisso com Testabilidade:**
   - **Testabilidade das Histórias:** Garantir que as histórias sejam testáveis e que haja dados de teste adequados no início da iteração é crucial, pois uma história não está completa até que todos os testes sejam concluídos.

5. **Colaboração com Clientes e Criação de Casos de Teste:**
   - **Exploração Detalhada:** Testadores colaboram com os clientes para detalhar as histórias e criar casos de teste de alto nível, ajudando os programadores a iniciar a codificação.

6. **Revisão e Comunicação dos Testes:**
   - **Revisão com Programadores:** Testadores revisam casos de teste e requisitos com os programadores para garantir uma comunicação clara e alinhamento.

7. **Casos de Teste como Documentação:**
   - **Documentação Baseada em Testes:** Casos de teste executáveis formam o núcleo da documentação do aplicativo, oferecendo uma forma objetiva e atualizada de verificar a funcionalidade do sistema.

Este resumo destaca a importância da colaboração e do planejamento cuidadoso no início de uma iteração para garantir que todas as histórias sejam bem entendidas, testáveis e documentadas adequadamente. A integração de tarefas de teste e desenvolvimento e a revisão contínua dos requisitos são essenciais para o sucesso da iteração e para a entrega de um produto de alta qualidade.
