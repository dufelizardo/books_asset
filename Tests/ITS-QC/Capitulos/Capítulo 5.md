# Capítulo 5


### **Chave 1: Conheça Suas Necessidades**

Para o sucesso da automação de testes (AST), entender profundamente suas necessidades e requisitos é fundamental. Este capítulo é o ponto de partida para garantir que você tenha uma base sólida para implementar uma estratégia de teste automatizado eficaz.

#### **Importância de Conhecer suas Necessidades**

1. **Base para Estratégia de Teste Automatizado**
   - Os requisitos servem como a fundação sobre a qual você desenvolverá sua estratégia de teste automatizado. Sem uma compreensão clara dos requisitos, você pode acabar criando uma solução de automação que não atende às necessidades reais do seu sistema ou que não é capaz de medir o sucesso de maneira eficaz.

2. **Criação e Implementação do Programa AST**
   - Os requisitos são essenciais para a criação e implementação do programa AST. Eles guiarão a seleção de ferramentas, o desenvolvimento de scripts de teste e a definição de critérios de sucesso.

3. **Medição de Sucesso**
   - Os requisitos também servirão como linha de base para medir o sucesso do seu programa de automação. Sem requisitos bem definidos, será difícil avaliar se os testes automatizados estão alcançando seus objetivos e se estão agregando valor.

#### **Abordagem de Alto Nível para Coleta de Requisitos**

1. **Determinação das Informações de Requisitos Disponíveis**
   - **Requisitos de Sistema (SUT):** Entenda as especificações do sistema a ser testado. Isso inclui funcionalidades, desempenho esperado e requisitos de segurança.
   - **Requisitos de Teste:** Identifique o que precisa ser testado, quais os critérios de aceitação e quais os cenários de teste relevantes.
   - **Requisitos de Automação:** Determine o que será automatizado e o que será mantido manualmente. Isso pode incluir a escolha das ferramentas de automação e a definição dos scripts de teste.

2. **O que Fazer Quando as Informações Estão Faltando**
   - **Engajamento das Partes Interessadas:** Se informações estão faltando, consulte todas as partes interessadas para obter uma visão mais clara. Isso inclui desenvolvedores, testadores e usuários finais.
   - **Documentação e Análise:** Documente o que você sabe e identifique as lacunas. Use essa documentação como base para discussões adicionais para preencher essas lacunas.
   - **Prototipagem e Experimentação:** Quando os requisitos não são claros, pode ser útil criar protótipos ou realizar experimentações para obter uma compreensão melhor das necessidades.

#### **Determinação dos Requisitos de Teste Automatizado**

- **Análise de Custo-Benefício:** Avalie quais testes trazem mais valor se automatizados. Isso pode incluir testes repetitivos, testes de regressão e testes que são críticos para o negócio.
- **Priorização dos Testes:** Defina quais testes devem ser automatizados primeiro com base na importância e na complexidade.

#### **Documentação e Matriz de Rastreabilidade de Requisitos**

1. **Documentação Centralizada**
   - **Banco de Dados de Requisitos:** Mantenha uma documentação centralizada de todos os requisitos. Isso ajuda na gestão e na comunicação entre as partes envolvidas.
   - **Atualização e Manutenção:** Garanta que a documentação seja atualizada regularmente para refletir as mudanças nos requisitos.

2. **Desenvolvimento de uma Matriz de Rastreabilidade**
   - **Definição e Implementação:** Desenvolva uma matriz de rastreabilidade que vincule requisitos específicos a casos de teste automatizados. Isso garante que todos os requisitos sejam cobertos pelos testes.
   - **Monitoramento e Ajuste:** Monitore continuamente a matriz para assegurar que os testes permaneçam alinhados com os requisitos e ajuste conforme necessário.

### **Resumindo**

O sucesso da automação de testes começa com uma compreensão clara e completa dos requisitos. Sem essa base, será difícil desenvolver uma estratégia de teste automatizado eficaz. A coleta, documentação e rastreabilidade dos requisitos são essenciais para garantir que sua automação de testes atenda às necessidades do sistema e agregue valor ao processo de teste.

Nos capítulos subsequentes, abordaremos as outras chaves essenciais para a implementação bem-sucedida da automação de testes, cada uma delas interligada e alimentando-se mutuamente para garantir um programa de automação robusto e eficaz.


### **5.1 Compreender os Requisitos de Suporte AST**

Para implementar um programa de Automação de Testes de Software (AST) eficaz, é essencial compreender e documentar os requisitos de suporte que irão orientar o desenvolvimento e a execução do programa. Esses requisitos incluem:

1. **Requisitos AUT ou SUT (Sistema Sob Teste)**
2. **Estrutura de Automação e Requisitos de Ferramentas**
3. **Requisitos de Dados AST**
4. **Requisitos do Ambiente AST**
5. **Requisitos do Processo AST**

#### **1. Requisitos AUT ou SUT**

Os requisitos do AUT (Application Under Test) ou SUT são fundamentais para qualquer programa de automação de testes. Eles podem ser:

- **Informais ou Formais:** Incluem especificações de funcionalidade, desempenho, segurança e usabilidade. Muitas vezes, esses requisitos vêm de documentos como especificações de projeto, contratos ou documentação técnica.
- **Obrigações Contratuais:** Podem refletir o que o cliente deseja e aprovou, e o que a equipe de projeto concordou em entregar. Idealmente, o automatizador de teste deve estar envolvido desde o início para ajudar a desenvolver requisitos que são automatizáveis e testáveis.

**Como coletar e entender os requisitos AUT/SUT:**

- **Entendimento do Sistema:** Obtenha uma visão geral dos requisitos funcionais e não funcionais do sistema. Isso pode incluir segurança, desempenho e usabilidade. Leia documentos relevantes e participe de reuniões para obter uma visão clara da lógica de negócios e dos fluxos funcionais.
- **Entendimento do Escopo:** Determine quais tipos de testes são necessários, como testes funcionais, de desempenho, de segurança, de usabilidade, etc. Identifique quais requisitos são testáveis e quais precisam ser detalhados para facilitar a automação.

**Exemplo:** Um requisito vago como “a aplicação deve ser compatível com a norma ANSI/C++” deve ser detalhado para se tornar testável e automatizável.

#### **2. Estrutura de Automação e Requisitos de Ferramentas**

Após compreender os requisitos do SUT, o próximo passo é identificar os requisitos para a estrutura de automação e as ferramentas necessárias. 

- **Estrutura de Automação (ASTF):** Avalie quais funcionalidades a estrutura deve oferecer para suportar a automação. Pode incluir capacidades como integração com outras ferramentas, suporte para diferentes tipos de testes e facilidade de uso.
- **Requisitos de Ferramentas:** Determine quais ferramentas de automação serão necessárias e como elas se integrarão com a estrutura existente. Considere se a ferramenta será usada sozinha ou como parte de uma estrutura maior.

**Como definir os requisitos da estrutura e das ferramentas:**

- **Identificação de Requisitos:** Liste os requisitos que a estrutura de automação precisa atender, baseando-se nas necessidades de teste e nas tecnologias usadas no SUT.
- **Estudo de Caso e Exemplos:** Consulte estudos de caso e exemplos de requisitos de estruturas de teste automatizado para adaptar às suas necessidades específicas.

**Exemplo:** Se você precisa de uma ferramenta que suporte testes de desempenho e integração contínua, garanta que a estrutura de automação e as ferramentas escolhidas atendam a essas necessidades.

#### **3. Requisitos de Dados AST**

Os dados necessários para a automação de testes são críticos. Eles podem incluir dados de entrada para os testes, dados esperados e dados de configuração.

**Como gerenciar os requisitos de dados:**

- **Identificação de Dados Necessários:** Determine quais dados serão usados durante os testes e como serão gerados e gerenciados.
- **Segurança e Privacidade:** Garanta que os dados estejam seguros e que a privacidade seja mantida, especialmente se dados sensíveis estiverem envolvidos.

**Exemplo:** Se o teste envolve a verificação de uma funcionalidade com diferentes conjuntos de dados, você precisa de um mecanismo para gerar e gerenciar esses conjuntos de dados.

#### **4. Requisitos do Ambiente AST**

O ambiente em que os testes automatizados serão executados deve ser configurado adequadamente. Isso inclui:

- **Hardware e Software:** Defina as especificações de hardware e software necessárias para suportar a automação.
- **Configuração do Ambiente de Teste:** Configure ambientes de teste que reproduzam as condições reais em que o SUT operará.

**Como definir os requisitos do ambiente:**

- **Configuração e Manutenção:** Certifique-se de que o ambiente de teste esteja configurado corretamente e que possa ser mantido ao longo do ciclo de vida do teste.
- **Simulação de Condições Reais:** O ambiente de teste deve simular as condições reais o mais próximo possível.

**Exemplo:** Se o teste precisa ser executado em várias plataformas, configure o ambiente para suportar essas plataformas.

#### **5. Requisitos do Processo AST**

Os processos associados à automação de testes também devem ser bem definidos. Isso inclui:

- **Processos de Teste:** Defina como os testes serão executados, monitorados e relatados.
- **Integração com Outros Processos:** Garanta que os processos de automação se integrem com processos de desenvolvimento e outros processos de teste.

**Como definir os requisitos do processo:**

- **Documentação e Procedimentos:** Documente os procedimentos para a execução dos testes e a gestão dos resultados.
- **Melhoria Contínua:** Estabeleça um processo para revisar e melhorar continuamente os procedimentos de automação.

**Exemplo:** Defina como os resultados dos testes serão registrados, analisados e usados para melhorar o software.

### **Resumo**

Compreender e documentar os requisitos de suporte para a automação de testes é crucial para garantir que a automação seja bem-sucedida. Isso inclui entender os requisitos do sistema, definir os requisitos para a estrutura e ferramentas de automação, gerenciar os dados de teste, configurar o ambiente adequado e definir os processos de automação. Ao seguir essas diretrizes, você estará preparado para criar uma estratégia de automação eficaz e alinhada com as necessidades do seu projeto.

### **5.1 Compreender os Requisitos de Suporte AST**

Para implementar com sucesso um programa de Automação de Testes de Software (AST), é essencial entender e documentar os requisitos de suporte que orientarão o desenvolvimento e a execução do programa. Esses requisitos incluem:

1. **Requisitos AUT ou SUT (Sistema Sob Teste)**
2. **Estrutura de Automação e Requisitos de Ferramentas**
3. **Requisitos de Dados AST**
4. **Requisitos do Ambiente AST**
5. **Requisitos do Processo AST**

#### **1. Requisitos AUT ou SUT**

Os requisitos do AUT (Application Under Test) ou SUT são a base para qualquer programa de automação de testes e podem ser:

- **Informais ou Formais:** Podem vir de especificações de projeto, contratos ou documentação técnica, e cobrem aspectos funcionais, de desempenho, segurança e usabilidade.
- **Obrigações Contratuais:** Refletem o que o cliente deseja e o que foi acordado no contrato. A participação do automatizador de testes desde o início pode ajudar a garantir que esses requisitos sejam automação e testáveis.

**Como Coletar e Entender os Requisitos AUT/SUT:**

- **Entendimento do Sistema:** Obtenha uma visão geral dos requisitos funcionais e não funcionais, como segurança e desempenho. Revise a documentação relevante e participe de reuniões para entender a lógica de negócios e os fluxos funcionais.
- **Entendimento do Escopo:** Determine quais tipos de testes são necessários (funcionais, desempenho, segurança, etc.) e identifique quais requisitos são testáveis e quais precisam de mais detalhes.

**Exemplo:** Um requisito vago como “a aplicação deve ser compatível com a norma ANSI/C++” deve ser detalhado para se tornar testável e automatizável.

#### **2. Estrutura de Automação e Requisitos de Ferramentas**

Após entender os requisitos do SUT, identifique os requisitos para a estrutura de automação e as ferramentas necessárias:

- **Estrutura de Automação (ASTF):** Avalie as funcionalidades necessárias na estrutura, como integração com outras ferramentas e suporte para diferentes tipos de testes.
- **Requisitos de Ferramentas:** Determine quais ferramentas serão necessárias e como elas se integrarão com a estrutura existente. Considere se a ferramenta será usada isoladamente ou como parte de uma estrutura maior.

**Como Definir os Requisitos da Estrutura e das Ferramentas:**

- **Identificação de Requisitos:** Liste os requisitos que a estrutura de automação precisa atender, com base nas necessidades de teste e nas tecnologias usadas no SUT.
- **Estudo de Caso e Exemplos:** Consulte estudos de caso e exemplos para adaptar os requisitos à sua situação.

**Exemplo:** Se você precisa de uma ferramenta que suporte testes de desempenho e integração contínua, garanta que a estrutura de automação e as ferramentas escolhidas atendam a essas necessidades.

#### **3. Requisitos de Dados AST**

Os dados necessários para a automação de testes incluem dados de entrada, dados esperados e dados de configuração.

**Como Gerenciar os Requisitos de Dados:**

- **Identificação de Dados Necessários:** Determine quais dados serão usados durante os testes e como serão gerenciados.
- **Segurança e Privacidade:** Assegure que os dados estejam protegidos e que a privacidade seja mantida, especialmente em casos de dados sensíveis.

**Exemplo:** Se o teste precisa verificar uma funcionalidade com vários conjuntos de dados, crie um mecanismo para gerar e gerenciar esses dados.

#### **4. Requisitos do Ambiente AST**

O ambiente onde os testes serão executados deve estar configurado adequadamente:

- **Hardware e Software:** Defina as especificações de hardware e software necessárias para suportar a automação.
- **Configuração do Ambiente de Teste:** Configure ambientes que simulem as condições reais do SUT.

**Como Definir os Requisitos do Ambiente:**

- **Configuração e Manutenção:** Assegure que o ambiente esteja corretamente configurado e possa ser mantido durante o ciclo de vida do teste.
- **Simulação de Condições Reais:** O ambiente de teste deve simular o mais próximo possível as condições reais.

**Exemplo:** Se o teste precisa ser realizado em várias plataformas, configure o ambiente para suportar essas plataformas.

#### **5. Requisitos do Processo AST**

Os processos associados à automação de testes devem ser claramente definidos:

- **Processos de Teste:** Estabeleça como os testes serão executados, monitorados e relatados.
- **Integração com Outros Processos:** Garanta que os processos de automação se integrem com outros processos de desenvolvimento e teste.

**Como Definir os Requisitos do Processo:**

- **Documentação e Procedimentos:** Documente os procedimentos para execução dos testes e gestão dos resultados.
- **Melhoria Contínua:** Estabeleça um processo para revisão e melhoria contínua dos procedimentos de automação.

**Exemplo:** Defina como os resultados dos testes serão registrados, analisados e usados para melhorar o software.

### **Resumo**

Compreender e documentar os requisitos de suporte para a automação de testes é fundamental para garantir uma automação bem-sucedida. Isso inclui entender os requisitos do sistema, definir os requisitos para a estrutura e ferramentas de automação, gerenciar os dados de teste, configurar o ambiente adequado e definir os processos de automação. Seguir essas diretrizes ajudará a criar uma estratégia de automação eficaz, alinhada com as necessidades do projeto.


### Requisitos do Ambiente de Teste

O ambiente de teste é um componente crucial para o sucesso da automação de testes, englobando todos os elementos que suportam o esforço de teste, como dados, hardware, software, e requisitos de rede e instalação. Um planejamento adequado para o ambiente de teste é essencial para garantir que todos os testes sejam realizados de forma eficaz e precisa. A seguir, detalhamos os principais aspectos a serem considerados ao definir e configurar o ambiente de teste.

#### **1. Elementos do Ambiente de Teste**

**1.1 Dados de Teste:**
- **Armazenamento e Arquivamento:** Garanta que haja um mecanismo adequado para arquivar dados grandes, como arquivos de log. Pode ser necessário utilizar unidades de fita, CD-R, ou outras formas de armazenamento.
- **Gerenciamento de Dados:** Assegure que os dados de teste estejam acessíveis e bem gerenciados. Inclua dados de entrada, dados esperados e dados de configuração.

**1.2 Hardware:**
- **Computadores:** Identifique a quantidade e os tipos de computadores necessários para a execução dos testes. Certifique-se de que haja capacidade suficiente para suportar o número de testes e a carga esperada.
- **Componentes Adicionais:** Inclua dispositivos periféricos, como impressoras, se necessários para os testes. Considere também a necessidade de hardware específico, como unidades removíveis para recuperação de dados.

**1.3 Software:**
- **Sistemas Operacionais e Aplicações:** Identifique quais sistemas operacionais e softwares são necessários para o ambiente de teste. Inclua software de suporte, ferramentas de teste, e quaisquer aplicativos específicos requeridos pelos testes.
- **Ferramentas de Automação:** Determine o número de licenças necessárias para ferramentas de teste automatizado e outros softwares relevantes, como VMware para virtualização.

**1.4 Requisitos de Rede:**
- **Infraestrutura de Rede:** Identifique a configuração da rede necessária, incluindo conexões de Internet, linhas alugadas, modems e protocolos diversos.
- **Servidores e Componentes de Rede:** Determine o número de servidores, sistemas operacionais de servidor, e bancos de dados necessários para o ambiente de teste.

**1.5 Requisitos de Instalação e Configuração:**
- **Scripts e Configuração:** Considere os scripts necessários para configurar o ambiente e o banco de testes. Inclua scripts para configuração de hardware e software.
- **Certificados de Segurança:** Avalie a necessidade de certificados de segurança e orçamento para implementá-los.

#### **2. Considerações para Ambientes Virtuais**

**2.1 Benefícios:**
- **Economia de Custos:** Ambientes virtuais podem reduzir custos ao permitir a execução de várias instâncias de sistemas operacionais em um único computador físico.
- **Controle:** Oferecem controle completo sobre o ambiente de teste e facilitam a migração e portabilidade entre diferentes máquinas.

**2.2 Limitações:**
- **Recursos e Suporte:** Alguns protocolos ou recursos específicos do AUT podem não ser suportados por ambientes virtuais. Problemas que ocorrem em um ambiente real podem não se manifestar em um ambiente virtual.

**Exemplo:** O VMware Workstation permite a execução de múltiplas máquinas virtuais em um único PC físico, proporcionando um ambiente controlado e virtualizado.

#### **3. Desenvolvimento do Design do Ambiente de Teste**

**3.1 Coleta de Informações:**
- **Informações do Ambiente de Produção:** Obtenha detalhes sobre o software de suporte, hardware, sistemas operacionais, e características específicas do ambiente de produção do SUT.
- **Arquivamento e Armazenamento:** Identifique requisitos para arquivamento, incluindo hardware para armazenamento de dados grandes.

**3.2 Projeto do Ambiente de Teste:**
- **Layout Gráfico:** Desenvolva um layout gráfico da arquitetura do ambiente de teste, representando todos os componentes e suas interações.
- **Lista de Componentes:** Crie uma lista dos componentes necessários, revisando quais já estão disponíveis, quais podem ser transferidos de outros locais e quais precisam ser adquiridos.

**3.3 Aquisição de Equipamentos:**
- **Lista de Compras:** Inclua quantidades necessárias, preços unitários e custos de manutenção e suporte. Considere a compra de componentes de backup para mitigar o risco de falhas de hardware.

#### **4. Robustez do Ambiente de Teste**

O ambiente de teste deve ser robusto o suficiente para suportar diferentes tipos de testes, incluindo:

- **Testes Funcionais:** Verificação das funcionalidades do sistema conforme especificado.
- **Testes de Estresse:** Avaliação do comportamento do sistema sob condições extremas.
- **Testes de Desempenho:** Medição da performance do sistema em várias condições.

Garantir que o ambiente de teste seja configurado e mantido adequadamente é fundamental para o sucesso dos testes automatizados e para a identificação de possíveis problemas no sistema antes que ele chegue ao ambiente de produção.

### Requisitos de Hardware para o Ambiente de Teste

Para garantir que o ambiente de teste esteja devidamente equipado para suportar a execução de testes automatizados, é fundamental definir claramente os requisitos de hardware necessários. Abaixo está um guia para elaborar uma lista abrangente de requisitos de hardware, incluindo exemplos e considerações importantes.

#### **1. Estrutura da Lista de Requisitos de Hardware**

A lista de requisitos de hardware deve conter informações detalhadas sobre os itens necessários para o ambiente de teste. Aqui está uma estrutura recomendada para a lista:

- **Nome do Hardware:** Identificação clara do componente.
- **Quantidade Necessária:** Número de unidades necessárias.
- **Descrição:** Detalhes técnicos e especificações do hardware.

**Exemplo de Lista de Requisitos de Hardware:**

| Nome do Hardware       | Quantidade Necessária | Descrição                                         |
|------------------------|------------------------|---------------------------------------------------|
| Servidor de Teste      | 5                      | Servidor com processador Intel Xeon, 32GB RAM, 1TB SSD |
| Estação de Trabalho    | 10                     | PC com processador i7, 16GB RAM, 512GB SSD       |
| Switch de Rede Gigabit  | 2                      | Switch com 24 portas Gigabit Ethernet             |
| Unidade de Backup      | 1                      | Unidade de fita LTO-8 para armazenamento de backup|
| Adaptador de Vídeo     | 2                      | Adaptador para suporte a resoluções 4K            |
| Impressora de Teste    | 1                      | Impressora laser a cores com capacidade de duplex |

#### **2. Identificação e Aquisição de Hardware**

**2.1 Hosts e Equipamentos Especializados:**
- **Servidores:** Determine o número de servidores necessários, considerando a carga esperada dos testes e os requisitos de desempenho.
- **Estações de Trabalho:** Defina a quantidade de PCs ou estações de trabalho necessárias para os testadores e desenvolvedores.
- **Equipamentos Especiais:** Inclua quaisquer equipamentos especializados que possam ser necessários, como impressoras de teste ou unidades de backup.

**2.2 Configuração de Rede:**
- **Switches e Roteadores:** Especifique os componentes de rede necessários, incluindo switches e roteadores, para suportar a comunicação entre os dispositivos no ambiente de teste.
- **Cabos e Conectores:** Inclua os cabos e conectores necessários para conectar todos os componentes de hardware.

**2.3 Considerações de Compra e Logística:**
- **Tempo de Entrega:** Itens como servidores e equipamentos especializados podem ter tempos de entrega mais longos. Planeje a aquisição com antecedência para evitar atrasos.
- **Customização e Configuração:** Alguns equipamentos podem precisar de configuração ou customização especial. Considere isso no planejamento.

#### **3. Exemplos de Hardware para Diferentes Tipos de Teste**

**3.1 Testes de Desempenho e Estresse:**
- **Servidores de Alto Desempenho:** Equipamentos com processadores rápidos, grande quantidade de RAM e armazenamento rápido são necessários para simular cargas pesadas e avaliar o desempenho sob estresse.
- **Unidades de Backup:** Para armazenar grandes volumes de dados gerados durante testes de estresse.

**3.2 Testes Funcionais e de Integração:**
- **Estações de Trabalho:** PCs com boa capacidade de processamento para execução de testes funcionais e integração contínua.
- **Adaptadores de Vídeo:** Para suportar a execução de testes que exigem alta resolução gráfica.

**3.3 Testes de Segurança e Conectividade:**
- **Equipamentos de Rede:** Switches e roteadores para testar a segurança e a integridade da comunicação entre diferentes componentes do sistema.

#### **4. Revisão e Atualização da Lista**

A lista de requisitos de hardware deve ser revisada e atualizada regularmente para garantir que atenda às necessidades do ambiente de teste conforme o projeto evolui. Considere realizar revisões periódicas para ajustar a lista conforme necessário, especialmente se houver mudanças nos requisitos do teste ou no escopo do projeto.

### **Resumo**

Definir os requisitos de hardware é um passo crucial para garantir que o ambiente de teste suporte adequadamente os testes automatizados. Uma lista bem elaborada, que inclua o nome do hardware, a quantidade necessária e uma descrição detalhada, ajudará a equipe do projeto a adquirir e configurar os equipamentos necessários de forma eficiente e eficaz. Certifique-se de considerar tempos de entrega e a necessidade de customização ao planejar a aquisição do hardware.

### Requisitos de Software para o Ambiente de Teste

Para garantir que o ambiente de teste esteja preparado para executar os testes automatizados, é fundamental identificar e documentar todos os requisitos de software necessários. Abaixo estão os principais componentes a serem considerados e uma estrutura para criar uma folha de requisitos de software.

#### **1. Componentes dos Requisitos de Software**

1. **Sistemas Operacionais**
   - **Versões:** Identifique as versões dos sistemas operacionais necessários, incluindo os níveis de patch e atualizações de segurança.
   - **Compatibilidade:** Garanta que o software de teste e o AUT (Application Under Test) sejam compatíveis com os sistemas operacionais especificados.

2. **Protocolos de Comunicação de Rede**
   - **Protocolos Necessários:** Especifique os protocolos de comunicação utilizados pelo AUT e os protocolos que precisam ser suportados pelos testes, como TCP/IP, UDP, DDS, etc.
   - **Configuração de Rede:** Inclua detalhes sobre como os protocolos devem ser configurados e quaisquer requisitos específicos para a rede.

3. **Idiomas**
   - **Idiomas de Programação:** Liste os idiomas de programação utilizados para o desenvolvimento do AUT e os idiomas suportados pelas ferramentas de automação.
   - **Idiomas de Teste:** Identifique quaisquer idiomas específicos usados nas scripts de teste ou na configuração do ambiente de teste.

4. **Compiladores**
   - **Tipos e Versões:** Especifique os compiladores necessários para construir e executar o AUT. Inclua detalhes sobre as versões e as configurações necessárias.
   - **Compatibilidade:** Verifique a compatibilidade entre os compiladores e o ambiente de teste.

5. **Ferramentas de Teste Automatizado**
   - **Ferramentas Necessárias:** Identifique as ferramentas de teste automatizado que serão utilizadas, como frameworks de teste, ferramentas de gerenciamento de testes e ferramentas de integração contínua.
   - **Configuração e Licenciamento:** Documente qualquer requisito de configuração ou licenciamento associado a essas ferramentas.

#### **2. Exemplo de Folha de Requisitos de Software**

Aqui está um exemplo de como uma folha de requisitos de software pode ser organizada:

| Categoria                         | Nome do Software            | Versão/Requisitos          | Descrição                                                                                   |
|-----------------------------------|------------------------------|----------------------------|-------------------------------------------------------------------------------------------|
| **Sistema Operacional**            | Windows 10 Pro               | Versão 21H2, Patch de Junho | Sistema operacional para execução de testes e AUT.                                        |
| **Protocolos de Comunicação**      | TCP/IP, UDP                  | --                         | Protocolos para comunicação de rede necessários para o AUT e testes de rede.              |
| **Idiomas**                       | C++, Java, Python            | --                         | Idiomas de programação usados no desenvolvimento do AUT e scripts de teste.                |
| **Compiladores**                   | GCC, Visual Studio            | GCC 9.3, VS 2019           | Compiladores necessários para construir o AUT e suportar o desenvolvimento de testes.      |
| **Ferramentas de Teste Automatizado** | Selenium, JUnit, JIRA       | Selenium 4.0, JUnit 5.7    | Ferramentas de automação e gerenciamento de testes.                                         |

#### **3. Considerações Adicionais**

- **Atualizações e Manutenção:** Mantenha os requisitos de software atualizados, especialmente para sistemas operacionais e ferramentas que podem receber atualizações regulares.
- **Compatibilidade:** Certifique-se de que todos os componentes de software são compatíveis entre si e com o ambiente de teste.
- **Documentação e Licenciamento:** Inclua informações sobre a documentação do software e os requisitos de licenciamento para garantir que todos os aspectos legais e de suporte sejam atendidos.

#### **4. Revisão e Atualização dos Requisitos**

A folha de requisitos de software deve ser revisada periodicamente para assegurar que continua a atender às necessidades do ambiente de teste e do AUT. Ajuste os requisitos conforme necessário para refletir mudanças no software, atualizações de versão ou novos requisitos de teste.

### **Resumo**

Definir e documentar os requisitos de software é crucial para garantir que o ambiente de teste suporte adequadamente os testes automatizados. A folha de requisitos deve incluir detalhes sobre sistemas operacionais, protocolos de comunicação, idiomas, compiladores e ferramentas de teste. Manter essa documentação atualizada e revisar os requisitos regularmente são práticas essenciais para o sucesso do ambiente de teste.

### Requisitos do Processo AST

Para garantir a eficácia do programa de Automação de Testes de Software (AST), é essencial compreender os requisitos do processo AST. Esses requisitos envolvem entender a abordagem de teste, a cultura corporativa, a tecnologia, o orçamento, e a programação, entre outros fatores. Aqui está um detalhamento dos principais aspectos a considerar:

#### **1. Fases de Testes**

- **Expectativas de Teste:** Determine as expectativas da gestão e do cliente para o tipo de teste a ser realizado. Verifique se há necessidade de uma fase de teste de aceitação do usuário e quais são os marcos e entregas esperados.
- **Fases Previstas:** Entenda as fases de teste propostas, como testes unitários, testes de integração, testes de sistema e testes de aceitação. Refinar o planejamento AST de acordo com essas fases é crucial para alinhar a automação com as expectativas.

**Exemplo:** Se a fase de teste de aceitação do usuário é necessária, defina claramente os critérios e a metodologia a ser seguida.

#### **2. Lições Aprendidas**

- **Experiências Anteriores:** Revise problemas ou lições aprendidas de projetos de teste anteriores semelhantes. Utilize essas informações para ajustar e melhorar as práticas e expectativas de teste atuais.
- **Aplicação Prática:** Aplique o conhecimento adquirido para prevenir a repetição de erros passados e ajustar as abordagens de teste conforme necessário.

**Exemplo:** Se em projetos anteriores foram encontrados problemas de integração que não foram detectados precocemente, considere uma abordagem de integração contínua para identificar esses problemas mais cedo.

#### **3. Nível de Esforço**

- **Complexidade do Projeto:** Avalie o nível de esforço necessário para construir o Sistema Sob Teste (SUT). Considere o número de desenvolvedores, a complexidade da solução, e se será uma solução completa ou uma versão reduzida.
- **Recursos Necessários:** Estime os recursos necessários para testes baseados na complexidade e no tamanho do projeto.

**Exemplo:** Um projeto complexo pode exigir mais tempo e recursos para testes de integração e performance, enquanto uma solução mais simples pode ser testada com menos recursos.

#### **4. Opções de Tecnologia**

- **Tecnologias Selecionadas:** Identifique as tecnologias utilizadas no desenvolvimento do sistema, como arquitetura de aplicativo (desktop, cliente-servidor, web) e quaisquer problemas potenciais associados a elas.
- **Escolha de Ferramentas:** Use essas informações para escolher ferramentas de teste adequadas e estratégias de teste que se alinhem com a tecnologia do SUT.

**Exemplo:** Se o SUT é um aplicativo web, considere ferramentas de automação que suportam testes de interface web e protocolos HTTP.

#### **5. Orçamento**

- **Restrições Orçamentárias:** Determine o orçamento disponível para o desenvolvimento e testes do sistema. O orçamento pode influenciar o tipo de testes que podem ser realizados e as ferramentas que podem ser usadas.
- **Adaptação do Orçamento:** Ajuste o orçamento de teste conforme necessário para alinhar com as alocações financeiras disponíveis.

**Exemplo:** Se o orçamento é limitado, pode ser necessário priorizar testes de alta prioridade e usar ferramentas de código aberto em vez de soluções comerciais.

#### **6. Programação**

- **Cronograma:** Verifique o tempo alocado para o desenvolvimento e testes. Entenda os prazos e como eles afetam o planejamento dos testes.
- **Ajuste de Cronograma:** Adapte o cronograma de teste para garantir que os testes possam ser executados de forma eficaz dentro dos prazos estabelecidos.

**Exemplo:** Se há uma data limite crítica para o lançamento, priorize testes essenciais e adie testes menos críticos, se necessário.

#### **7. Solução Faseada**

- **Implementação em Fases:** Determine se a solução será implementada em fases ou como uma grande versão. Ajuste o planejamento de testes para se alinhar com a abordagem de implementação faseada.
- **Fases e Prioridades:** Compreenda as fases e prioridades do desenvolvimento para garantir que os testes estejam alinhados com as iterações do desenvolvimento.

**Exemplo:** Para uma solução faseada, planeje testes de integração e regressão para cada fase e ajuste os testes conforme a funcionalidade é incrementada.

#### **8. Entendimento da Cultura e Processos Corporativos**

- **Cultura Corporativa:** Conheça a cultura e os processos de desenvolvimento e teste da organização. Entenda quem é responsável pelos processos e como a equipe de testes contribui para o processo de desenvolvimento.
- **Melhoria de Processos:** Se a melhoria de processos é um objetivo importante, considere como o programa AST pode se alinhar com essas metas.

**Exemplo:** Se a organização valoriza a melhoria contínua, implemente práticas de feedback e revisão contínua nos processos de teste.

#### **9. Tipo de Equipe de Testes**

- **Estrutura da Equipe:** Determine se a equipe de testes é independente ou integrada à equipe de desenvolvimento. Avalie se há validação e verificação independentes (IV&V) envolvidas.
- **Papéis e Responsabilidades:** Compreenda os papéis e responsabilidades da equipe de teste, incluindo sua responsabilidade pelo lançamento final e critérios de aceitação.

**Exemplo:** Se a equipe de testes é responsável pelo lançamento final, estabeleça processos claros para revisão e aprovação de qualidade.

#### **10. Tipo de Processo de Desenvolvimento**

- **Metodologia de Desenvolvimento:** Entenda o tipo de processo de desenvolvimento (extremo, ágil, orientado a testes) e como ele influencia os métodos de teste.
- **Adaptação dos Métodos de Teste:** Adapte os métodos de teste para se alinharem com o processo de desenvolvimento em uso.

**Exemplo:** Em um ambiente ágil, use métodos de teste ágeis e integração contínua para acompanhar o ritmo rápido de desenvolvimento.

### **Resumo**

Compreender os requisitos do processo AST é crucial para o sucesso da automação de testes. Isso inclui entender as fases de testes, lições aprendidas, nível de esforço, opções de tecnologia, orçamento, programação, solução faseada, cultura corporativa, estrutura da equipe de testes e tipo de processo de desenvolvimento. Ao abordar esses aspectos, você pode garantir que o programa de automação de testes seja bem planejado e eficaz, alinhando-se com as necessidades e expectativas do projeto.

### Informações Adicionais em Apoio aos Requisitos AST

Para garantir uma automação de testes eficiente e bem-sucedida, é crucial acessar e revisar toda documentação e informações relevantes. Aqui estão os principais tipos de informações adicionais que podem apoiar os requisitos de Automação de Testes de Software (AST):

#### 1. Procedimentos de Teste Manual

**Importância:** Os procedimentos de teste manual, se disponíveis, fornecem uma base sólida para entender a funcionalidade do Sistema Sob Teste (SUT) e podem ajudar na criação de casos de teste automatizados.

**Como Utilizar:**
- **Análise de Testes Manuais:** Revise os procedimentos para identificar os passos e a lógica dos testes manuais. Isso pode ajudar a entender o comportamento esperado do sistema e criar scripts de teste automatizados baseados nos mesmos.
- **Desenvolvimento de Testes Automatizados:** Se não houver procedimentos manuais existentes, você precisará criar os procedimentos de teste do zero. Baseie-se em informações disponíveis e desenvolva um conjunto de casos de teste que cobrem as funcionalidades essenciais do SUT.

**Exemplo:** Se um procedimento de teste manual descreve um fluxo de trabalho de compra em um aplicativo e-commerce, você pode criar scripts automatizados que simulam esse fluxo de trabalho, incluindo a seleção de produtos, adição ao carrinho e finalização da compra.

#### 2. Documentos de Projeto

**Importância:** Documentos de design fornecem detalhes essenciais sobre a arquitetura e a implementação do sistema, ajudando na criação de testes que validam a integridade do software.

**Tipos de Documentos:**

- **Documento de Projeto do Sistema e Software (SDD):** 
  - **Descrição:** Contém informações sobre o design arquitetônico, de interface, de dados e de procedimento do sistema.
  - **Uso:** Ajuda a entender como os componentes do sistema interagem e quais são os requisitos de interface e dados, essencial para criar testes que validem a integração e a funcionalidade.

- **Documento de Design de Interface (IDD):**
  - **Descrição:** Detalha o design e as características das interfaces entre sistemas e componentes.
  - **Uso:** Fornece informações sobre como diferentes partes do sistema se comunicam, o que é crucial para testes de integração e verificação de interfaces.

- **Documento de Projeto de Banco de Dados (DDD):**
  - **Descrição:** Descreve o design do banco de dados, incluindo estrutura e métodos de acesso aos dados.
  - **Uso:** Necessário para testes que verificam a integridade e a manipulação dos dados, como testes de CRUD (Create, Read, Update, Delete) e testes de desempenho do banco de dados.

**Exemplo:** Se o SDD descreve uma API que o sistema usa para comunicação entre módulos, você pode criar testes automatizados que verificam se a API responde conforme o esperado em diferentes cenários.

#### 3. Protótipos

**Importância:** Protótipos fornecem uma visualização antecipada do sistema ou de partes dele, permitindo feedback precoce e ajustes antes da implementação final.

**Como Utilizar:**
- **Desenvolvimento e Teste de Protótipos:** Use protótipos para validar a funcionalidade e obter feedback dos usuários sobre a usabilidade e a interface do sistema. Isso pode informar a criação de testes automatizados que alinhem-se com os requisitos reais e a experiência do usuário.
- **Identificação de Problemas de Compatibilidade:** Protótipos ajudam a identificar problemas potenciais com ferramentas de teste automatizado e ajustar a abordagem de teste antes da entrega final.

**Exemplo:** Se um protótipo mostra um novo recurso de visualização de dados, você pode criar testes automatizados que verifiquem se a visualização está correta, se os dados são apresentados conforme esperado e se as interações do usuário são suaves.

#### **Resumo**

- **Procedimentos de Teste Manual:** Útil para entender a lógica dos testes e criar scripts automatizados. Se não disponíveis, você precisará criar os testes manualmente.
- **Documentos de Projeto:** Fornecem detalhes críticos sobre o design e a arquitetura do sistema, essenciais para criar testes precisos e abrangentes.
- **Protótipos:** Permitem a visualização antecipada do sistema e ajudam a identificar problemas e ajustar a automação de testes antes da implementação final.

Ao revisar e usar essas informações, você pode criar um conjunto de testes automatizados mais robusto e alinhado com as expectativas e necessidades do projeto.


### Quando as Informações Não Estão Disponíveis

Quando enfrentamos a ausência de informações claras sobre o Sistema Sob Teste (SUT), a abordagem precisa ser estratégica e flexível. Aqui estão algumas táticas eficazes para coletar informações e desenvolver uma estratégia de automação de testes (AST) quando a documentação e o acesso a especialistas são limitados:

#### 1. **Realização de Entrevistas**

Entrevistar stakeholders pode ser um dos métodos mais eficazes para coletar informações quando a documentação é escassa. Aqui estão algumas dicas para conduzir entrevistas eficazes:

1. **Planejamento Adequado:**
   - **Tempo:** Dedique tempo suficiente para entender a profundidade dos requisitos. Não apresse o processo para evitar perder informações cruciais. Uma coleta inicial bem feita pode economizar muito tempo e esforço em fases posteriores.

2. **Definição de Termos:**
   - **Clareza:** Antes de iniciar a entrevista, defina claramente os termos e conceitos que serão usados. Isso ajuda a evitar mal-entendidos e garante que todos os envolvidos tenham a mesma compreensão dos requisitos.

3. **Perguntas Estruturadas:**
   - **Perguntas Amplas e Específicas:** Comece com perguntas abertas para obter uma visão geral e depois refine para perguntas mais específicas com respostas "sim" ou "não" para detalhes mais concretos.

4. **Feedback e Verificação:**
   - **Confirmação:** Durante a entrevista, forneça feedback sobre as respostas para garantir a compreensão correta e ajustar qualquer mal-entendido imediatamente.

5. **Perguntar "Por Quê":**
   - **Exploração:** Use a pergunta "por quê" para aprofundar a compreensão dos requisitos. Isso pode revelar requisitos implícitos e clarificar o raciocínio por trás dos requisitos expressos.

**Exemplo:** Se um cliente afirma que um sistema deve permitir que os usuários "visualizem relatórios", pergunte por que isso é importante, quais tipos de relatórios são esperados, e quais ações o usuário deve poder realizar com esses relatórios.

#### 2. **Aumentando a Base de Conhecimento**

Quando não há documentação, é crucial aumentar seu próprio conhecimento sobre o SUT:

1. **Estudo Independente:**
   - **Exploração do SUT:** Passe tempo interagindo com o SUT, se possível. Realize tarefas comuns para entender seu comportamento e identificar cenários de uso.

2. **Documentação Interna:**
   - **Cenários de Negócio:** Documente os cenários de uso, dados de entrada e saídas esperadas enquanto explora o sistema. Isso ajudará a construir uma base para desenvolver casos de teste.

3. **Protótipos:**
   - **Iterativos:** Use protótipos para experimentar e validar partes do sistema. Isso pode ajudar a descobrir como o sistema se comporta e informar a criação de testes automatizados.

**Exemplo:** Se você está trabalhando com um novo aplicativo de gerenciamento de projetos e não há documentação, explore o aplicativo para entender como os usuários criam e gerenciam projetos. Use isso para criar protótipos de casos de teste que verifiquem a criação de projetos e a interação com tarefas.

#### 3. **Desenvolvimento de Requisitos com Base em um Aplicativo Legado**

Se o novo sistema está sendo desenvolvido com base em um sistema existente, mas sem documentação clara, siga estas etapas:

1. **Seleção de Versão:**
   - **Versão Base:** Escolha uma versão específica do aplicativo legado para ser a base do desenvolvimento do novo sistema. Isso ajuda a garantir que todos os stakeholders estejam alinhados e facilita o rastreamento de defeitos.

2. **Documentação do Legado:**
   - **Documentar Funcionalidades:** Se possível, documente os recursos e o comportamento do aplicativo legado. Inclua descrições detalhadas dos recursos e cenários de teste associados.

3. **Padrões e Especificações:**
   - **Referências:** Procure padrões da indústria ou especificações que possam ser aplicados ao novo sistema. Isso pode fornecer uma base para os requisitos e auxiliar na definição de expectativas.

4. **Comparações e Experiência:**
   - **Aplicações Semelhantes:** Compare o SUT com aplicativos similares para identificar requisitos comuns e melhores práticas. Utilize sua experiência e conhecimento para preencher as lacunas.

5. **Atualizações e Documentação:**
   - **Manutenção de Documentos:** Documente qualquer atualização ou mudança de requisitos à medida que o desenvolvimento avança para manter uma base de conhecimento sólida e minimizar inconsistências.

**Exemplo:** Se você está desenvolvendo um novo sistema de gerenciamento de clientes baseado em um antigo sistema legado, selecione uma versão do legado para referência. Documente como o antigo sistema lida com clientes, e use essa documentação para desenvolver e validar requisitos para o novo sistema.

#### **Resumo**

- **Entrevistas:** Planeje bem, defina termos, comece com perguntas amplas, e dê feedback para garantir uma coleta de requisitos eficaz.
- **Aumento de Conhecimento:** Explore o SUT, documente cenários e use protótipos para entender e testar o sistema.
- **Aplicativo Legado:** Se baseie em uma versão específica do legado, documente suas funcionalidades e compare com padrões da indústria para criar requisitos para o novo sistema.

Implementando essas estratégias, você pode superar a falta de documentação e informações, desenvolvendo uma base sólida para a automação de testes e garantindo que o novo sistema atenda às expectativas dos stakeholders.

### Matriz de Rastreabilidade de Requisitos (RTM)

A Matriz de Rastreabilidade de Requisitos (RTM) é uma ferramenta crucial para o gerenciamento eficaz de requisitos ao longo do ciclo de vida do desenvolvimento de software. Aqui está uma visão geral sobre o que é um RTM, sua importância e como você pode começar a implementá-lo:

#### **O que é um RTM?**

Um RTM é um documento ou ferramenta que mapeia e rastreia a relação entre requisitos, design, desenvolvimento e testes. O objetivo principal de um RTM é garantir que todos os requisitos sejam atendidos e testados, fornecendo uma visão clara da cobertura de testes e da conformidade com os requisitos. Ele também ajuda a gerenciar mudanças e garantir que as alterações nos requisitos sejam refletidas em todos os aspectos do projeto.

#### **Importância do RTM**

1. **Rastreabilidade:**
   - **Cobertura Completa:** Garante que todos os requisitos sejam rastreados até os casos de teste associados, ajudando a garantir que nenhum requisito seja negligenciado.
   - **Gerenciamento de Mudanças:** Facilita a gestão de mudanças nos requisitos, atualizando automaticamente os casos de teste e outras documentações associadas.

2. **Gestão de Requisitos:**
   - **Organização:** Facilita a organização e a priorização dos requisitos, ajudando a identificar quais requisitos são críticos e precisam de mais atenção.
   - **Visibilidade:** Proporciona uma visão clara do status de cada requisito e do progresso do teste, facilitando a comunicação com as partes interessadas.

3. **Eficiência no Teste:**
   - **Cobertura de Teste:** Ajuda a garantir que todos os requisitos sejam testados, reduzindo o risco de bugs e problemas não detectados.
   - **Documentação:** Serve como documentação clara e detalhada sobre quais testes foram realizados e os resultados obtidos.

#### **Componentes de um RTM**

Um RTM pode variar em complexidade, mas geralmente inclui os seguintes componentes:

1. **Identificador do Requisito:**
   - Um identificador único para cada requisito, facilitando a referência e rastreamento.

2. **Descrição do Requisito:**
   - Uma descrição detalhada do requisito, explicando o que é necessário e por quê.

3. **Categoria:**
   - Classificação do requisito (por exemplo, funcional, não funcional, de desempenho).

4. **Caso de Teste:**
   - Referência aos casos de teste que validam o requisito. Isso pode incluir links para documentos ou sistemas de gerenciamento de testes.

5. **Status do Teste:**
   - Resultados dos testes realizados, indicando se o requisito foi aprovado ou reprovado.

6. **Prioridade:**
   - A importância do requisito, ajudando a priorizar o trabalho de teste e desenvolvimento.

#### **Exemplo de RTM**

Aqui está um exemplo simplificado de como um RTM pode ser estruturado:

| ID do Requisito | Descrição do Requisito | Categoria | Caso de Teste | Status do Teste | Prioridade |
|-----------------|-------------------------|-----------|---------------|-----------------|------------|
| REQ-001          | O sistema deve permitir a autenticação de usuários. | Funcional | [Teste de Autenticação](link) | Aprovado | Alta |
| REQ-002          | O sistema deve processar transações em menos de 2 segundos. | Desempenho | [Teste de Desempenho](link) | Reprovado | Alta |
| REQ-003          | O sistema deve fornecer relatórios de erros. | Funcional | [Teste de Relatórios](link) | Aprovado | Média |

#### **Como Implementar um RTM**

1. **Coleta de Requisitos:**
   - Reúna todos os requisitos do projeto, garantindo que estejam claros e completos.

2. **Desenvolvimento do RTM:**
   - Crie o RTM em um formato que se adapte ao seu ambiente, que pode ser um documento simples ou uma ferramenta especializada.

3. **Mapeamento:**
   - Mapeie cada requisito para casos de teste associados. Certifique-se de que todos os requisitos tenham cobertura de teste.

4. **Atualização e Manutenção:**
   - Atualize o RTM conforme os requisitos e casos de teste evoluem. Garanta que o RTM reflita todas as mudanças e novos requisitos.

5. **Automatização:**
   - Considere utilizar ferramentas de gerenciamento de requisitos e testes que possam automatizar o processo de rastreabilidade e fornecer relatórios atualizados.

#### **Conclusão**

Implementar e manter um RTM eficaz é fundamental para garantir que todos os requisitos sejam atendidos e testados adequadamente. Ele proporciona uma visão clara e detalhada do progresso do projeto, facilita a gestão de mudanças e ajuda a assegurar que o sistema atenda às expectativas dos stakeholders. Ao seguir as etapas para desenvolver e utilizar um RTM, você pode melhorar significativamente a eficácia e a eficiência do processo de teste automatizado e do desenvolvimento de software.
