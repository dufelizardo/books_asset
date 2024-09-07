# Apêndices


## Apêndice A

### Lista de Verificação do Processo de AST

Para garantir a qualidade e a eficácia do processo de automação de testes de software (AST) em cada fase, aqui está uma lista de verificação de alta qualidade dividida por fases. Esta lista pode ser usada como um guia para garantir que todas as etapas críticas sejam cobertas, mas deve ser adaptada conforme necessário para atender às necessidades específicas do seu ambiente e projeto.

---

#### **A.1 AST Fase 1: Coleta de Requisitos - Análise das Necessidades de Testes Automatizados**

**Lista:**
1. **Reunião Inicial e Visão Geral:**
   - A reunião inicial sobre o Sistema Sob Teste (SUT) foi realizada.
   
2. **Avaliação dos Processos Atuais:**
   - Os processos atuais de teste do SUT foram avaliados para identificar oportunidades de melhoria.

3. **Testabilidade e Automatizabilidade:**
   - Confirmou-se que os requisitos do SUT são testáveis e automatizáveis.

4. **Avaliação do Potencial de Automação:**
   - Foi realizada uma avaliação para identificar o que pode ser automatizado.

5. **Comunicação dos Requisitos do ASTF:**
   - Os requisitos para a Estrutura de Teste de Software Automatizado (ASTF) foram comunicados através de reuniões técnicas e processos claros.

6. **Coleta de Dados de Teste Manual:**
   - Foram coletados cronogramas de testes manuais e métricas de duração para servir como base de comparação para o Retorno sobre Investimento (ROI) da AST.

7. **Análise de Ferramentas e Reutilização:**
   - Analisou-se o uso atual de ferramentas de ciclo de vida do SUT e a possibilidade de reutilizar ferramentas existentes de AST.

8. **Avaliação de Necessidades de Ferramentas:**
   - Avaliou-se a necessidade de ferramentas adicionais de AST e suporte de teste, e foram feitas recomendações apropriadas.

9. **Identificação das Partes Interessadas:**
   - As partes interessadas foram identificadas e envolvidas.

10. **Definição do Ambiente de Teste:**
    - O ambiente de teste foi definido e discutido, incluindo a aquisição ou programação do ambiente.

11. **Definição dos Tipos de Teste:**
    - Os tipos de teste e os requisitos relacionados (funcionais, de segurança, simultaneidade, desempenho, etc.) foram definidos e comunicados.

12. **Desenvolvimento de Critérios de Entrada e Saída:**
    - Foram desenvolvidos os critérios de entrada e saída para o programa AST.

**Produtos:**
1. Relatório sobre oportunidades de melhoria de teste, conforme aplicável.
2. Passo a passo dos requisitos de teste AST com as partes interessadas, resultando em um acordo.
3. Relatório sobre recomendações de testes a serem automatizados.
4. Resumo inicial da abordagem de automação de teste de alto nível.
5. Relatório sobre a ferramenta de teste ou necessidades de desenvolvimento interno e recomendações associadas.
6. Identificação de componentes de código aberto e/ou freeware.
7. Utilitários de software AST identificados.
8. Requisitos iniciais dos dados de ensaio.
9. Configuração AST para o aplicativo.
10. Resumo do ambiente de teste.
11. Cronogramas iniciais de teste.
12. Tipos de teste e requisitos relacionados.
13. Resumo do nível de esforço atual do teste manual para comparação com medições automatizadas de ROI de teste.
14. Primeiro rascunho da "Estratégia de Projeto de Teste de Software Automatizado", incluindo um resumo dos produtos listados.
15. Critérios de entrada e saída do programa AST.

---

**Nota:** Este guia é uma base para análise e planejamento. Dependendo do contexto do projeto e das especificidades do ambiente, ajustes e adições podem ser necessários.

### A.2 AST Fase 2: Design e Desenvolvimento de Caso de Teste

**Lista de Verificação:**

1. **Compreensão da Tarefa e Comunicação:**
   - A tarefa de automação de teste foi compreendida e a meta de automação relacionada foi comunicada.
   - A arquitetura do SUT, os componentes subjacentes e os problemas técnicos foram compreendidos e discutidos.

2. **Consideração de Riscos:**
   - Os riscos associados foram identificados e as estratégias de mitigação foram implementadas.

3. **Avaliação dos Casos de Teste Manuais:**
   - Casos e procedimentos de teste manuais foram avaliados para determinar se podem ser reutilizados ou convertidos para testes automatizados.

4. **Definição da Arquitetura e Design do ASTF:**
   - A arquitetura e o design da Estrutura de Teste de Software Automatizado (ASTF) foram definidos.

5. **Desenvolvimento de Casos de Teste Automatizados:**
   - Casos de teste automatizados foram desenvolvidos usando técnicas de teste eficazes, como análise de limites, particionamento de equivalência, e testes baseados em risco.

6. **Definição e Desenvolvimento de Dados de Teste:**
   - Dados de teste foram definidos, desenvolvidos ou adquiridos conforme necessário para suportar os casos de teste.

7. **Rastreamento de Requisitos e Casos de Teste:**
   - Requisitos de teste, casos de teste e outros artefatos AST foram vinculados ao rastreamento de Requisitos de Teste e Manutenção (RTM).

8. **Passo a Passo e Acordo sobre Prioridades:**
   - O passo a passo dos casos/procedimentos de teste AST foi realizado, e um acordo sobre a prioridade dos casos de teste foi alcançado.

**Produtos:**

1. **Casos de Teste Documentados:**
   - Casos de teste de alto nível documentados a serem automatizados, com etapas de teste detalhadas.

2. **Passo a Passo e Acordo de Prioridade:**
   - Documentação do passo a passo do caso de teste e acordo sobre a prioridade dos casos.

3. **Implementação e Cronograma:**
   - Cronograma de implementação de casos de teste por fase e prioridade.

4. **Orientações de Arquitetura e Design ASTF:**
   - Orientações e documentação da arquitetura e design do ASTF.

5. **RTM Preenchido:**
   - RTM atualizado com requisitos de teste e artefatos relacionados.

6. **Relatórios de Problemas:**
   - Quaisquer relatórios de problemas de software associados à execução manual de testes para alimentar o esforço de automação.

7. **Cronogramas Atualizados:**
   - Cronograma finalizado e atualizado.

8. **Estratégia de Projeto de Teste de Software Automatizado:**
   - Segundo rascunho do documento "Estratégia de Projeto de Teste de Software Automatizado", incorporando as informações mais recentes e ajustes necessários.

---

**Nota:** Esta lista de verificação serve como um guia para garantir que todas as etapas essenciais da Fase 2 do processo de automação de testes sejam concluídas de forma eficaz. As etapas devem ser adaptadas conforme necessário para atender às necessidades específicas do projeto e ao contexto do ambiente de teste.

### A.3 AST Fase 3: Estrutura de Teste de Software Automatizado (ASTF) e Desenvolvimento de Script de Teste

**Lista de Verificação:**

1. **Análise e Reutilização:**
   - A estrutura de automação existente e os scripts de teste foram analisados para possíveis reutilizações.
   - Itens reutilizáveis foram identificados para determinar o delta de implementação necessário.

2. **Modificação e Desenvolvimento:**
   - A estrutura de automação foi modificada conforme necessário.
   - Novos scripts de teste foram desenvolvidos para atender aos requisitos dos casos de teste definidos.

3. **Monitoramento:**
   - O cronograma e o desempenho da automação estão sendo monitorados regularmente.

4. **Teste do ASTF:**
   - A Estrutura de Teste de Software Automatizado (ASTF) foi testada para garantir seu funcionamento correto e alinhamento com os requisitos.

**Ambiente de Teste:**

1. **Verificação dos Dados de Teste:**
   - Os dados de teste usados foram verificados quanto à eficácia, garantindo a profundidade e a amplitude necessárias para a cobertura dos testes.
   - Os conjuntos de dados que tocam em várias regras de negócios ou permissões de acesso foram verificados quanto à precisão.

2. **Configuração do Ambiente de Teste:**
   - A configuração específica do ambiente de teste foi determinada, e os prazos para pedidos de hardware foram considerados.
   - O ambiente de teste foi configurado para espelhar o ambiente de produção ou foi avaliada a eficácia de usar um ambiente virtual (como VMWare) para testes funcionais iniciais.
   - Métodos de extrapolação aceitáveis foram considerados para avaliar a eficácia dos testes.

3. **Permissões e Segurança:**
   - As permissões de acesso e segurança foram configuradas corretamente para permitir a instalação do software e a execução do software de automação de teste, bem como do software aplicativo e seus componentes.

4. **Configurações de Teste:**
   - As configurações de teste foram definidas e validadas para garantir que o ambiente de teste esteja pronto para a execução dos testes automatizados.

**Produtos:**

1. **ASTF Implementado e/ou Modificado:**
   - Estrutura de Teste de Software Automatizado (ASTF) implementada ou modificada conforme necessário.

2. **Automação de Casos de Teste:**
   - Scripts de teste recém-desenvolvidos para automação de casos de teste.

3. **Passo a Passo de Casos de Teste Automatizados:**
   - Passo a passo de alto nível dos casos de teste automatizados documentado e revisado com o cliente.

4. **Passo a Passo da Configuração do Ambiente de Teste:**
   - Passo a passo documentado da configuração do ambiente de teste.

5. **Relatório de Cobertura de Teste Automatizado:**
   - Relatório detalhado sobre a cobertura de teste automatizado, incluindo áreas cobertas e lacunas identificadas.

6. **RTM Atualizado:**
   - Requisitos de Teste e Manutenção (RTM) atualizado com os novos artefatos e informações relacionadas à automação.

7. **Configurações de Teste:**
   - Configurações de teste documentadas e validadas para garantir a execução adequada dos testes automatizados.

---

**Nota:** Esta lista de verificação é uma ferramenta para assegurar que todos os aspectos críticos da Fase 3 do processo de automação de testes sejam abordados. As etapas devem ser ajustadas conforme necessário para se adequar ao contexto e às necessidades específicas do projeto.

### A.4 AST Fase 4: Execução Automatizada de Testes e Relatórios de Resultados

**Lista de Verificação:**

1. **Critérios de Entrada e Saída:**
   - Os critérios de entrada e saída para a fase de execução de testes foram compreendidos e estão sendo seguidos rigorosamente.

2. **Ambiente de Teste:**
   - O ambiente de teste foi devidamente isolado do ambiente de desenvolvimento para garantir a integridade dos resultados dos testes.

3. **Execução de Testes:**
   - A estrutura de automação e os scripts de teste foram executados conforme planejado.

4. **Registro de Status:**
   - O status de aprovação ou reprovação de cada execução de teste foi registrado de maneira precisa e detalhada.

5. **Relatórios de Problemas:**
   - Relatórios de problemas de software foram produzidos conforme necessário.
   - O ciclo de vida de rastreamento de defeitos está sendo seguido, e os defeitos são rastreados até o fechamento.

6. **Comparação de Tempos de Teste:**
   - Os tempos de execução de testes manuais e automatizados foram comparados para começar a construir o retorno sobre investimento (ROI) da automação.

7. **Monitoramento:**
   - O desempenho da automação e o cronograma do projeto estão sendo monitorados para garantir que o projeto esteja no caminho certo.

**Produtos:**

1. **Relatório de Teste:**
   - Relatório abrangente de teste, incluindo o status de aprovação ou reprovação por caso de teste e requisito. Este relatório deve incluir um RTM (Requisitos de Teste e Manutenção) atualizado.

2. **Tempos de Execução de Testes:**
   - Relatórios detalhados dos tempos de execução dos testes manuais e automatizados, incluindo relatórios iniciais sobre o ROI da automação.

3. **Apresentação do Resumo do Teste:**
   - Apresentação detalhada do resumo do teste, incluindo os principais resultados, descobertas e recomendações.

4. **Treinamento AST:**
   - Treinamento fornecido para a equipe, conforme necessário. Isso pode incluir um guia do usuário para o ASTF (Framework de Teste de Software Automatizado), se aplicável.

---

**Nota:** Esta lista de verificação é projetada para assegurar que todos os aspectos críticos da Fase 4 sejam abordados de maneira completa e eficiente. Ajustes podem ser necessários com base nas particularidades e necessidades específicas do projeto de automação de testes.

### A.5 AST Fase 5: Revisão e Avaliação do Programa

**Lista de Verificação:**

1. **Critérios de Saída:**
   - Verifique se os esforços de Automação de Software de Teste (AST) satisfizeram todos os critérios de saída estabelecidos anteriormente.

2. **Conclusão do Esforço de Automação:**
   - Confirme que o esforço de automação para o Aplicativo em Teste (AUT) foi concluído conforme o planejado.

3. **Documentação de Lições Aprendidas:**
   - Documente todas as lições aprendidas durante o processo de automação de teste para referência futura e melhoria contínua.

4. **Análise de Causa Raiz:**
   - Realize qualquer análise de causa raiz necessária para identificar e entender as causas subjacentes de quaisquer problemas encontrados durante o processo.
   - As ações apropriadas para resolver esses problemas devem ser tomadas.

**Produtos:**

1. **Relatório Final do Programa AST:**
   - Prepare um relatório final abrangente do programa AST que inclua todos os artefatos relevantes discutidos nas fases anteriores. Este relatório deve conter:
     - **Métricas de Status:** Informações detalhadas sobre o desempenho do programa, incluindo métricas de sucesso e áreas de melhoria.
     - **Resultados de Testes:** Resultados detalhados de todos os testes realizados, incluindo casos de teste e suas execuções.
     - **Análise de Causa Raiz:** Detalhes sobre a análise de causa raiz realizada e as ações corretivas implementadas.
     - **Outros Artefatos Relevantes:** Qualquer outro documento ou artefato relevante para a revisão e avaliação do programa.

---

**Nota:** A revisão e avaliação do programa são fundamentais para garantir que o processo de automação de testes tenha atingido seus objetivos e para identificar oportunidades para aprimoramento futuro. A documentação completa e a análise crítica ajudam a melhorar a eficácia dos futuros esforços de automação de testes.
