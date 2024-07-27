# Capítulo 20

Neste capítulo, discutimos como os testadores podem contribuir para a entrega bem-sucedida de um produto, enfatizando a importância do ajuste e acabamento, planejamento, e a celebração dos sucessos:

1. **O Que Faz um Produto:**
   - **Valor ao Cliente:** Não é apenas sobre codificar e testar, mas garantir que o produto entregue agregue valor real ao cliente. Um produto bem entregue é aquele que atende às expectativas e constrói uma boa relação com o cliente.

2. **Ajuste e Acabamento:**
   - **Lista de Verificação:** Use uma lista de verificação para garantir que todos os itens necessários, como licenças, acordos legais e detalhes finais, sejam incorporados ao produto antes do lançamento.
   - **Preparação na Última Iteração:** Monte todos os componentes finais durante a última iteração de desenvolvimento para evitar a necessidade de ajustes posteriores.

3. **Planejamento e Tempo de Teste:**
   - **Dívida Técnica e Refatoração:** Planeje iterações regulares para refatoração e redução da dívida técnica. Isso pode envolver sprints dedicados apenas à correção de bugs e melhoria do código.
   - **Endurecimento:** Para equipes novas ou que acumularam muitos bugs, considere uma iteração extra dedicada ao endurecimento, focando apenas em encontrar e corrigir problemas existentes.

4. **Integração Contínua e Estabilidade:**
   - **Compilações Estáveis:** Trabalhe para garantir que uma compilação estável esteja disponível diariamente, de modo que a equipe possa entregar uma versão confiável e pronta para produção com mais frequência.

5. **Retrospectivas e Melhoria Contínua:**
   - **Aprendizado e Integração:** Use retrospectivas e outras práticas de melhoria para integrar melhor testes e codificação. Trabalhe para que o código produzido em cada iteração esteja pronto para produção, reduzindo a necessidade de ajustes finais.

6. **Celebração de Sucessos:**
   - **Reconhecimento e Moral:** Celebre os sucessos, grandes e pequenos, para manter a moral da equipe alta e reconhecer as contribuições individuais e coletivas.

Esses princípios ajudam a garantir que o produto final não apenas atenda aos requisitos técnicos, mas também ofereça valor real ao cliente e se destaque pela qualidade e confiabilidade.

**O Jogo Final: Preparando a Entrega**

O conceito de "jogo final" refere-se à fase final antes da entrega do produto, onde a equipe faz os últimos ajustes e garante que o produto esteja pronto para o lançamento. Aqui estão os principais pontos abordados sobre essa fase crucial:

1. **Definição do Jogo Final:**
   - **Últimos Ajustes:** O jogo final é o momento de finalizar detalhes e não uma fase para correção de bugs significativos. Idealmente, você deve ter corrigido a maioria dos bugs antes dessa fase.
   - **Coordenação:** Colabore com grupos e indivíduos que gerenciam ambientes de preparo e produção, bem como com administradores externos. Isso inclui coordenar com operações e gerentes de configuração.

2. **Planejamento do Tempo para o Jogo Final:**
   - **Duração Variável:** O tempo necessário pode variar dependendo da maturidade da equipe e da complexidade do produto. Pode ser um dia, uma semana, ou até uma iteração inteira.
   - **Teste e Integração:** Use esse tempo para testar integrações e cenários finais. Inclua testes exploratórios e validações finais do sistema.

3. **Testes em Ambiente de Preparo:**
   - **Ambiente Realista:** Teste o aplicativo em um ambiente de preparo que imite a produção para validar a implantação e os processos de lançamento. 
   - **Testes Não Funcionais:** Realize testes de carga, desempenho e recuperação, que são críticos para garantir a robustez do produto em condições reais.

4. **Coordenação com Equipes Externas:**
   - **Integração Externa:** Certifique-se de testar a integração com aplicativos externos e parceiros. Esteja preparado para ajustar o aplicativo conforme necessário durante o jogo final.

5. **Testando o Release Candidate:**
   - **Automação e Testes Manuais:** Realize testes de regressão automatizados e planeje tempo para testes manuais se necessário. Avalie os riscos e ajuste os testes conforme as mudanças feitas no Release Candidate.

6. **Histórias e Exemplos:**
   - **História de Lisa:** Mostra a importância de testar em janelas específicas e colaborar com outras equipes para garantir que todas as partes do sistema estejam integradas e funcionando corretamente.
   - **História de Janet:** Destaca a importância de testar com parceiros externos reais para evitar surpresas e garantir que todas as integrações funcionem conforme o esperado.

**Resumo:**
O "jogo final" é uma fase crítica onde você faz os últimos ajustes e testes antes do lançamento. Envolve uma coordenação detalhada, testes finais em ambientes de preparo e a integração com sistemas e parceiros externos. Planeje adequadamente e utilize esse tempo para garantir que o produto esteja totalmente pronto para a produção.

**Conversão de Dados e Atualizações de Banco de Dados**

Na fase final do desenvolvimento de um aplicativo, a gestão eficaz das alterações de banco de dados é crucial para garantir uma transição suave de dados e a integridade do sistema. Aqui estão os principais aspectos a considerar para a conversão de dados e atualizações de banco de dados:

### **1. Gestão das Alterações no Banco de Dados**

- **Alterações e Compatibilidade:** Quando um aplicativo evolui, pode haver alterações no banco de dados, como a adição ou remoção de colunas e a modificação de campos. Para novos aplicativos, recriar o banco de dados a cada compilação pode ser viável. No entanto, para aplicativos em produção com dados existentes, essa abordagem não é adequada.

- **Colaboração:** É essencial que especialistas em banco de dados, programadores e testadores trabalhem juntos para garantir a liberação bem-sucedida das alterações no banco de dados. Scripts de atualização devem ser criados e testados continuamente para garantir consistência entre ambientes de desenvolvimento, teste e produção.

- **Scripts de Atualização:** Scripts de banco de dados devem ser parte da compilação e testados continuamente. Alternativamente, diffs de banco de dados podem ser utilizados para identificar e aplicar alterações.

### **2. Automação e Testes**

- **Automação:** A automação de migrações de dados e scripts de atualização reduz a chance de erros humanos e melhora a capacidade de testar as mudanças. Ferramentas nativas, scripts de shell e arquivos de comando podem ser usados para automação.

- **Testes com Dados Reais:** Testar com dados reais de clientes é crucial, pois os dados podem variar significativamente em formato e integridade. Garanta que todas as alterações sejam compatíveis com dados existentes para evitar problemas em produção.

- **Testes de Atualização:** Após executar scripts de atualização, testes manuais e automatizados devem ser realizados para verificar se as alterações foram aplicadas corretamente.

### **3. Estratégias de Mitigação e Limitação de Riscos**

- **Limpeza de Dados:** A limpeza de dados para conformidade com novas restrições deve ser considerada como parte da estratégia de mitigação. Isso pode envolver a manipulação dos dados existentes para que estejam em conformidade com as novas regras.

- **UAT e Implementação Gradual:** Se não for possível simular adequadamente os dados de produção, considere realizar testes de aceitação no local do cliente ou realizar lançamentos em etapas menores. Desenvolva novas funcionalidades em paralelo com as antigas e use mecanismos de ativação para alternar entre elas.

### **4. Teste de Instalação**

- **Prática de Implantação:** Equipes responsáveis pela implantação devem praticar o processo de instalação para identificar e corrigir problemas antes do lançamento para produção.

- **Testes de Instalação:** Teste a instalação do produto em diferentes sistemas operacionais e hardware para garantir que a instalação seja feita sem causar interrupções significativas e que a experiência do usuário seja satisfatória.

### **5. Comunicação e Coordenação**

- **Reuniões Extras:** Reuniões adicionais e stand-ups rápidos podem ser úteis para garantir que todos os aspectos do lançamento estejam cobertos e que nada seja esquecido.

- **Cartões de Tarefa:** Use cartões de tarefas ou listas de verificação para garantir que todas as etapas do lançamento sejam seguidas. Mesmo equipes experientes podem se beneficiar desses lembretes, especialmente quando novos membros estão envolvidos.

### **Histórias e Exemplos:**

- **História de Lisa:** Mostra a importância de garantir que todos os esquemas de teste estejam sincronizados com a produção e a necessidade de scripts de atualização consistentes. Enfatiza a criação de scripts em cada iteração e a verificação de mudanças antes do lançamento.

- **História de Janet:** Destaca a importância de testar cenários de instalação, incluindo a transferência de licenças e a compatibilidade com versões anteriores, para evitar problemas no suporte ao cliente.

### **Resumo:**

A conversão de dados e as atualizações de banco de dados são componentes críticos para garantir um lançamento bem-sucedido. A automação, testes rigorosos, limpeza de dados, planejamento de implantação e comunicação eficaz são essenciais para minimizar riscos e garantir que o produto funcione conforme o esperado em todos os ambientes.

**E se a Versão Não Estiver Pronta?**

Mesmo com um planejamento cuidadoso e acompanhamento contínuo do progresso, desastres podem ocorrer no final do ciclo de desenvolvimento, que podem ameaçar a capacidade da equipe de lançar um produto conforme o cronograma. Aqui estão algumas estratégias e considerações para lidar com situações em que uma versão não está pronta para o lançamento:

### **1. Diagnóstico Precoce e Flexibilidade**

- **Acompanhamento Constante:** Utilize métricas e ferramentas como gráficos de burndown, conjuntos de testes de regressão e storyboards para monitorar o progresso. Isso ajuda a identificar problemas com antecedência e ajustar o cronograma conforme necessário.

- **Flexibilidade na Iteração:** Se um problema crítico for detectado tarde, considere pular o lançamento e usar o tempo da próxima iteração para corrigir os problemas. No entanto, adiar o lançamento pode impactar o cronograma e deve ser evitado sempre que possível.

### **2. Estratégias para Situações Críticas**

- **Pular o Lançamento:** Em ciclos de lançamento mais curtos (como duas semanas), pular um lançamento e agendar duas iterações para o próximo ciclo pode ser uma solução. Isso permite tempo adicional para resolver problemas críticos sem comprometer a qualidade.

- **Atraso de Lançamento:** Se a situação for crítica e uma data fixa é necessária, considere atrasar o lançamento por um ou dois dias para resolver problemas críticos. Isso pode ajudar a garantir que o produto lançado esteja em um estado mais estável e confiável.

- **Lançamento com Patch:** Se o lançamento não puder ser adiado, libere o que está pronto e planeje um lançamento de patch imediato para corrigir problemas identificados. Isso pode ser uma abordagem viável para problemas que não afetam gravemente a funcionalidade principal do produto.

### **3. Ciclos de Lançamento Mais Longos**

- **Planejamento de Jogo Final:** Para ciclos de lançamento mais longos, com mais de três meses, planeje um período de validação final de pelo menos duas semanas. Isso proporciona mais tempo para identificar e corrigir problemas.

- **Avaliação Antecipada:** Com um ciclo mais longo, você tem mais tempo para avaliar o risco e decidir entre ajustar o cronograma ou remover funcionalidades menos críticas.

### **4. Colaboração e Decisões**

- **Avaliação de Alternativas:** Se o lançamento está em risco devido a falhas de última hora, avalie alternativas como adiar o lançamento, restaurar código anterior temporariamente ou lançar um patch. As decisões devem ser tomadas com base na necessidade e impacto para os clientes.

- **Envolvimento da Equipe e Cliente:** Em situações críticas, envolva toda a equipe e, se necessário, a equipe do cliente para brainstorm e encontrar a melhor solução. A comunicação aberta ajuda a tomar decisões informadas e ajustadas à realidade.

### **5. Prevenção e Melhoria Contínua**

- **Evitar Espirais de Morte:** Trabalhe para evitar ciclos contínuos de atraso e recuperação. Foque em uma abordagem disciplinada para garantir que o produto esteja pronto para o lançamento conforme o cronograma.

- **Análise e Melhoria:** Após um atraso, analise as causas do problema e tome medidas para evitar que ocorram no futuro. Aprender com erros passados e ajustar processos são fundamentais para melhorar a capacidade da equipe de entregar produtos dentro do prazo.

### **Histórias e Exemplos:**

- **História de Lisa:** Lisa ilustra como a equipe pode adotar diferentes abordagens quando enfrenta problemas de última hora, como atrasar o lançamento por alguns dias, pular um lançamento ou realizar uma iteração especial para corrigir problemas. Ela destaca a importância de disciplina e melhoria contínua para evitar problemas recorrentes.

### **Resumo:**

Se a versão não estiver pronta para o lançamento, a equipe deve adotar uma abordagem flexível e estratégica para resolver problemas. Avalie alternativas como atrasar o lançamento, liberar um patch ou pular o lançamento, dependendo da gravidade da situação. A colaboração estreita e o planejamento adequado são essenciais para lidar com imprevistos e garantir a entrega de um produto de alta qualidade. Evite cair em espirais de atraso e trabalhe constantemente para melhorar processos e evitar problemas futuros.

Você trouxe um ponto crucial sobre a importância de envolver o cliente no processo de testes e aceitação de um produto de software. Vamos explorar os principais pontos abordados sobre o teste do cliente, como o Teste de Aceitação do Usuário (UAT), os testes Alpha/Beta e a definição de critérios de aceitação para lançamentos.

### Teste de Aceitação do Usuário (UAT)

**UAT** é fundamental para garantir que a solução atenda às expectativas dos usuários finais e funcione conforme o esperado no ambiente real do cliente. Algumas práticas e recomendações incluem:

1. **Envolvimento dos Clientes**: O UAT é realizado pelos clientes ou usuários finais para validar a funcionalidade e a usabilidade do sistema. Idealmente, isso ocorre quando o sistema está estável o suficiente, mas pode ser necessário ajustar o cronograma para acomodar o feedback do cliente.

2. **Integração com o Cronograma de Lançamento**: Em algumas situações, pode ser benéfico integrar o UAT com o ciclo final de desenvolvimento, especialmente se o tempo for limitado. Isso permite que a equipe de desenvolvimento e os usuários façam seus testes simultaneamente, economizando tempo.

3. **História de Janet**: Janet compartilha uma experiência em que, devido a um prazo apertado, o UAT foi realizado em paralelo com o teste final do sistema. Essa abordagem foi possível graças à confiança que o cliente tinha na equipe e à qualidade consistente dos lançamentos anteriores.

### Testes Alpha e Beta

Para organizações que distribuem software a uma ampla base de clientes, os testes Alpha e Beta são importantes para coletar feedback em diferentes estágios de maturidade do produto:

1. **Alpha Testing**: Realizado internamente ou com um grupo seleto de clientes, foca em identificar grandes problemas antes do lançamento mais amplo. É importante escolher clientes que possam fornecer feedback construtivo sem esperar um produto finalizado.

2. **Beta Testing**: Mais próximo do UAT, este teste é realizado com uma versão relativamente estável do software. É utilizado para validar o produto em um ambiente real, mas ainda não é considerado uma versão final.

### Ciclos de Teste Pós-Desenvolvimento

Em projetos grandes, pode ser necessário realizar testes adicionais após o desenvolvimento. Isso pode ocorrer devido a várias razões:

1. **Acesso ao Ambiente de Teste**: Em projetos complexos, o ambiente de teste pode estar disponível apenas em janelas de tempo específicas. Isso exige coordenação adicional e pode exigir que a equipe de desenvolvimento continue com novos trabalhos enquanto o UAT está em andamento.

2. **História de Lisa**: Lisa relata um cenário onde os testes pós-desenvolvimento foram essenciais devido à disponibilidade limitada do ambiente de teste. A equipe precisou dividir suas responsabilidades para garantir que o teste e o desenvolvimento pudessem continuar sem atraso.

### Critérios de Aceitação de Lançamento

Definir quando um produto está pronto para lançamento é essencial para garantir que ele atenda às expectativas de qualidade e funcionalidade. Algumas diretrizes incluem:

1. **Critérios de Aceitação**: Definem o que precisa ser atendido para que o produto seja aceito. Isso pode incluir desempenho, cobertura de código, e ausência de bugs críticos. É importante definir esses critérios de maneira clara e garantir que todos os envolvidos os compreendam.

2. **Critérios de "Cozimento"**: Bob Galen propõe uma abordagem de múltiplos níveis para definir os critérios de aceitação, começando com a definição de critérios para histórias individuais e expandindo para o nível de lançamento. Essa abordagem ajuda a alinhar as expectativas e garantir que todas as áreas sejam cobertas.

3. **Compilações Release Candidate**: A equipe de Coni Tartaglia utiliza uma lista de verificação para garantir que a compilação do candidato a lançamento atenda a todos os critérios e esteja pronta para ser distribuída. Essa abordagem inclui validar que todos os testes acordados foram aprovados e que não há defeitos críticos abertos.

### Conclusão

O envolvimento do cliente e a definição clara dos critérios de aceitação são fundamentais para o sucesso de um lançamento de software. Testadores desempenham um papel crucial em ajudar a definir e alcançar esses critérios, trabalhando estreitamente com a equipe de desenvolvimento e os clientes para garantir que o produto final atenda às expectativas e esteja pronto para produção.

Se precisar de mais detalhes ou quiser explorar um aspecto específico, sinta-se à vontade para perguntar!

