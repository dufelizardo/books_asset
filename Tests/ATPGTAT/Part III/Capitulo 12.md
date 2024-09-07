# Capítulo 12

### Resumo dos Quadrantes de Teste e Exemplo Prático

Neste capítulo, revisitamos os quatro quadrantes de teste ágeis e apresentamos um exemplo prático de uma equipe que usou testes de todos os quadrantes para um projeto complexo.

#### Revisão dos Quadrantes de Teste

1. **Quadrante 1: Testes Funcionais**:
   - **Propósito**: Validar a funcionalidade do sistema com base em requisitos específicos.
   - **Exemplos**: Testes de aceitação, testes exploratórios.

2. **Quadrante 2: Testes de Integração**:
   - **Propósito**: Testar a integração de componentes e serviços para garantir que eles funcionem juntos corretamente.
   - **Exemplos**: Testes de integração, testes de sistema.

3. **Quadrante 3: Testes de Sistema**:
   - **Propósito**: Avaliar o sistema completo e seu comportamento em condições reais ou simuladas.
   - **Exemplos**: Testes de desempenho, escalabilidade, carga e estresse.

4. **Quadrante 4: Testes Voltados para a Tecnologia**:
   - **Propósito**: Examinar aspectos técnicos e de infraestrutura do sistema, como segurança, gerenciamento de memória e capacidade de manutenção.
   - **Exemplos**: Testes de segurança, compatibilidade, confiabilidade e instalação.

#### Exemplo de Projeto Ágil

**Contexto do Projeto:**

- **Aplicativo**: Sistema de Monitoramento Remoto de Dados para poços de petróleo e gás.
- **Arquitetura**: Dispositivos de monitoramento via satélite, transmissão de dados para servidores, interface web e sistema de notificação.

**Equipe e Processo:**

- **Equipe**: 4 programadores de software, 2 programadores de firmware, 3-4 testadores, 1 engenheiro de produto, 1 gerente externo.
- **Metodologia**: Práticas XP, programação em pares, TDD (Desenvolvimento Orientado a Testes).
- **Relatórios**: Scrum para relatórios externos, iterações de duas semanas com lançamentos a cada quatro meses.

**Ambientes de Teste:**

1. **Ambiente de Novas Histórias**: Atualizado com a versão mais recente para testes de novas histórias.
2. **Ambiente de Problemas Relatados**: Continha a última versão lançada para testes de problemas relatados.
3. **Ambiente de Teste Completo**: Para testes de carga, confiabilidade e integrações completas.

**Testes Impulsionando o Desenvolvimento:**

- **Testes Unitários**: 
  - **Importância**: Suporte à programação e design do sistema.
  - **Prática**: Implementados com TDD e programação em pares, levando a uma redução significativa de bugs pós-codificação e melhorias na estabilidade do sistema legado.
  - **Evolução**: À medida que o sistema legado era alterado, novos testes unitários eram adicionados para garantir estabilidade e suportar refatorações.

- **Testes de Aceitação**:
  - **Importância**: Garantir que o sistema atenda aos requisitos dos usuários e partes interessadas.

**Observações Finais:**

- **Integração Contínua**: Utilização do CruiseControl para compilações constantes.
- **Retrospectivas**: Realizadas após cada iteração para melhorar o processo e corrigir problemas.

A equipe mostrou como uma abordagem estruturada e o uso de diferentes tipos de testes podem levar a um desenvolvimento ágil e bem-sucedido, garantindo que todos os aspectos do sistema sejam testados de maneira eficaz e eficiente.

### Testes de Aceitação e Automação em Projetos Ágeis

#### Testes de Aceitação

- **Responsabilidade**: O engenheiro de produto, atuando como proxy do cliente, era responsável pela criação dos testes de aceitação. Estes testes variavam em formato dependendo da história e incluíam dados, configuração necessária, variações críticas e exemplos para esclarecer expectativas.
  
- **Processo de Criação**: Inicialmente desafiador, o engenheiro de produto melhorou na criação de testes e na comunicação com os programadores antes da codificação. A equipe desenvolveu um modelo de teste que evoluiu ao longo do tempo, atendendo às necessidades de programadores e testadores.

- **Automação**: Os testes de aceitação eram automatizados rapidamente, muitas vezes simultaneamente ao desenvolvimento das histórias. Esses testes apoiavam o desenvolvimento, alimentavam o conjunto de regressão e auxiliavam na identificação de testes exploratórios.

- **Objetivos dos Testes de Aceitação**:
  1. **Apoio ao Desenvolvimento**: Fornecendo testes à equipe antes da codificação.
  2. **Base para Automação e Testes Exploratórios**: Servindo como base para o conjunto de regressão e gerando ideias para testes exploratórios.
  3. **Confirmação da Implementação**: Validando se a solução atendia às necessidades do cliente, com o engenheiro de produto verificando a conformidade.

#### Automação de Testes

**Estrutura de Teste Funcional Automatizado**

- **Tecnologia**: Ruby com Watir foi escolhido para a automação funcional devido à sua flexibilidade e personalização.

- **Camadas de Teste**:
  1. **Camada 1**: Incluía Watir e outras classes auxiliares, como loggers.
  2. **Camada 2**: Camada de acesso à página, contendo classes para interagir com páginas específicas (login, criação de usuário, etc.). Essas classes não continham dados diretamente, facilitando a reutilização com diferentes conjuntos de dados.
  3. **Camada 3**: Camada de teste que utilizava a Camada 2 para executar testes reais, incluindo a manipulação de mensagens de erro e verificação de resultados esperados.

- **Benefícios**: Permitiu a execução de testes funcionais em compilações noturnas, fornecendo feedback consistente e ajudando na estabilização do sistema à medida que novos testes de unidade eram desenvolvidos.

**Testes de Serviços Web**

- **Desenvolvimento e Teste**: Utilizando Ruby e o framework de teste unitário Test::Unit, a equipe criou um cliente para testar serviços web. A equipe desenvolveu mais de 1.000 casos de teste que foram executados rapidamente, oferecendo uma cobertura significativa.

- **Uso pelo Cliente**: Os clientes inicialmente usaram o cliente de teste fornecido, mas eventualmente desenvolveram seus próprios testes utilizando a interface interativa IRB do Ruby. Isso proporcionou um ambiente exploratório para testar e ganhar confiança na funcionalidade dos serviços.

- **Três Propósitos dos Testes de Serviços Web**:
  1. **Para Programadores**: Auxiliou no desenvolvimento e teste dos clientes.
  2. **Para Testadores**: Automatizou a crítica ao produto, oferecendo eficiência.
  3. **Para Clientes**: Permitiram testes ad hoc usando IRB, aumentando a familiaridade com Ruby e confiança nos testes realizados.

Essas práticas demonstram a importância de testes de aceitação bem definidos e a eficácia da automação em diferentes níveis para suportar o desenvolvimento ágil e garantir a qualidade do software.

### Testes Incorporados e Testes Voltados para Negócios

#### Testes Incorporados

- **Contexto**: O sistema de Monitoramento Remoto de Dados (RDM) incluía um dispositivo embarcado com uma interface administrativa de linha de comando. A equipe usou Ruby para desenvolver testes para essa interface.

- **Automação de Testes**: Testes automatizados foram criados a partir de comandos e expectativas armazenados em uma planilha do Excel. Um script Ruby lia os comandos e comparava as respostas do dispositivo com os resultados esperados. Esse processo reduziu o tempo de execução de testes de 8 horas para 1 hora.

- **Simulador**: Um simulador em Ruby com GUI FOX (FXRuby) foi criado para fornecer dados fictícios ao dispositivo. O simulador permitiu testar a leitura de dados, resposta a condições de erro e geração de alarmes quando dados excediam limites predefinidos. O simulador foi útil tanto para testes da equipe quanto para o desenvolvimento do firmware.

#### Testes Voltados para Negócios que Criticam o Produto

**Testes Exploratórios**

- **Automação e Testes Exploratórios**: Testes exploratórios foram usados para complementar a automação, permitindo a detecção de problemas que os testes automatizados não identificaram. Testes de usabilidade foram realizados, mas não eram um requisito crítico. Testes exploratórios foram amplamente utilizados pelo engenheiro de produto e pelos testadores para verificar a solução e a interface do sistema.

**Testes de Feeds de Dados**

- **Fila JMS**: Para testar a fila JMS, um proxy Java foi desenvolvido para imprimir todos os dados recebidos. Também foi criado um cliente Ruby para processar os dados via pipe no sistema de teste automatizado.

- **E-mails de Alarme**: Um cliente de e-mail Ruby que suportava anexos MIME foi criado para testar o envio automático de e-mails de alarme, que continham informações úteis para teste.

**Testes de Ponta a Ponta**

- **Objetivo**: Testes de ponta a ponta foram necessários para garantir o funcionamento correto do sistema como um todo, desde o início. A integração de simulador, testes de dispositivos embarcados, testes de serviços web e testes de aplicativos resultou em um teste automatizado de todo o sistema.

- **Desafios**: Os testes de ponta a ponta enfrentaram desafios devido à resposta imprevisível do caminho de transmissão via satélite. Um tempo limite foi definido para lidar com problemas de transmissão esporádicos. Se um teste não correspondia ao esperado dentro do tempo limite, ele era considerado falho.

- **Manutenção**: Devido à complexidade e fragilidade dos testes de ponta a ponta, eles não eram mantidos como parte do conjunto de regressão automatizado. No entanto, eram essenciais para verificar o sistema completo devido à natureza do sistema.

Esses testes abrangem um conjunto completo de estratégias para garantir a qualidade e o desempenho do sistema, desde testes incorporados e exploratórios até testes funcionais de ponta a ponta. A combinação dessas abordagens ajudou a equipe a validar a solução de forma eficaz e a lidar com desafios específicos do sistema.

### Teste de Aceitação do Usuário (UAT) e Outras Estratégias de Teste

#### Teste de Aceitação do Usuário (UAT)

- **Contexto**: O UAT é a validação final do produto pelo cliente, crucial para garantir que o produto atende às suas expectativas. No exemplo dado, o cliente estava localizado na França, longe da equipe de desenvolvimento.

- **Primeiro UAT**: Janet facilitou o primeiro UAT no local do cliente, o que ajudou a resolver problemas críticos e aceitar o lançamento. A interação direta foi crucial para o sucesso do teste.

- **Segundo UAT**: A segunda aprovação foi realizada internamente. O cliente colaborou na criação de um conjunto de testes que pudesse executar durante o ciclo de desenvolvimento, o que fez com que o UAT final fosse rápido e sem problemas.

- **Importância da Colaboração**: O envolvimento contínuo do cliente e a comunicação direta foram fundamentais. Mesmo com um proxy de cliente (engenheiro de produto), a interação real foi essencial para o sucesso do UAT.

#### Confiabilidade

- **Desafio da Confiabilidade**: A confiabilidade foi crítica devido à natureza remota e inacessível dos locais monitorados, especialmente em condições extremas. 

- **Testes de Confiabilidade**: Um simulador foi utilizado para testar a estabilidade do sistema em um ambiente separado por semanas, ajudando a identificar e corrigir problemas antes do final do projeto.

#### Documentação

- **Documentação do Código de Teste**: Foi adotado o RDoc para documentar o código de teste em Ruby. Essa ferramenta gerou documentação web das classes e métodos de teste, facilitando a compreensão do que estava sendo testado e como.

- **Relato dos Resultados de Teste**: Para aumentar a visibilidade dos resultados de teste, foi desenvolvido um sistema de registro e relatório com Apache, PHP e MySQL. Esse sistema permitiu que as partes interessadas visualizassem os resultados dos testes e a taxa de aprovação/reprovação.

- **Visualização de Progresso**: Tabelas e gráficos foram criados e exibidos em áreas comuns para tornar o progresso visível para toda a equipe, melhorando a transparência e a comunicação.

#### Usando os Quadrantes de Teste Ágil

- **Integração dos Quadrantes**: O exemplo ilustra como integrar práticas de todos os quatro quadrantes de teste ágil ao longo do projeto. A equipe usou uma combinação de ferramentas e abordagens, desde testes unitários até testes de ponta a ponta e UAT.

- **Planejamento e Prioridades**: Ao planejar epics, lançamentos ou iterações, é essencial trabalhar com a equipe e os clientes para entender as prioridades de negócios e analisar os riscos. Use os quadrantes para identificar e planejar os testes necessários.

- **Arquitetura de Teste**: Invista em uma arquitetura de teste que suporte a complexidade do sistema. Certifique-se de ter os recursos e conhecimentos necessários para testes especializados e escolha ferramentas adequadas para resolver problemas específicos.

- **Retrospectivas e Melhoria Contínua**: Use retrospectivas para avaliar se a equipe tem os recursos necessários e se todos os testes estão sendo especificados e automatizados adequadamente. Experimente diferentes abordagens e ferramentas para encontrar as melhores soluções.

Este capítulo mostra que a combinação de diferentes estratégias de teste e a colaboração próxima com o cliente são fundamentais para o sucesso em projetos ágeis. A abordagem de testar desde a unidade até o sistema completo, junto com uma comunicação eficaz, garante uma entrega de produto de alta qualidade.

### Resumo das Lições Aprendidas do Projeto de Monitoramento Remoto de Dados

Este capítulo explorou como um projeto real utilizou os quatro quadrantes de testes ágeis para superar desafios complexos e garantir uma entrega bem-sucedida. As lições principais incluem:

1. **Escolha e Criação de Ferramentas**:
   - **Importância**: A equipe deve selecionar ou criar ferramentas que resolvam problemas de teste específicos.
   - **Exemplo**: Usar Ruby com Watir para testes funcionais e criar um simulador para testar o dispositivo embarcado.

2. **Combinação de Ferramentas**:
   - **Importância**: Ferramentas comuns, como planilhas e scripts personalizados, podem ser necessárias para realizar testes complexos.
   - **Exemplo**: Utilização de planilhas para armazenar dados de testes e scripts Ruby para interagir com dispositivos e sistemas.

3. **Arquitetura de Teste**:
   - **Importância**: Investir na criação de uma arquitetura de teste que funcione para todos os membros da equipe é crucial.
   - **Exemplo**: Estrutura de teste com várias camadas, incluindo testes funcionais e de serviços da web.

4. **Envolvimento do Cliente**:
   - **Importância**: Manter os clientes envolvidos em todos os tipos de testes, mesmo à distância, é essencial para o sucesso.
   - **Exemplo**: Facilitação do UAT no local do cliente e colaboração contínua para criar conjuntos de testes.

5. **Relatar Resultados de Teste**:
   - **Importância**: Relatar resultados de testes de forma a manter todas as partes interessadas informadas sobre o progresso e as iterações do projeto.
   - **Exemplo**: Uso de um sistema de registro e relatório para fornecer visibilidade sobre os resultados dos testes.

6. **Documentação**:
   - **Importância**: Documentar o que é útil e necessário, sem exagerar.
   - **Exemplo**: Utilização de RDoc para documentar o código de teste e gerar páginas da web com detalhes de testes.

7. **Considerar Todos os Quadrantes de Teste**:
   - **Importância**: Pensar em todos os quatro quadrantes de teste ao longo dos ciclos de desenvolvimento.
   - **Exemplo**: Combinação de testes funcionais, de serviços da web, incorporados e de ponta a ponta.

8. **Aprendizado e Melhoria Contínua**:
   - **Importância**: Usar as lições aprendidas durante os testes para criticar e melhorar o produto nas iterações subsequentes.
   - **Exemplo**: Ajustes e correções baseados no feedback dos testes para otimizar o desenvolvimento.

Essas lições destacam a importância de uma abordagem integrada e bem planejada para testes, colaboração eficaz com o cliente e comunicação transparente para o sucesso em projetos ágeis complexos.