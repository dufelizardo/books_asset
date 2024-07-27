# Capítulo 19

Quando a iteração se encerra e a equipe se prepara para a próxima, há várias atividades importantes para os testadores e a equipe como um todo:

### **1. Demonstração de Iteração**
- **Exibição das Histórias Concluídas:** O objetivo principal é mostrar as histórias finalizadas aos clientes, permitindo que eles vejam o aplicativo em ação, façam perguntas e ofereçam feedback.
- **Função dos Testadores:** Testadores frequentemente conduzem a revisão da iteração, aproveitando sua visão detalhada do que foi implementado. No entanto, outros membros da equipe, como o ScrumMaster ou analistas de negócios, também podem conduzir a demonstração.
- **Feedback do Cliente:** A demonstração é uma oportunidade para captar feedback valioso. Testadores podem identificar inconsistências e os clientes podem sugerir alterações, que podem ser pequenas ou exigir novas histórias para iterações futuras.
- **Perguntas Adicionais:** Após a demonstração, é útil perguntar aos clientes sobre quaisquer problemas com versões anteriores ou novas preocupações. Isso pode levar a novas ideias e melhorias.

### **2. Retrospectivas**
- **Objetivo das Retrospectivas:** Melhorar continuamente o processo de trabalho. É um momento para refletir sobre o que funcionou bem, o que não funcionou e o que pode ser ajustado para a próxima iteração.
- **Metodologia:** 
  - **Iniciar, Parar, Continuar:** Os membros da equipe discutem o que começar a fazer, o que parar de fazer e o que continuar fazendo. Isso ajuda a identificar ações concretas para melhorar o processo.
  - **Facilitador:** Geralmente, o ScrumMaster ou um facilitador conduz a reunião, garantindo que todos se sintam seguros para expressar suas opiniões.
- **Registro de Feedback:** Anote as sugestões e publique-as para que todos possam consultá-las durante a próxima iteração.

### **3. Exemplos Práticos de Retrospectiva**
- **Iniciar:**
  - Enviar histórias do próximo sprint mais cedo.
  - Evitar o processamento preguiçoso de registros únicos.
  - Comunicar alterações no banco de dados a todos.

- **Parar:**
  - Aceitar histórias com requisitos incompletos.

- **Continuar:**
  - Executar testes FitNesse para o código atual.
  - Documentar o que surge em reuniões informais.
  - Melhorar a comunicação e mostrar maquetes cedo.

### **4. Ações e Priorização**
- **Foco em Itens Importantes:** Se a lista de itens a serem abordados for longa, escolha um ou dois itens prioritários para concentrar esforços na próxima iteração.
- **Votação:** Use um sistema de votos para priorizar itens a serem abordados.

### **5. Avaliação e Ação**
- **Monitoramento:** No início da próxima iteração, reserve um tempo para revisar se as melhorias propostas foram eficazes.
- **Ajustes Necessários:** Se problemas persistirem, reavalie se a abordagem foi adequada ou se é necessário tentar uma solução diferente.

### **6. Discussão e Resolução de Problemas**
- **Discussão Objetiva:** Levante questões relacionadas aos testes de forma objetiva e sem atribuição de culpa. A equipe pode discutir e encontrar soluções para problemas identificados.

Em resumo, o encerramento da iteração envolve não apenas a revisão e demonstração das funcionalidades concluídas, mas também a reflexão crítica através de retrospectivas para melhorar o processo e preparar a equipe para a próxima iteração. Isso ajuda a garantir um ciclo contínuo de aprimoramento e entrega de um produto cada vez melhor.

Ao encerrar uma iteração e se preparar para a próxima, é crucial identificar e implementar melhorias para otimizar o processo. Aqui estão algumas ideias e abordagens para melhorar a eficiência da equipe e garantir que problemas identificados sejam resolvidos:

### **1. Identificação de Problemas e Definição de Ações**

- **Problemas de Cobertura de Testes:** Se muitos bugs no nível da unidade são descobertos após a codificação, pode ser necessário garantir que os programadores cubram mais código com testes de unidade. Considere:
  - Implementar uma regra para usar ferramentas de cobertura de código antes do check-in.
  - Criar cartões de tarefa para cada história que exijam a criação de testes de unidade.

- **Automação de Testes:** Se a automação de testes é incompleta, talvez seja necessário simplificar os testes ou aprimorar o design de testes. Ações podem incluir:
  - Começar com testes simples antes de abordar testes complexos.
  - Emparelhar com outros para melhorar o design de teste.

### **2. Regras e Diretrizes**

- **Regras da Equipe:** A equipe de Lisa estabeleceu regras que ajudaram a melhorar o fluxo de trabalho. Exemplos de regras incluem:
  - **Conclusão de Casos de Teste:** Completar os casos de teste de alto nível para todas as histórias até o quarto dia da iteração.
  - **Entrega e Teste de Histórias:** Entregar uma história para teste até o quarto dia.
  - **Foco em Histórias:** Concluir uma história de cada vez.
  - **Verificação Completa:** Garantir que 100% dos recursos sejam verificados até o fechamento do expediente no penúltimo dia da iteração.

### **3. Revisão e Monitoramento de Itens de Ação**

- **Revisão dos Itens de Ação:** No início de cada retrospectiva, revise quais itens de ação foram benéficos e quais não foram. Utilize rostos felizes, tristes ou neutros para indicar o sucesso ou os problemas com os itens. Pergunte-se:
  - **Razões para Falhas:** Alguns itens foram esquecidos? Restrições de tempo impediram a implementação? A ideia perdeu relevância?

- **Acompanhamento de Melhorias:** Itens que se tornam hábitos positivos podem ser movidos para a coluna "Continuar" e itens que não são úteis podem ser removidos. Mantenha uma lista visível e consulte-a regularmente durante a iteração.

### **4. Abordagens Criativas para Melhorias**

- **Backlog de Impedimentos:** Manter um backlog de impedimentos pode ser mais eficaz do que listas genéricas de "parar, começar e continuar". Esse backlog deve incluir todos os obstáculos, sejam eles relacionados a testes ou ferramentas.

- **Mapeamento do Fluxo de Valor:** Identifique o maior "tempo de espera" no fluxo de trabalho e use os "cinco porquês" para entender e abordar a causa raiz dos impedimentos.

- **Exemplo Prático:** Rafael Santos e Jason Holzer usaram um exemplo prático em que o gargalo de teste foi abordado. Eles mapearam as atividades do testador e identificaram tarefas que os programadores poderiam assumir. Isso ajudou a redistribuir responsabilidades e melhorou a eficiência.

### **5. Experimentos e Inovação**

- **Abordagens Inovadoras:** Experimente novas abordagens e soluções durante as retrospectivas. A participação ativa da equipe pode levar a soluções criativas e eficazes para problemas persistentes.

- **Integração de Testes:** Use as retrospectivas para discutir problemas relacionados a testes e envolver toda a equipe na busca de soluções.

### **6. Manutenção e Atualização Contínua**

- **Lista de Pendências:** Mantenha uma lista visível de impedimentos e problemas que precisam ser resolvidos. Revise esta lista regularmente e tome medidas para eliminar esses impedimentos.

### **Conclusão**

Implementar melhorias efetivas exige uma abordagem estruturada e criativa. Ao revisar os itens de ação, definir regras claras, experimentar novas abordagens e monitorar constantemente os obstáculos, sua equipe pode melhorar continuamente o processo e a qualidade do produto. A retrospectiva é uma oportunidade valiosa para aprender, crescer e adaptar-se, ajudando a equipe a enfrentar desafios e aprimorar o desempenho iterativo.

Comemorar os sucessos é essencial para manter a moral da equipe e incentivar uma cultura positiva e produtiva. Mesmo em um ambiente ágil, onde as iterações são rápidas e a ênfase está na continuidade do trabalho, reservar um tempo para reconhecer e celebrar as conquistas pode ter um impacto significativo na motivação e coesão da equipe. Aqui estão algumas maneiras de celebrar e reconhecer o sucesso, desde pequenas vitórias até grandes marcos:

### **1. Celebrações Regulares**

- **Friday Fun:** Após cada iteração, a equipe pode se reunir para uma atividade social, como um jogo, uma saída para beber, ou qualquer outra atividade que proporcione diversão e relaxamento. A equipe de Lisa, por exemplo, participa de “Friday Fun” para relaxar e fortalecer os laços.

- **Reconhecimento Diário:** Celebre pequenas vitórias, como a conclusão de uma linha de base de teste ou a correção de um bug crítico. Isso pode ser feito com elogios informais, reconhecimento em reuniões ou até mesmo pequenos gestos, como trazer guloseimas para a equipe.

### **2. Comemorações de Marcos**

- **Festividades para Grandes Marcos:** Para marcos significativos, como grandes lançamentos ou a conquista de metas importantes, uma festa para toda a empresa pode ser apropriada. Isso pode incluir eventos como almoços ou jantares comemorativos.

- **Reconhecimento Público:** Durante as reuniões de revisão, aproveite para reconhecer publicamente as contribuições da equipe. Se houver outras partes interessadas presentes, isso amplifica o reconhecimento e reforça o valor do trabalho realizado.

### **3. Caixa de Sapatos Shout-Out**

- **Shout-Out Shoebox:** Implementar uma caixa de sapatos decorada onde os membros da equipe podem colocar cartões de reconhecimento e elogios para colegas que fizeram um bom trabalho. No final da iteração ou em reuniões, essas mensagens são lidas em voz alta para toda a equipe. Esse método promove reconhecimento público e valoriza o trabalho em equipe.

### **4. Recompensas Pessoais e Simbolicas**

- **Reconhecimento Pessoal:** Ofereça recompensas pessoais para realizações individuais, como um presente para alguém que resolveu um problema complicado ou um reconhecimento simbólico, como uma estrela dourada para conquistas específicas.

- **Brindes e Presentes:** Pequenos brindes, como cartões-presente ou itens relacionados ao trabalho, podem ser oferecidos como reconhecimento por esforços excepcionais.

### **5. Integração e Coesão da Equipe**

- **Atividades de Formação de Equipe:** Organize atividades que ajudem a fortalecer os laços entre os membros da equipe. Isso pode incluir eventos sociais ou desafios colaborativos que incentivem a cooperação e a camaradagem.

- **Reflexão e Perspectiva:** Após as comemorações, reserve um tempo para refletir sobre o que foi alcançado e como isso pode impactar a próxima iteração. Isso ajuda a manter o foco nas metas e a motivação para enfrentar novos desafios.

### **6. Manutenção de Uma Cultura de Reconhecimento**

- **Cultura de Celebração:** Encoraje uma cultura onde os membros da equipe estão sempre atentos para reconhecer e celebrar os sucessos dos colegas. Isso cria um ambiente positivo e reforça o comportamento colaborativo e o compromisso com os objetivos da equipe.

- **Feedback e Melhoria Contínua:** Utilize o feedback das celebrações e reconhecimentos para melhorar continuamente os processos e práticas da equipe. As retrospectivas podem incluir discussões sobre como aprimorar a maneira de reconhecer e comemorar as conquistas.

### **Conclusão**

Comemorar sucessos, mesmo pequenos, é uma parte vital de manter a moral e a motivação da equipe em um ambiente ágil. Isso não apenas proporciona uma pausa necessária do trabalho intenso, mas também fortalece o espírito de equipe e incentiva um desempenho contínuo de alta qualidade. Ao implementar práticas de reconhecimento regulares e significativas, sua equipe poderá continuar a se sentir valorizada e motivada a alcançar novos sucessos.

Neste capítulo, discutimos práticas essenciais para encerrar uma iteração ou lançamento, com foco em como aprimorar a equipe e reconhecer suas conquistas:

1. **Revisão de Iteração:**
   - Realize uma revisão de iteração para obter feedback valioso da equipe do cliente.
   - Utilize esta oportunidade para mostrar histórias concluídas e coletar insights que podem influenciar o próximo ciclo de trabalho.

2. **Retrospectivas:**
   - As retrospectivas são fundamentais para a melhoria contínua da equipe.
   - Identifique áreas de melhoria, mas concentre-se em uma ou duas mudanças por vez para evitar sobrecarga.
   - Mantenha os itens de melhoria visíveis e faça um acompanhamento contínuo durante a iteração.

3. **Celebração de Sucessos:**
   - Comemore tanto os grandes quanto os pequenos sucessos para manter a moral da equipe.
   - Reconheça as contribuições individuais e coletivas de todos os membros da equipe.
   - Inclua atividades sociais ou simbólicas para reforçar o espírito de equipe e a motivação.

4. **Identificação e Superação de Obstáculos:**
   - Após cada iteração, identifique obstáculos relacionados a testes e discuta soluções para superá-los.
   - Envolva a equipe na busca de maneiras de resolver problemas e melhorar os processos.

Essas práticas ajudam a garantir um processo ágil eficiente e colaborativo, promovendo um ambiente de trabalho positivo e produtivo.